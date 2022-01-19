FROM node:14.17.5
WORKERDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT ["node", "server.js"]
