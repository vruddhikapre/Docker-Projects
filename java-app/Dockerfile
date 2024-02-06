# Use an official Java runtime as the base image
FROM openjdk:11

# Set the working directory inside the container
WORKDIR /app

# Copy the application file into the container
COPY Hello.java .

# Compile the Java code
RUN javac Hello.java

# Run the Java application when the container starts
CMD ["java", "Hello"]

