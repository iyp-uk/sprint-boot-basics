# Spring boot demo

> Inspired by [official spring boot documentation](https://docs.spring.io/spring-boot/docs/current-SNAPSHOT/reference/htmlsingle/)

## Prerequisites

Ensure you have Java and Maven:

```console
$ java -version
java version "1.8.0_151"
Java(TM) SE Runtime Environment (build 1.8.0_151-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.151-b12, mixed mode)
```
```console
$ mvn -v
pache Maven 3.5.2 (138edd61fd100ec658bfa2d307c43b76940a5d7d; 2017-10-18T08:58:13+01:00)
Maven home: /usr/local/Cellar/maven/3.5.2/libexec
Java version: 1.8.0_151, vendor: Oracle Corporation
...
```

## Useful commands

### Check dependencies

```console
$ mvn dependency:tree
```

### Run the app

```console
$ mvn spring-boot:run
```

* Visit http://localhost:8080 to browse it
* Stop it with `CTRL+C`

### Creating an executable JAR

```console
$ mvn package
```

#### Inspect your JAR package

```console
$ jar tvf target/demo-0.0.1-SNAPSHOT.jar 
```

#### The the app from the JAR

```console
$ java -jar target/demo-0.0.1-SNAPSHOT.jar
```
