FROM adoptopenjdk/openjdk11

COPY /service-discovery/target/service-discovery-0.0.1-SNAPSHOT.jar /app.jar

ENTRYPOINT ["java", "-jar", "/app.jar"]