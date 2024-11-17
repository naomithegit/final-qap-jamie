FROM openjdk:17-jdk-slim
COPY golf-tournament-management-0.0.1-SNAPSHOT.jar /app/golf-tournament-management.jar
WORKDIR /app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "golf-tournament-management.jar"]