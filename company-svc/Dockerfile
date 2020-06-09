FROM openjdk:12-jdk-oracle

COPY ./target/company-svc-1.0.0.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch company-svc-1.0.0.jar'

ENTRYPOINT ["java", "-jar", "company-svc-1.0.0.jar"]