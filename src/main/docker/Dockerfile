FROM java:8

MAINTAINER Bill Corrie, hinterwelt.com
 
ADD discovery.jar /app.jar
 
EXPOSE 8761
 
CMD java -Djava.security.egd=file:/dev/./urandom -jar /app.jar