FROM mysql:latest

WORKDIR /tmp/app1

ENV MYSQL_USER=catalina
ENV MYSQL_PASSWORD=somepasswd
ENV MYSQL_DATABASE=testdatabase
ENV MYSQL_ROOT_PASSWORD=rootpasswd

COPY test.sql .
