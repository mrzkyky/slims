FROM alpine
Maintainer drajathasan
RUN apk add php7 php7-pdo php7-pdo_mysql php7-gd php7-mbstring php7-apache2 apache2 php7-session php7-json php7-mysqli php7-gettext php7-fileinfo
WORKDIR /var/www/localhost/htdocs
COPY ./httpd.conf /etc/apache2/
EXPOSE 80
CMD  [ "/usr/sbin/httpd", "-D", "FOREGROUND"]
