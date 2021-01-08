# Hands-On RESTful Go

Projects from [A Hands-On RESTful Web Services with Go](https://www.packtpub.com/product/hands-on-restful-web-services-with-go-second-edition/9781838643577) book by Naren Yellavula.

## Install

Before installing please check that `go env GOPATH` and `$GOPATH` are not empty and are set correctly.

```bash
git clone https://github.com/dbystruev/handsOnRestfulGo.git $(go env GOPATH)/src/github.com/dbystruev/handsOnRestfulGo
```

## Stopping

If running a project in background (with `&`), use ``kill `lsof -t -i:8000` `` or ``sudo kill `sudo lsof -t -i:8000` `` to kill it.

## Projects

### Chapter 1: Hello
```bash
go run $GOPATH/src/github.com/dbystruev/handsOnRestfulGo/chapter01/hello/hello.go
```

### Chapter 1: Fastest Mirror
```bash
go run $GOPATH/src/github.com/dbystruev/handsOnRestfulGo/chapter01/mirrorFinder/mirrorFinder/main.go
```
[localhost:8000/fastest-mirror](http://localhost:8000/fastest-mirror)

### Chapter 2: Health Check
```bash
go run $GOPATH/src/github.com/dbystruev/handsOnRestfulGo/chapter02/healthCheck/main.go
```
[localhost:8000/health](http://localhost:8000/health)

### Chapter 2: UUID Generator
```bash
go run $GOPATH/src/github.com/dbystruev/handsOnRestfulGo/chapter02/uuidGenerator/main.go
```
[localhost:8000](http://localhost:8000)

### Chapter 2: Random Number Generators
```bash
go run $GOPATH/src/github.com/dbystruev/handsOnRestfulGo/chapter02/multipleHandlers/main.go
```
[localhost:8000/randomFloat](http://localhost:8000/randomFloat)  
[localhost:8000/randomInt](http://localhost:8000/randomInt)

### Chapter 2: HTTP Router Example
```bash
cd $GOPATH/src/github.com/dbystruev/handsOnRestfulGo
go run $GOPATH/src/github.com/dbystruev/handsOnRestfulGo/chapter02/httprouterExample/main.go
```
[localhost:8000/api/v1/go-version](http://localhost:8000/api/v1/go-version)  
[localhost:8000/api/v1/show-file/greek.txt](http://localhost:8000/api/v1/show-file/greek.txt)  
[localhost:8000/api/v1/show-file/latin.txt](http://localhost:8000/api/v1/show-file/latin.txt)

### Chapter 2: Static File Server
```bash
cd $GOPATH/src/github.com/dbystruev/handsOnRestfulGo
go run $GOPATH/src/github.com/dbystruev/handsOnRestfulGo/chapter02/fileServer/main.go
```
[localhost:8000/static](localhost:8000/static)
[localhost:8000/static/greek.txt](http://localhost:8000/static/greek.txt)
[localhost:8000/static/latin.txt](http://localhost:8000/static/latin.txt)