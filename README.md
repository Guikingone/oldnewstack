Hi there !

This is my first stack using the vibrant Dockerization technology.

I will :

- Use only official images
- Select alpine when available
- Deliver a PHP/Symfony ready stack for dev


I'll try :

* Busybox
* Nginx
* Php-fpm
* PostgresSql (maybe Sqlite)


Main parameters will be specified in Environment variables in .env file (supported by docker-compose)


_________________________________________________________________________________________________________

1. First try to get nginx from a debian.
2. Pulled nginx official from alpine. Github gives Dockerfile that allows more customization
3. To mount volumes, you have to mount at launch via CLI or docker-compose
