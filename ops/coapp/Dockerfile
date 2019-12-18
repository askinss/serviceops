FROM openjdk:8-jdk-alpine

WORKDIR /serv

COPY ./countries-assembly-1.0.2.jar /serv/countries-assembly-1.0.2.jar

EXPOSE 8081

CMD ["java", "-Dhttp.port=8081", "-jar", "/serv/countries-assembly-1.0.2.jar"]