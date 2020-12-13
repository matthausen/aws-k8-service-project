FROM node:13-alpine as build

WORKDIR /app

COPY package*.json /app/

RUN npm i -g @ionic/cli

RUN npm install

COPY ./ /app/

RUN ionic build && ionic serve