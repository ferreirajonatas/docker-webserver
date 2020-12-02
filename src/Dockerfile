FROM php:7.4-fpm-alpine


# install the pdo_mysql extensions to access MySQL.
RUN apk update && apk upgrade \
    && apk add postgresql-dev 
RUN docker-php-ext-install pdo_pgsql

#MySQLi
RUN docker-php-ext-install mysqli 
RUN docker-php-ext-enable mysqli
 