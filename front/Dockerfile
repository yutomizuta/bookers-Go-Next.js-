FROM node:16.13.0-alpine

WORKDIR /usr/src/app

COPY package.json yarn.lock ./
RUN yarn
COPY . .

CMD ["yarn", "dev"]
