FROM       openjdk:8-jre-alpine
COPY       app/target/app.jar /app/app.jar
COPY       app/samples /samples
CMD        ["java", "-jar", "/app/app.jar"]

