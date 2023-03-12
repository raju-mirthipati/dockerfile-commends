FROM ubuntu:latest
RUN apt-get update -y
RUN apt-get install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon 0ff;"]
LABEL AUTHOUR="raju"
EXPOSE 8080/tcp
ENV NAME=nginx
COPY qw /usr/share/nginx/html