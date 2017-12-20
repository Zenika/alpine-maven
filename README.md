# alpine-maven
Minimal Java/Maven Docker Images built on Alpine Linux

# Alpine version

```
docker run --rm zenika/maven cat /etc/alpine-release
3.4.6
```

# Java version

```
docker run --rm zenika/alpine-maven java -version
openjdk version "1.8.0_111-internal"
OpenJDK Runtime Environment (build 1.8.0_111-internal-alpine-r0-b14)
OpenJDK 64-Bit Server VM (build 25.111-b14, mixed mode)
```

# Maven version

```
docker run --rm zenika/alpine-node mvn -v
Apache Maven 3.5.2 (138edd61fd100ec658bfa2d307c43b76940a5d7d; 2017-10-18T07:58:13Z)
Maven home: /usr/lib/mvn
Java version: 1.8.0_111-internal, vendor: Oracle Corporation
Java home: /usr/lib/jvm/java-1.8-openjdk/jre
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "4.9.49-moby", arch: "amd64", family: "unix"
```
