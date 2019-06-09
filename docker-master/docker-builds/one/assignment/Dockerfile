FROM node:12.4-alpine 

EXPOSE 3000

RUN apk add --update tini
RUN mkdir -p /usr/src/app
COPY package.json package.json 
RUN npm install 
RUN npm cache clean --force
COPY . .
CMD ["/sbin/tini", "--", "node", "./bin/www"]
