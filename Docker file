# Use an official OpenJDK runtime as a parent image
FROM openjdk:8

# Expose port 8080 for the application
EXPOSE 8080

# Add the JAR file to the container
ADD target/docker-jenkins-integration-sample.jar /docker-jenkins-integration-sample.jar

# Set the entry point to run the JAR file
ENTRYPOINT ["java", "-jar", "/docker-jenkins-integration-sample.jar"]
