FROM openjdk:17-alpine
LABEL authors="Bonevy BEBY"
VOLUME /tmp
ADD target/dockerfile-demo-springboot*.jar /app.jar
CMD ["java","-jar","/app.jar","--spring.profiles.active=prod"]
EXPOSE 8095