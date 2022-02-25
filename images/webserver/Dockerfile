FROM php:apache
RUN apt update && apt install -y msmtp
RUN a2enmod rewrite
COPY ./uploads.ini /usr/local/etc/php/conf.d/uploads.ini
COPY msmtprc /etc/msmtprc