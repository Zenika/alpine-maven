FROM zenika/alpine-maven

ONBUILD COPY pom.xml /usr/src/app/
ONBUILD RUN mvn dependency:get && mvn deploy:deploy-file
ONBUILD COPY . /usr/src/app

CMD [ "mvn", "package" ]