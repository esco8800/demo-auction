FROM php:7.4-fpm-alpine

RUN mv $PHP_INI_DIR/php.ini-development $PHP_INI_DIR/php.ini

COPY .docker/common/php-fpm/conf.d usr/local/etc/php/conf.d

WORKDIR /app

COPY ./ ./