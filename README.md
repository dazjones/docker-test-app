# Docker Test App 

A simple Hello World application, with a docker container for testing.

## Build
```
docker build -t test-app .
```

## Run
```
docker run --rm -it -p 8080:8080 test-app
```

## Verify
```
curl http://localhost:8080
Hello World%
```