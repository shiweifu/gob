# gob
Build go project cross platform.

You must install `gorun` first:

```
go get github.com/erning/gorun
```
https://github.com/erning/gorun



## Build for Windows:

```
gob windows
```

## Build for Linux:

```
gob linux
```

## Build for Darwin:

```
gob darwin
```

-----



This script does two things:

1. Set the environment variables needed to compile to the destination platform
2. Execute `go build` in the run command directory

