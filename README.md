# Spring Boot WebFlux Example

A simple application written using [Spring Boot WebFlux](https://spring.io/guides/gs/reactive-rest-service/)

## Build

```
$ mvn clean package
```

## Run

```
$ java -jar target/target/greeting-1.0-SNAPSHOT.jar
```

It will listen at `http://127.0.0.1:8080`

## Some calls

```
$ curl http://127.0.0.1:8080/greet
```

## TODO

- Test the application
- Add a downstream service called from the controller