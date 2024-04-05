para crear un contenedor de mongo db:

docker pull mongo:latest

docker run -d --name mongo1 -p 27017:27017 mongo

docker exec -it mongo1 mongo

* [ ]
