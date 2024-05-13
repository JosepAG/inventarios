FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/inventarios-0.0.1.jar
COPY ${JAR_FILE} app_inventarios.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_inventarios.jar"]