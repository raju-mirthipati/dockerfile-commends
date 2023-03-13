FROM ubuntu
RUN apt-get update -y && apt-get install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY new /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80/tcp
