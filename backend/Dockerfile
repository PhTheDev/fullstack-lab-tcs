# React/Vite (usado como serviço "frontend" no docker-compose)
FROM node:lts-alpine
WORKDIR /usr/src/app
COPY package*.json ./
ENV NODE_ENV=development
RUN npm install
COPY . .
EXPOSE 5173
CMD ["npx", "vite", "--host", "0.0.0.0"]