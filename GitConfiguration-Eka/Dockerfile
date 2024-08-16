# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/GitConfiguration-Eka-0.0.1-SNAPSHOT.jar /app/GitConfiguration-Eka-0.0.1-SNAPSHOT.jar

# Expose port 2029
EXPOSE 2029

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/GitConfiguration-Eka-0.0.1-SNAPSHOT.jar"]

