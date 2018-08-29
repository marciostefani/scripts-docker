FROM ubuntu
RUN  apt-get update
RUN  apt-get install wget git figlet apache2 -y
COPY hosts /etc/
COPY index.html /var/www/html/
#CMD  service apache2 restart 



