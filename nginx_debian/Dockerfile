FROM debian
MAINTAINER gompali me ygranger@yg-project.fr

RUN apt-get update && apt-get dist-upgrade
RUN apt-get install -y wget gnupg*

RUN echo "deb http://nginx.org/packages/debian/ stretch nginx"> /etc/apt/sources.list.d/nginx.list
RUN echo "deb-src http://nginx.org/packages/debian/ stretch nginx"> /etc/apt/sources.list.d/nginx.list

RUN wget -nc https://nginx.org/keys/nginx_signing.key
RUN apt-key add nginx_signing.key

RUN apt-get update
RUN apt install -y nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
