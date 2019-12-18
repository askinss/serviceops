FROM openjdk:8-jdk-alpine

WORKDIR /serv

COPY ./airports-assembly-1.1.2.jar /serv/airports-assembly-1.1.2.jar

EXPOSE 8083

CMD ["java", "-Dhttp.port=8083", "-jar", "/serv/airports-assembly-1.1.2.jar"]