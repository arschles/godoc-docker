# godoc-docker
[godoc](http://godoc.org/golang.org/x/tools/cmd/godoc) running in Docker.

This container defaults to running `godoc -http=:6060`.

Run it with this command:

`docker run -v $GOPATH:/gopath --net=host -d --name=godoc -p 6060:6060 arschles/docker-godoc`
