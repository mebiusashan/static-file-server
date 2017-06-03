# Static File Server

A simple static file server.


## Build

`go build fs.go`

## How to use

```
//start server
fs
fs -d
fs -p :9090
fs -d -p -9090


//close server, '-i' is your server pid
fs -c -i 12345
```