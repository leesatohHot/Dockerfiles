FROM alpine:latest
RUN mkdir /wrk
WORKDIR /wrk
RUN apk add --no-cache nodejs
RUN apk add --no-cache npm
RUN apk add --no-cache vim
RUN npm install -g express-generator
RUN express --view=pug
RUN npm install
EXPOSE 3000
