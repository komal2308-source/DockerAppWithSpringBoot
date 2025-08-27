# Use a base image with OpenJDK 17
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
EXPOSE 8080

# Copy the application JAR file into the container
# Replace 'your-application.jar' with the actual name of your JAR file
ADD target/dockerApp.jar dockerApp.jar

# Define the command to run when the container starts
ENTRYPOINT ["java", "-jar", "dockerApp.jar"]