FROM ubuntu:latest
MAINTAINER LUKASANTOL
LABEL maintainer="antollukas6@gmail.com"
RUN apt-get update 
RUN  apt-get -y install apache2
RUN apt-get -y install apache2-utils
COPY ./index.html /var/www/html
CMD ["apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80

