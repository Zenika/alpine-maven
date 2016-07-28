# alpine-maven
Minimal Java/Maven Docker Images built on Alpine Linux
Size: XX MB (All Layers: 152 MB)

Layers:
- alpine:3.4 5 MB
- java7 138 MB
- maven3 10 MB

# Java version

```
docker run --rm zenika/alpine-maven java -version
java version "1.7.0_91"
OpenJDK Runtime Environment (IcedTea 2.6.3) (Alpine 7.91.2.6.3-r2)
OpenJDK 64-Bit Server VM (build 24.91-b01, mixed mode)
```

# Maven version

```
docker run --rm zenika/alpine-node mvn -v
Apache Maven 3.3.9 (bb52d8502b132ec0a5a3f4c09453c07478323dc5; 2015-11-10T16:41:47+00:00)
Maven home: /usr/lib/mvn
Java version: 1.7.0_91, vendor: Oracle Corporation
Java home: /usr/lib/jvm/java-1.7-openjdk/jre
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "4.4.12-boot2docker", arch: "amd64", family: "unix"
```
