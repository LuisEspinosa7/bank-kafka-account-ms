FROM adoptopenjdk/openjdk16
WORKDIR /opt
COPY target/accounts-commands-ms.jar /opt/app.jar
EXPOSE 5000
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar