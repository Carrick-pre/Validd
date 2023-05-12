FROM openjdk:8-jdk-alpine
LABEL authors="false"
COPY target/producer-0.0.1-SNAPSHOT.jar producer.jar
ENTRYPOINT ["java","-jar","/producer.jar"]