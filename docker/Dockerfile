FROM tomcat:9-jre11-openjdk

RUN rm -Rf /usr/local/tomcat/webapps/ROOT
COPY webapp.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
