*** docker-nginx-jenkins ***
overhead task, use this command before it


docker pull jenkins

docker network create --driver bridge private_network

docker volume create --name cache

docker volume create --name=data
