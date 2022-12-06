FROM composer:latest AS composer
FROM bitnami/php-fpm:8.1
COPY --from=composer /usr/bin/composer /usr/bin/composer
