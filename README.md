# hello_http
Hello world with a webserver in C


## Build docker image
```
# under hello_http folder
docker build -t test-image .
```

## Complie C code
```gcc -o dummyserv dummy_serv.c```

## How to run
```
dummyserv 8081
# open the brower
localhost:8081
```



