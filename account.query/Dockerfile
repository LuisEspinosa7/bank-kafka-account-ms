FROM adoptopenjdk/openjdk16
WORKDIR /opt
COPY target/accounts-queries-ms.jar /opt/app.jar
EXPOSE 5001 9092
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar