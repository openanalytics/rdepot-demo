FROM openjdk:jre-alpine

LABEL maintainer="jonas.vanmalder@openanalytics.eu"

ARG VERSION
LABEL version=$VERSION

RUN mkdir -p /opt/repo/
COPY oa-rdepot-repo-$VERSION.jar /opt/repo/oa-rdepot-repo.jar

CMD ["java", "-jar", "/opt/repo/oa-rdepot-repo.jar"]
