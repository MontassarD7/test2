# Use an existing OpenJDK 17 slim image
FROM openjdk:17.0.9-jdk-slim

WORKDIR /app
COPY target/my-app-1.0-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
