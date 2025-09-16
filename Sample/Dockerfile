# Use an OpenJDK base image
FROM openjdk:17-jdk-slim

# Set working directory inside container
WORKDIR /app

# Copy jar or project files
COPY target/sample1.jar ./sample1.jar

# Command to run the jar
CMD ["java", "-jar", "sample1.jar"]
