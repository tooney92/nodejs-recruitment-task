FROM node:14.15-alpine

WORKDIR /app

COPY ./package.json ./package-lock.json ./
RUN npm install

COPY ./src ./src

CMD ["node", "./src/server.js"]