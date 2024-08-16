# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/PaymentModule-0.0.1-SNAPSHOT.jar /app/PaymentModule-0.0.1-SNAPSHOT.jar

# Expose port 2025
EXPOSE 2025

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/PaymentModule-0.0.1-SNAPSHOT.jar"]

