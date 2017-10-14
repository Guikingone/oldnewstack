Hi there !

This is my first stack using the vibrant Dockerization technology.

I will :

- Use only official images

- Focus on lightweight (ie if alpine is available, default choice)

- Deliver an effective PHP / Symfony ready to use developpement stack


From those hypothesis good candidates are :

* Nginx
* Php-fpm
* PostgresSql


To keep aligned with docker's philosophy, the source code (app) will be contained in a busybox
Database will of course be persistent
Our dev website will be mounted from an existing local path

Main parameters will be specified in Environment variables
