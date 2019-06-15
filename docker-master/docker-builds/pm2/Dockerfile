FROM node:4-stretch

RUN npm -g install pm2

EXPOSE 80 443 43554

CMD ["pm2-runtime", "start", "pm2.json"]
