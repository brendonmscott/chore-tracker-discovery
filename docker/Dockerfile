# Start with a base image containing Java runtime
FROM openjdk:8-jdk-alpine

MAINTAINER brendonmscott@gmail.com

ADD target/chore-tracker-discovery-application-1.0.0-SNAPSHOT.jar /opt/spring-cloud/lib/chore-tracker-discovery-application.jar

ENTRYPOINT ["/usr/bin/java"]

CMD ["-jar", "/opt/spring-cloud/lib/chore-tracker-discovery-application.jar"]