FROM openjdk:17-jdk-alpine

EXPOSE 8080

WORKDIR /usr/src

COPY spring-example-project/ .

RUN ./mvnw package

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]