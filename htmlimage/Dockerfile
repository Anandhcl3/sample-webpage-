FROM ubuntu:latest
RUN apt-get update && apt-get install apache2 -y
RUN service apache2 start
COPY . /var/www/html


