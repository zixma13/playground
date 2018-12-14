FROM maven:alpine

WORKDIR /opt/code
COPY ./code .
RUN ["mvn","package"]

EXPOSE 8080
CMD ["java", "-jar", "target/gs-spring-boot-0.1.0.jar"]

