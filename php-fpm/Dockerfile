FROM php:7.1.3-fpm-alpine

RUN addgroup -g 3000 -S app
RUN adduser -S -u 3000 -g app app

COPY ./etc /usr/local/etc
