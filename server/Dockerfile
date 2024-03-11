FROM node:14-alpine

COPY ["package.json", "/usr/src/service/server/"]

WORKDIR /usr/src/service/server

RUN yarn install --force

COPY [".", "/usr/src/service/server/"]

CMD ["yarn", "start"]
