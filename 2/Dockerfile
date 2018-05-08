FROM ubuntu:14.04
MAINTAINER xscorpio Turnbull "xscorpio@outlook.com"
ENV REFRESHED_AT 2018-05-08

RUN apt-get update
RUN apt-get -y -q install nginx

RUN mkdir -p /var/www/html
ADD https://github.com/Crazy-bear/dockerbook-code/tree/master/code/5/sample/nginx/global.conf /etc/nginx/conf.d/
ADD https://github.com/Crazy-bear/dockerbook-code/tree/master/code/5/sample/nginx/nginx.conf /etc/nginx/

EXPOSE 80
