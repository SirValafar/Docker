FROM ubuntu:16.04
MAINTAINER TOTO totobronco@hotmail.com
RUN apt-get update
RUN apt-get -y install apache2
EXPOSE 81
CMD /usr/sbin/apache2ctl -D FOREGROUND
