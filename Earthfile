VERSION 0.6
FROM maven:3.8
WORKDIR /workspace

build:
    COPY src src
    COPY pom.xml pom.xml
    RUN mvn clean package
    SAVE ARTIFACT target AS LOCAL target
