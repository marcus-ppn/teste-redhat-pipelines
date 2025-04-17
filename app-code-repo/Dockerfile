FROM node:22-alpine
LABEL maintainer="rodrigo.mota@ppntecnologia.com.br"
LABEL version="1.0"
LABEL description="Dockerfile for Node.js application"
LABEL app="node-app"

WORKDIR /app
COPY package*.json ./
RUN npm install

COPY . .
EXPOSE 8080
CMD ["node", "app.js"]
