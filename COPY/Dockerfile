FROM ubuntu
RUN apt-get update -y && apt-get install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "daemon off;" >>/etc/nginx/nginx.conf
COPY qw /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80/tcp
