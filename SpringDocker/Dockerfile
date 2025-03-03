FROM eclipse-temurin:17-jdk-focal
LABEL authors="arnav"
ARG JAR_FILE=target/spring-docker-0.0.1.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
