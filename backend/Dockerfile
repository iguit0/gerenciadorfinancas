FROM node:10.15.3-alpine

WORKDIR /usr/app

COPY package*.json ./

RUN yarn install

COPY . .
