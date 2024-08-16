# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/Eureka_EKA-0.0.1-SNAPSHOT.jar /app/Eureka_EKA-0.0.1-SNAPSHOT.jar

# Expose port 8761
EXPOSE 8761

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/Eureka_EKA-0.0.1-SNAPSHOT.jar"]

