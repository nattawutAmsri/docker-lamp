# Simple LAMP docker

Run your LAMP with docker-compose
* Just docker-compose up -d (Run background)

Docker basic command
* docker-compose up -> to run your docker container from docker-compose.yml
* docker-compose down -> to stop  your container 
* docker-compose build -> to build you docker-compose.yml
* docker ps -> to view your all container is running
* docker images -> to view your all image is available
* docker inspect [container ID] -> to check your container information

Directory guid
* bin -> store you webserver and mysql install command using Dockerfile
* confif -> store you php and host config
* data -> store your db data
* logs -> allow your server with logs and easy to get log from you host
* www -> store your php application
 
