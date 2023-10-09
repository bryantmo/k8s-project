FROM openjdk:11
ADD eureka-1.0-SNAPSHOT.jar /
ENTRYPOINT ["java", "-jar","/eureka-1.0-SNAPSHOT.jar","--server.port=8087","--spring.profiles.active=dev"]
RUN echo 'eureka image build finish..'