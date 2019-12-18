FROM openjdk:8-jdk-alpine

WORKDIR /serv

COPY ./airports-assembly-1.0.3.jar /serv/airports-assembly-1.0.3.jar

EXPOSE 8082

CMD ["java", "-Dhttp.port=8082", "-jar", "/serv/airports-assembly-1.0.3.jar"]