What is Docker?   
Docker is a software platform that simplifies the process of building, 
running, managing and distributing applications.

What is docker compose?  
Compose is a tool for defining multi-container Docker applications. With
Compose, we use a YAML file to configure our application services. Then,
with a single command, we can create and start all the services from our configuration.

Commands.                                                                                                                                         
For making the docker containers up and running we use command `docker-compose up -d`.
Here -d stands for detach mode and containers will keep on running in the background.
For stopping the containers, removing containers, networks, volumes, and images
created by `up` we use command `docker-compose  down`.

--Install Docker before running test cases.                                                                                     
--File `docker_setup` contains methods to run batch file required to start,
stop and remove the containers.

Some Docker Commands:
______________________
docker --version -> Returns the docker version installed on system.
docker pull image_name ( Fetch docker_image from dockerhub. Example - "docker pull ubuntu" )
docker run -it -d image_name ( Run the image to form container. -it refers to Interactive. -d refers to detatch mode. )
docker start container_id ( Start the docker container )
docker stop container_id ( Stop the docker container )
docker restart container_id ( Restart the docker container )
docker ps ( Return list of runnning docker containers )
docker ps -a ( Return list of all docker containers )
docker images / docker image ls ( Return list of all docker images )
docker rm container_id ( Removes the docker container with the containe_id passed )
docker rmi image_id ( Removes the docker image with image_id passed )
docker kill container_id ( Stop the container with the image_id passed )
docker image prune -a ( Remove dangling images )
