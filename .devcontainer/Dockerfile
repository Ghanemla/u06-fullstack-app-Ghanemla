FROM php:8.2.0

# Install MariaDB client
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get install -y mariadb-client git unzip \ 
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*

# Install php-mysql driver
RUN docker-php-ext-install mysqli pdo pdo_mysql

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install nodejs npm
RUN npm install -g n
RUN n latest

COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer