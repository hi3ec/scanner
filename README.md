# scanner
scanner with django and mangodb

### Run Mongo Docker
```
docker run --rm -it --name mongo -p 27017:27017 -v ~/w/docker-db/mongo:/etc/mongo  -e MONGO_INITDB_ROOT_USERNAME=mongoadmin -e MONGO_INITDB_ROOT_PASSWORD=secret -d mongo
```
https://hub.docker.com/_/mongo

#### connect VS to monogdb
```
mongodb://mongosecret:secret@127.0.0.1:27017
```
