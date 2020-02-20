FROM php:7.4-fpm-alpine

RUN apk update \
    && apk upgrade 

RUN docker-php-ext-install pdo pdo_mysql

EXPOSE 9000 