FROM node:14-alpine as runner

WORKDIR /app/backend

RUN npm install

EXPOSE 3000

ENTRYPOINT ["yarn", "start:dev"]