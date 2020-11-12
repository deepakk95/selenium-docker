What is Docker?    
Docker is a software platform that simplifies the process of building, running, managing and distributing applications.

What is docker compose?   
Compose is a tool for defining multi-container Docker applications. With Compose, we use a YAML file to configure our application services. Then, with a single command, we can create and start all the services from our configuration.

Commands.                                                                                                                                         
For making the docker containers up and running we use command `docker-compose up -d`. Here -d stands for detach mode and containers will keep on running in the background.
For stopping the containers, removing containers, networks, volumes, and images created by `up` we use command `docker-compose  down`.

--Install Docker before running test cases.                                                                                     
--File `docker_setup` contains methods to run batch file required to start, stop and remove the containers.
