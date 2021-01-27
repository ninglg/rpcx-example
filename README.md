# rpcx-example

```txt
server.go 服务端
client.go 客户端
gateway.go 中间层
client.php 通过中间层访问服务端的客户端

client.go ---> server.go(localhost:8972)
client.php ---> gateway.go(localhost:9981) ---> server.go(localhost:8972)
```
