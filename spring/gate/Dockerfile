FROM openjdk:11-jdk
ARG JAR_FILE=spring-jpa-1.0.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]