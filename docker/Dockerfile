FROM adoptopenjdk:11.0.5_10-jre-hotspot-bionic

### Add entrypoint as executable file
COPY entrypoint.sh /
RUN chmod +x /entrypoint.sh

### Set entrypoint to script running Java application
ENTRYPOINT ["/entrypoint.sh"]

### Add Java application artifact
COPY *.jar /application/application.jar