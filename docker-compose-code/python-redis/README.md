myweb:

   Docker compose will do the below activities for you using the compose file, we have written.

1. It will first download the base image image
2. It will build u Docker image y reading the Dockerfile 
   which is present in ur current directory
3. Using the image which was built, it will create a container
   and provide the port mapping as 5000:5000 and give a container    name as mywebsite

  docker container run -d -p 5000:5000 --name mywebsite 

redis:

1. First it will download the image from Hub.docker.com              redis:latest
2. Create a container for you, which replicated the below command.
    
   docker container run -d --name myredis redis:latest
