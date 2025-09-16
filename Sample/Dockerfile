# Use an OpenJDK base image
FROM openjdk:17-jdk-slim

# Set working directory inside container
WORKDIR /app

# Copy jar (any version) into container and rename to sample1.jar
COPY target/*.jar ./sample1.jar

# Command to run the jar
CMD ["java", "-jar", "sample1.jar"]
