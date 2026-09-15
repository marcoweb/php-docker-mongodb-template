FROM mcr.microsoft.com/devcontainers/php:1-8.3-bookworm

RUN pecl install mongodb \
    && docker-php-ext-enable mongodb \
    && rm -rf /tmp/pear
