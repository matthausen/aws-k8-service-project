FROM nginx:1.15.9-alpine
COPY nginx.conf /etc/nginx/nginx.conf
WORKDIR /usr/share/nginx/html
COPY www .
RUN ls -laR .
EXPOSE 8100

# FROM node:alpine

#WORKDIR /app
#COPY package.json .
#RUN yarn install
#COPY . .
# RUN yarn build

#EXPOSE 8100

#CMD ["yarn", "start"]