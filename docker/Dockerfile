
FROM php:8.0-cli

RUN docker-php-ext-install pdo pdo_mysql

COPY ../backend /var/www/html

WORKDIR /var/www/html

CMD [ "php", "-S", "0.0.0.0:8000", "-t", "/var/www/html" ]