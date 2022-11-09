FROM openjdk:17
LABEL maintainer="Manish Bohra"
ADD target/springboot-docker-0.0.1-SNAPSHOT.jar springboot-docker.jar
ENTRYPOINT [ "java", "-jar", "springboot-docker.jar"]

#command below
#docker build -t springboot-docker:latest .    //build docker file
#docker run -dp 9090:8080 springboot-docker