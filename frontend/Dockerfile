FROM centos:7
MAINTAINER mohan.korde2@gmail.com
RUN yum -y update
RUN yum -y install httpd
ADD code /var/www/html
EXPOSE 80
ENV BACKENDLB = test
CMD ["apachect","-D","FOREGROUND"]