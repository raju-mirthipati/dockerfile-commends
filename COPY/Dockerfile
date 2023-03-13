FROM ubuntu
RUN apt-get update -y && apt-get install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY qw /usr/share/nginx/html
EXPOSE 80/tcp
