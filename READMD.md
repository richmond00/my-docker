### my-docker

# container

docker container ls
docker container ps
docker container stop ${containerid}
docker container stop $(docker container ls -aq)
docker container prune

# image

docker image ls
docker image rm ${iamgeid}
docker image rm ${image name}
docker image rm $(docker image ls -aq)
