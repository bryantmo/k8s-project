FROM openjdk:11
ADD app1-1.0-SNAPSHOT.jar /
ENTRYPOINT ["java", "-jar","/app1-1.0-SNAPSHOT.jar","--server.port=8089","--spring.profiles.active=dev"]
RUN echo 'app1 image build finish..'