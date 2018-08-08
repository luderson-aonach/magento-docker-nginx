FROM nginx:1.13

RUN apt-get update -y && \
    apt-get upgrade -y && \
    apt-get autoclean -y && \
    apt-get autoremove -y

RUN groupmod -g 1000 www-data && \
    usermod -u 1000 -G www-data www-data