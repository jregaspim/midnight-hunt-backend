FROM openjdk:17-jdk
EXPOSE 8080
ADD target/jobpost-service-0.0.1-SNAPSHOT.jar jobpost-service.jar
ENTRYPOINT ["java","-jar","/jobpost-service.jar"]