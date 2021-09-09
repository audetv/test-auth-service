FROM php:7.4-fpm-alpine

#ENV PHP_INI_DIR /usr/local/etc/php
RUN mv $PHP_INI_DIR/php.ini-production $PHP_INI_DIR/php.ini

COPY ./docker/production/php-fpm/conf.d /usr/local/etc/php/conf.d

WORKDIR /app

COPY ./ ./
