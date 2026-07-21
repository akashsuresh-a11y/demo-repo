FROM eclipse-temurin:21-jre

WORKDIR /app

COPY springboot/ms-demo-service/build/libs/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]