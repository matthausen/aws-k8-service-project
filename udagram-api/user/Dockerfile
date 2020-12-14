FROM node:13

WORKDIR /app
COPY package.json .
RUN yarn install
RUN yarn global add typescript
COPY . .
RUN tsc

CMD ["yarn", "start"]