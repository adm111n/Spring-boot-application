# Spring-boot-application
1) Build java application `./mvnw package && java -jar target/spring-docker-simple-0.0.1-SNAPSHOT.jar`
2) Build docker image `docker build -t timur322/spring-boot-application:0.1 .`
3) Login to dockerhub `docker login`
4) Push docker image to Dockerhub `docker push timur322/spring-boot-application:0.1`

