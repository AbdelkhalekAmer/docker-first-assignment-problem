# docker-first-assignment-problem

Learn how to write docker file, create images and deploy containers.

node-app

build image: docker build -t nodeapp:latest .

run container: docker run -p 3000:3000 -d --name nodeapp_latest nodeapp:latest

python-app

build image: docker build -t pythonapp:latest .

run container: docker run -it --name pythonapp_latest pythonapp:latest

List all images in your machine
docker image ls

List all containers in your machine
docker ps -a
