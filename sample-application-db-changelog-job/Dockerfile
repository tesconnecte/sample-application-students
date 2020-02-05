FROM  openjdk:11-jre
ENV  MY_APP_HOME /opt/myapp
WORKDIR $MY_APP_HOME
COPY ./target/*-exec.jar $MY_APP_HOME/myapp.jar
ENTRYPOINT java -jar myapp.jar
