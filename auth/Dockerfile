FROM openjdk:17-slim-bullseye

LABEL authors="Stainley Lebron"

WORKDIR /app
COPY target/auth-*.jar app.jar
EXPOSE 8081
CMD ["java", "-jar", "app.jar"]