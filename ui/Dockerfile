FROM node:12-slim

WORKDIR /app
COPY ./src/* /app/src/
COPY ./babel.config.js /app
COPY package.json /app/
COPY yarn.lock /app/

RUN yarn install --production
CMD yarn serve


