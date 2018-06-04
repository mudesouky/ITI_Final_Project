FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install -y apache2 wget curl\
    php libapache2-mod-php php-mysql php-curl \
    php-gd php-pear php-imagick php-imap php-mcrypt php-recode php-tidy php-xmlrpc

RUN rm -rf /var/www/html/index.html

CMD ["/usr/sbin/apachectl","-DFOREGROUND"]


