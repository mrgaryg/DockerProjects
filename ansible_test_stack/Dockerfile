FROM ubuntu:14.04
 
RUN mkdir /u01 && \
chmod a+xr /u01 && \
apt-get update && \
apt-get install -q -y apache2
EXPOSE 80
COPY /files/readme.txt /u01/
COPY /web-site/ /var/www/html/