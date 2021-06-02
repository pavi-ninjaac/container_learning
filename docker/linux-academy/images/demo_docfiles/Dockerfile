FROM ubuntu:bionic

ENV NGINX_VER 1.14.0-0ubuntu1.7
RUN apt-get update && apt-get install -y curl
RUN apt-get update && apt-get install -y nginx

WORKDIR /var/www/html
ADD index.html ./

EXPOSE 80

CMD ["nginx" , "-g" , "daemon off;"]



