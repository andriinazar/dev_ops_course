FROM php:7.4.3-fpm-alpine3.11

# Copy the php config file
COPY ./php/php-fpm.conf /usr/local/etc/php-fpm.d/www.conf

# Copy the application code
COPY . /app

# copy index file
COPY ./public/index.php /var/www/html/

VOLUME ["/app"]
VOLUME ["/www:/var/www"]

