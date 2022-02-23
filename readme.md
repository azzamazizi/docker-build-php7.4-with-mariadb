--------------------- Requirement ---------------------
- make sure docker and docker-compose has been installed.
- using php:7.4-fpm-alpine
- using mariadb:latest for database
- nginx for proxy



--------------------- START ---------------------
step 1
- configure your setting in docker-compose.yml

step 2
- put your code in directory /app 

step 3, build your own docker images using command :
- docker-compose build

step 4, run your images using command :
- docker-compose up -d
to stop docker-compose :
- docker-compose down



i'm using nginx for redirect url. configure your url in directory /nginx/nginx.conf
replace server_name 127.0.0.1 into your url example : azzamdev.site

--------------------- END ---------------------


contact me for more information
whatsapp : +62 85655909004
email : azzamazizi09@gmail.com