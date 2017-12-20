# Supported tags and respective `Dockerfile` links

 * `3-jdk8`, `3`, `latest` [(jdk8/Dockerfile)](https://github.com/Zenika/alpine-maven/blob/master/jdk8/Dockerfile)

 * `3-jdk7` [(jdk7/Dockerfile)](https://github.com/Zenika/alpine-maven/blob/master/jdk7/Dockerfile)

 * `3-jdk-8-onbuild`, `3-onbuild`, `onbuild` [(jdk8/onbuild/Dockerfile)](https://github.com/Zenika/alpine-maven/blob/master/jdk8/onbuild/Dockerfile)

 * `3-jdk-7-onbuild` [(jdk7/onbuild/Dockerfile)](https://github.com/Zenika/alpine-maven/blob/master/jdk7/onbuild/Dockerfile)

# alpine-maven
Minimal Java/Maven Docker Images built on Alpine Linux
Based on `java:8-alpine`

# What is Maven

Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

See https://en.wikipedia.org/wiki/Apache_Maven for more information.

![Maven Logo](https://maven.apache.org/images/maven-logo-black-on-white.png)

# How to use this image

Start using the Maven : `docker container run --rm zenika/alpine-maven mvn [options] [<goal(s)>] [<phase(s)>]`

# Reference

 * Maven website : https://maven.apache.org

 * Where to file issues : https://github.com/Zenika/alpine-maven/issues

 * Maintained by : https://www.zenika.com

# Versions (in latest)

## Alpine version

```
docker container run --rm zenika/alpine-maven cat /etc/alpine-release
3.4.6
```

## Java version

```
docker container run --rm zenika/alpine-maven java -version
openjdk version "1.8.0_111-internal"
OpenJDK Runtime Environment (build 1.8.0_111-internal-alpine-r0-b14)
OpenJDK 64-Bit Server VM (build 25.111-b14, mixed mode)
```

## Maven version

```
docker container run --rm zenika/alpine-node mvn -v
Apache Maven 3.5.2 (138edd61fd100ec658bfa2d307c43b76940a5d7d; 2017-10-18T07:58:13Z)
Maven home: /usr/lib/mvn
Java version: 1.8.0_111-internal, vendor: Oracle Corporation
Java home: /usr/lib/jvm/java-1.8-openjdk/jre
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "4.9.49-moby", arch: "amd64", family: "unix"
```
