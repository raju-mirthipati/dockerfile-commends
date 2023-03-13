FROM ubuntu
RUN apt-get update -y && apt-get install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
WORKDIR /usr/share/nginx/html/
COPY qw .
EXPOSE 80/tcp
CMD ["nginx", "-g", "daemon off;"]