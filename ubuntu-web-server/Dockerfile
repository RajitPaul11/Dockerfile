FROM ubuntu 
RUN apt-get update && \ 
apt-get install apache2 -y && \
apt-get install apache2-utils -y && \
apt-get clean 
EXPOSE 80 
ENTRYPOINT ["apache2ctl", "-D", "FOREGROUND"]
