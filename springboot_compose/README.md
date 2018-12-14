# something

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
