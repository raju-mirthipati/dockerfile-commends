FROM ubuntu
RUN apt-get update -y && apt-get install -y apache2
RUN rm -rf /usr/share/nginx/html/index.html
COPY qw /var/www/html/
CMD [ "/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80/tcp
