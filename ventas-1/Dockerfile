FROM openjdk:19-jdk-alpine
ARG JAR_FILE=target/ventas-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} ventas.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/ventas.jar"]