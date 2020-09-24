FROM openjdk:8-jdk

MAINTAINER archana.jeena@morningstar.com

EXPOSE  8080
WORKDIR "/usr/local/tomcat/"

#RUN ["rm","-R","webapps/ROOT"]

ADD *.jar /usr/local/tomcat/webapps/ROOT.jar

CMD ["catalina.sh","run"]