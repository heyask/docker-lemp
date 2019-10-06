FROM php:7.2-fpm

RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get autoremove -y

### Use this if project requires deprecated extension ###
# RUN apt-get install libmcrypt-dev -y
# RUN no '' | pecl uninstall mcrypt
# RUN no '' | pecl install mcrypt
# RUN no '' | pecl uninstall apcu_bc
# RUN no '' | pecl install apcu_bc
# RUN docker-php-ext-install mysqli
# RUN docker-php-ext-enable mcrypt apc apcu mysqli
