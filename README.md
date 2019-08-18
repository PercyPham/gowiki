# gowiki

## Work with Go installed on current machine

Follow [Getting Started](https://golang.org/doc/install) to install Go

Run:

```
go run src/wiki.go
```

## Work with Docker

### Build Image

```
docker build -t gowiki .
```

### Run gowiki

```
docker run --rm -it -v /$(pwd)/src:/app/src gowiki
```
