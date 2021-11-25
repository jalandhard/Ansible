FROM centos:latest
MAINTAINER Jalandhar Naidu <jalandhar.naidu@onmobile.com>
RUN yum install httpd -y
COPY index.html  /var/www/html/
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80
