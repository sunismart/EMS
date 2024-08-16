# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/AdminModule-EKA-0.0.1-SNAPSHOT.jar /app/AdminModule-EKA-0.0.1-SNAPSHOT.jar

# Expose port 2022
EXPOSE 2022

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/AdminModule-EKA-0.0.1-SNAPSHOT.jar"]

