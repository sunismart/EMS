# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/Attendance_01-0.0.1-SNAPSHOT.jar /app/Attendance_01-0.0.1-SNAPSHOT.jar

# Expose port 1998
EXPOSE 1998

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/Attendance_01-0.0.1-SNAPSHOT.jar"]

