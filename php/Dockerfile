# DOCKERFILE para servidor Apache con PHP
FROM php:8.2-apache

# Instala mysqli, pdo y pdo_mysql
RUN docker-php-ext-install mysqli pdo pdo_mysql

COPY . /var/www/html/app




#DOCKERFILE para servidor apache con PHP
#FROM php:8.2-apache
#Instalacion y habilita la extensión mysqli
#RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
#COPY . /var/www/html/app