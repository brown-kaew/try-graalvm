# try-graalvm

## Install GraalVM

```bash
sdk install java 21.0.7-graal 
sdk use java 21.0.7-graal
```

## Build native image

```bash
mvn native:compile -Pnative
```

## Run native image

```bash
./target/demo
```