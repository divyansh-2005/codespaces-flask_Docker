free -h
lscpu

<!-- docker cmds -->

docker version  # show docker version
docker pull

https://hub.docker.com/_/nginx # nginx is a web server
docker pull nginx

docker image ls

docker run --name nginx -p 80:80 nginx

docker ps -a #shows number of running processes 

docker stop nginx
docker rm nginx # removes container

docker run --name nginx -p 8000:80 nginx