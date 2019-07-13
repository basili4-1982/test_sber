FROM php:7.1-fpm


RUN curl -sS https://getcomposer.org/installer | \
    php -- --install-dir=/usr/bin/ --filename=composer \
    composer global require "fxp/composer-asset-plugin:^1.3.1"

WORKDIR /app