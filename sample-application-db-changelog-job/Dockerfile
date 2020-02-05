FROM openjdk:11-jre
ENV MYAPP_HOME /opt/db
WORKDIR $MYAPP_HOME
COPY $MYAPP_HOME/target/*-exec.jar $MYAPP_HOME/db.jar

ENTRYPOINT java -jar db.jar
