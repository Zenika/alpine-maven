FROM zenika/alpine-maven:3-jdk-7

ONBUILD COPY pom.xml /usr/src/app/
ONBUILD RUN mvn dependency:get && mvn deploy:deploy-file
ONBUILD COPY . /usr/src/app

CMD [ "mvn", "package" ]
