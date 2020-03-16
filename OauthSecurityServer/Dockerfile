FROM openjdk:8

COPY ./OauthSecurityServer/oauth-authorization-server.jar /usr/app/oauth-authorization-server.jar
WORKDIR /usr/app

ENTRYPOINT ["java", "-jar", "oauth-authorization-server.jar"]