# Dockerfile Updated
FROM openjdk:8-jre-alpine


# Set the working directory
WORKDIR /usr/app


# Copy the JAR file to the container
COPY ./target/java-maven-app-1.0-SNAPSHOT.jar /usr/app/

EXPOSE 8080

# Command to run the JAR file
CMD ["java", "-jar", "java-maven-app-1.0-SNAPSHOT.jar"]
