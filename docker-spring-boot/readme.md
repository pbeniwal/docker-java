## What is it?
This source code is an Spring Boot web application .
 
Tested with
* Docker 19.03
* Ubuntu 19
* Java 8
* Spring Boot 2.2.4.RELEASE
* Maven

## How to run this?
```bash
$ git clone https://github.com/mkyong/docker-java
$ cd docker-spring-boot
$ mvn clean package
$ java -jar target/spring-boot-web.jar --server.port=8888

  access http://localhost:8888

//dockerize

// create a docker image
$ sudo docker build -t spring-boot:1.0 .
// run it
$ sudo docker run -d -p 8888:8080 -t spring-boot:1.0

  access http://localhost:8888
```
