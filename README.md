# rpcx-example

```txt
server.go 服务端(Go)
client.go 客户端(Go)

gateway.go API网关层(Go)
client.php 通过API网关层访问服务端的客户端(php)

client.go ---> server.go(localhost:8972)
client.php ---> gateway.go(localhost:9981) ---> server.go(localhost:8972)
```
