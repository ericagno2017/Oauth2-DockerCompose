FROM openjdk:8

COPY ./OauthResourseServer/resource-server.jar /usr/app/resource-server.jar
WORKDIR /usr/app

ENTRYPOINT ["java", "-jar", "resource-server.jar"]