# Java Docker image
FROM docker202020/java-base:v

MAINTAINER shinto Antony

COPY base.jar /home
RUN chmod 755 /home/base.jar

CMD ["java","-jar","/home/base.jar"]
