# what is it ?
this is an docker-compose file for start the lamp stack with phpadmin with docker.

# prerequisite

- [x] docker
- [x] docker-compose
- [ ] git

# How to use ?
- git clone git@github.com:jyapujuju/lamp-mysql-phpmyadmin-docker.git
- cd lamp-mysql-phpmyadmin-docker
- docker-compose build
- docker-compose up
- chown -R $USER:$GROUPS .
-  - chown step is necessary for linux user only $USER is username and $GROUPS is corresponding groupname you can find this using $> ls -l
- create folder inside the www folder :)
