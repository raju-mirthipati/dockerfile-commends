FROM ubuntu
RUN apt-get update -y
RUN apt-get install -y nginx
CMD ["nginx","-g","daemon off;"]
LABEL AUTHOUR="raju"
LABEL application="login"
EXPOSE 8080/tcp
ENV application=login
ENV key=1233222