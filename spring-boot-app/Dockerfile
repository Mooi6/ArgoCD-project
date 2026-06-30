FROM eclipse-temurin:17-jre-alpine

WORKDIR /opt/app

# تحديد مكان الـ JAR اللي طالع من الـ Maven build
COPY target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
