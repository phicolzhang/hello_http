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
# at terminal
dummyserv 12344
# open browser
localhost:12344
```



