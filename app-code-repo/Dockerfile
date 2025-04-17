FROM docker.io/library/node:22-slim

LABEL maintainer="rodrigo.mota@ppntecnologia.com.br"
LABEL version="1.0"
LABEL description="Dockerfile for Node.js application"
LABEL app="node-app"

WORKDIR /app
COPY package*.json /app/
RUN npm install

COPY . .
EXPOSE 8080
CMD ["node", "app.js"]