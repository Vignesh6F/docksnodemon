FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=vky
ENV MONGODB_PASSWORD=vky

CMD ["npm", "start"]