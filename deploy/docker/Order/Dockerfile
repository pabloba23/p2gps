FROM openjdk:8-jre

RUN mkdir -p /usr/local/app

COPY drop/* /usr/local/app/

COPY drop/run.sh usr/local/app/run.sh

COPY drop/application.properties application.properties

EXPOSE 8080

ENTRYPOINT usr/local/app/run.sh
