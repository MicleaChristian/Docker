FROM node:14

WORKDIR /app

COPY . .

RUN npm install prom-client
RUN npm install

COPY package*.json ./

EXPOSE 8080

CMD ["node", "server.js"]
