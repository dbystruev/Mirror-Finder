# Mirror Finder

Debian closest mirror finder project from [A Hands-On RESTful Web Services with Go](https://www.packtpub.com/product/hands-on-restful-web-services-with-go-second-edition/9781838643577) book by Naren Yellavula.

## Install

Before installing plesase check that `go env GOPATH` is not empty and is set correctly.

```bash
git clone https://github.com/dbystruev/Mirror-Finder.git $(go env GOPATH)/src/github.com/dbystruev/mirrorFinder
go install github.com/dbystruev/mirrorFinder/mirrors
$(go env GOPATH)/bin/mirrorFinder
```

## Run
```bash
$(go env GOPATH)/bin/mirrorFinder
```

## Check
[localhost:8000/fastest-mirror](http://localhost:8000/fastest-mirror)
