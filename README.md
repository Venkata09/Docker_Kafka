# Docker_Kafka

Since I am practicing the Kafka and Docker. I imported a lot of Confluent Docker Images which my machine is overflooded with. I want to clean them.


```text

# For Listing all the images

docker ps -a

# For removing all the container or the images. 

docker rm $(docker ps -aq)

# For Stopping all the running docker CONTAINERS. 

docker stop $(docker ps -a -q)

# For stopping a container

docker stop my_container



Put your ID and start the DOCKER Image. 

$ MY_IP=*********** docker-compose -f docker-compose.yml up

    kill all running containers with docker kill $(docker ps -q)
      delete all stopped containers with docker rm $(docker ps -a -q)
    delete all images with docker rmi $(docker images -q)
    
    

```

# Kafka Docker image with multi broker.


1. **Container port** is a port exposed by the container and accessible from the Docker Machine.
1. **Machine port** is a port exposed by the Docker Machine and accessible from the host.
1. **Port mapping** is essentially forwarding a machine port to a container port.







