FROM node:16.13.1-alpine

RUN npm i -g @nestjs/cli
WORKDIR /api
COPY . .
RUN npm i

CMD ["npm", "run", "start:dev"]
