FROM openjdk:11-jre
ENV MYAPP_HOME /opt/myapp
WORKDIR $MYAPP_HOME
COPY ./target/*-exec.jar ./myapp.jar

ENTRYPOINT java -jar myapp.jar
