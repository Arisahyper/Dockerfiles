FROM node:16.13.1-alpine

RUN npm i -g @nestjs/cli
WORKDIR /api
COPY package.json .
RUN npm i

COPY . .
CMD ["npm", "run", "start:dev"]
