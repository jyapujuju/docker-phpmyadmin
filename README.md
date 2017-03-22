# what is it ?
this is an docker-compose file for start the lamp stack with phpadmin with docker. just add the php files in www folder.

# prerequisite

- [x] docker
- [x] docker-compose
- [ ] git

# How to use ?
- ```git clone git@github.com:jyapujuju/docker-phpmyadmin.git```
- ```cd docker-phpmyadmin```
- ```docker-compose up -d```
- ```docker-compose up```
- ```sudo chmod -R 777 www```
-  - for linux user only
- create folder inside the www folder :)
- phpmyadmin may take some moment start up in initial phase for sake of necessary file generation
- username is ``root``
- password is ``password``
- add ```ruby ini_set('display_errors',"1");  ``` in your php file to get error info
