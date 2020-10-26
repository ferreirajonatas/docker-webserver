FROM php:7.2-fpm-alpine

RUN apk update && apk upgrade && apk add postgresql-dev
RUN docker-php-ext-install pdo_pgsql

#MySQLi
RUN docker-php-ext-install mysqli 
RUN docker-php-ext-enable mysqli
