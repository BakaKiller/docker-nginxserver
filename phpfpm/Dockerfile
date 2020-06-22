ARG VERSION
FROM php:${VERSION}-fpm

RUN apt update && apt install unzip git wget
RUN cd /usr/local/bin && curl -fsSL https://getcomposer.org/installer | php
RUN mv /usr/local/bin/composer.phar /usr/local/bin/composer
