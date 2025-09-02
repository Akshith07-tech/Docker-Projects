# Use the official OpenJDK 17 image as the base image
FROM openjdk:17-jdk-alpine AS build

#set working directory
WORKDIR  /app

#copy source file
COPY src/Main.java /app/Main.java

COPY quotes.txt quotes.txt

#complie java code inside container 
RUN javac Main.java 

#Expose port 8000 to HTTP Server
EXPOSE 8000

CMD ["java", "Main"]
