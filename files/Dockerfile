FROM php:8.2-apache

COPY . /var/www/html/

RUN a2enmod rewrite

EXPOSE 80
RUN chown -R www-data:www-data /var/www/html \
 && chmod -R 755 /var/www/html
