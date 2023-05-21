FROM tomcat
RUN apt update 
RUN rm -rf /usr/local/tomcat/bin/*

COPY target/vprofile-v2.war  /usr/local/tomcat/bin/vprofile-v2.war
CMD ["catalina.sh", "run"]
