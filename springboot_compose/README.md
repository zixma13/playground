# something

## Ref:

> https://spring.io/guides/gs/spring-boot/

> https://stackoverflow.com/questions/15940234/how-to-do-a-soap-web-service-call-from-java-class

## run

```
$ docker build --tag myspring .
$ docker run --name spring -d -p 80:8080 myspring
$ curl http://localhost
$ curl http://localhost/tempconvert
$ curl http://localhost/actuator/health
```
## remove

```
$ docker stop spring && docker rm spring && docker rmi myspring
```
