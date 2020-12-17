FROM node:13
ENV CI=true

WORKDIR /app
COPY package.json .
RUN yarn install
RUN yarn global add typescript
COPY . .
RUN tsc

CMD ["yarn", "start"]
