FROM node:8.12.0-alpine

WORKDIR /src
EXPOSE 3000
COPY package*.json ./
RUN npm install
COPY . .

USER 1000

CMD [ "node", "server.js" ]