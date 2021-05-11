# docker-spring-boot

## To build the application using maven use the below command

```sh
./mvnw package && java -jar target/gs-spring-boot-docker-0.1.0.jar
```


## To containerize the maven application use below command

```sh
docker build -t springio/gs-spring-boot-docker .
```
## To run the docker container use the command

```sh
docker run -it -p 8080:8080 springio/gs-spring-boot-docker:latest
```

### Refrence

- [Dockerizing a Spring Boot Application](https://spring.io/guides/gs/spring-boot-docker/)
