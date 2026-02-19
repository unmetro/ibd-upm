FROM ubuntu

MAINTAINER [unmetro] <[emlome22@gmail.com]>

RUN apt-get update
RUN apt-get install -y apache2

COPY index.html /var/www/html/

EXPOSE 80

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]