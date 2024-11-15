# Docker-hub-pulling-fom-dockerhub
Container validation 

STEP 1

ON TERMINAL NOT SERVER 
docker image ls
docker pull ubuntu:latest
docker image ls
docker run -it --name ebere ubuntu:latest /bin/bash
ls
Touch Toni
ls
Ctrl  then press PQ
docker ps
docker exec -it ebere bash
pwd
ls
Exit ebere
docker ps
docker stop ebere
docker ps
docker start ebere
docker exec -it ebere bash
ls
Exit
docker stop ebere
docker ps -a



STEP 2
docker
sudo snap install docker
sudo chmod 666 /var/run/docker.sock
docker

GO TO MR KEN DOCKERHUB
https://hub.docker.com/r/281188/webserver/tags
docker pull 281188/webserver:kenuapachenginx
docker image ls
docker run -it  --name webserver -p 80:80 -p 81:81 281188/webserver:kenuapachenginx /bin/bash
ls
service apache2 start
service nginx start
service mariadb start
service php8.3-fpm start


VALIDATE THE PORT
http://72.144.23.229/apache_site/


TO EXIT YOU FROM THE CONTAINER 
CTRL HOLD PQ
docker ps
docker stop webserver
docker ps
docker ps -a
