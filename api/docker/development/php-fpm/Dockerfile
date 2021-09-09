FROM php:7.4-fpm-alpine

#ENV PHP_INI_DIR /usr/local/etc/php
RUN mv $PHP_INI_DIR/php.ini-development $PHP_INI_DIR/php.ini

COPY ./conf.d /usr/local/etc/php/conf.d

WORKDIR /app
