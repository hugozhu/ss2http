# INSTALL

```
export GOPATH=`pwd`
go get github.com/shadowsocks/shadowsocks-go/shadowsocks
go get github.com/elazarl/goproxy
```

# config.json

···
{
    "server":"_your_server_ip",
    "server_port":8888,
    "local_port":1080,
    "password":"oneworld",
    "method":"bf-cbf",
    "timeout":600,
}
···


# RUN

```
go run ss2http.go --proxy_type http
2015/08/23 20:50:23 available remote server ******:8888
2015/08/23 20:50:23 starting local http proxy server at :1080 ...
```