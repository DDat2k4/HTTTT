FROM eclipse-temurin:21-jre-jammy
WORKDIR /app
COPY cong-nghe-web-dattestbr/src/main/docker/thitn-0.0.1-SNAPSHOT.jar app.jar
COPY cong-nghe-web-dattestbr/src/main/docker/.env /app/.env
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app/app.jar"]
