# docker-tutorial
This is to try to set up docker

## Steps to set up a Docker Container

1. Install Docker on your Desktop/Mac
2. Open command prompt and just type ```docker -v``` you will know that its properly installed
3. Now clone/copy the files in this repository to your local computer
4. Now using command prompt go to the folder where these files are copied and type ```docker image build -t [name-your-project] .``` .This will create a docker image on your computer.
5. Now use this image to create a container in your local system using command, ```docker container run -d -p 8084:80 [name-your-project]``` . This will create a container on your local machine
6. Now push this container to your Docker repository using, ```docker push [name-your-project]```
