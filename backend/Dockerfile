# API NestJS (usada como serviço "backend" no docker-compose)
FROM node:lts-alpine
WORKDIR /usr/src/app
COPY package*.json ./
ENV NODE_ENV=development
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npx", "nest", "start", "--watch"]