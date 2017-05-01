FROM node:6.9.2

EXPOSE 9000
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY ./app/ ./
RUN npm install

CMD ["node", "app.js"]
