ARG VERSION
FROM php:${VERSION}-fpm

ARG VERSION
RUN apt update && apt install -y unzip git wget
RUN docker-php-ext-install pdo_mysql
RUN cd /usr/local/bin && curl -fsSL https://getcomposer.org/installer | php
RUN mv /usr/local/bin/composer.phar /usr/local/bin/composer
