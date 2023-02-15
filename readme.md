How to build the image:
-- need to be in the directory with the Dockerfile.
docker build . -t joke_nginx (or whatever name you are using)

How to run the image:
docker run -it --rm -p 8080:80 joke_nginx (or whatever name you are using)

How to stop container:

How to remover container:

How to stop/remove the container in one step: 
    docker ps (to get the container id)
    docker -rm -f (container id)