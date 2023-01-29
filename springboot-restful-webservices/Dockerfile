FROM eclipse-temurin:17

LABEL mentainer="ninoos@gmail.com"

WORKDIR /app

COPY target/springboot-restful-webservices-0.0.1-SNAPSHOT.jar /app/web.jar

ENTRYPOINT ["java","-jar","web.jar"]