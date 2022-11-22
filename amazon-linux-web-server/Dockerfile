FROM amazonlinux:latest
RUN yum -y install httpd && echo hello world > /var/www/html/index.html
EXPOSE 80
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]

