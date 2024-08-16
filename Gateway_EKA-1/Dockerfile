# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/Gateway_EKA-1-0.0.1-SNAPSHOT.jar /app/Gateway_EKA-1-0.0.1-SNAPSHOT.jar

# Expose port 2030
EXPOSE 2030

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/Gateway_EKA-1-0.0.1-SNAPSHOT.jar"]

