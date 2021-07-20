FROM adoptopenjdk/openjdk11:alpine-jre	

ARG JAR_FILE=java-webserver.jar

COPY ${JAR_FILE} java-webserver.jar

EXPOSE 8080

CMD ["java","-jar","java-webserver.jar"]
