FROM ubuntu:latest
RUN apt-get update -y
RUN apt-get install apache2 php 
COPY . /var/www/html
ENTRYPOINT apachectl -d FOREGROUND
EXPOSE 80
