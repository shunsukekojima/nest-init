FROM node:21.1-alpine3.17
ARG API_WORKDIR
WORKDIR ${API_WORKDIR}
ENV TZ Asia/Tokyo
RUN apk update
RUN apk add lsof git vim
RUN yarn global add @nestjs/cli
