1-Create CatalogAPI
2-docker pull mongodb to store catalog with username as si.lam@serverlessdeveloper.com

docker pull mongo

$ docker run --name catalogdb -d mongo:tag -p 27017:27017

docker logs -f catalogdb

>docker exec -it catalogdb /bin/bash


Install MongoDB Compass client for Windows

