FROM node:22.13.1-alpine3.20
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT ["node", "server.js"]
