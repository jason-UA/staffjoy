FROM openjdk:12-jdk-oracle

COPY ./target/mail-svc-1.0.0.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch mail-svc-1.0.0.jar'

ENTRYPOINT ["java", "-jar", "mail-svc-1.0.0.jar"]