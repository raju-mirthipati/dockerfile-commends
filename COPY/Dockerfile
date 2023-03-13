FROM ubuntu
RUN apt-get update -y
RUN apt-get install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY qw /usr/share/nginx/html/
EXPOSE 80/tcp
CMD ["nginx", "-c", "/etc/nginx/nginx.conf"]
