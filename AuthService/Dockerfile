# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/AuthService-0.0.1-SNAPSHOT.jar /app/AuthService-0.0.1-SNAPSHOT.jar

# Expose port 2055
EXPOSE 2055

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/AuthService-0.0.1-SNAPSHOT.jar"]

