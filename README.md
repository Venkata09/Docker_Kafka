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


    kill all running containers with docker kill $(docker ps -q)
      delete all stopped containers with docker rm $(docker ps -a -q)
    delete all images with docker rmi $(docker images -q)
    
    

```



