# rpcx-example

```txt
server.go 服务端
client.go 直接访问的客户端
gateway.go 服务中间层
client.php 通过gateway访问server的php客户端

client.go ---> server.go(localhost:8972)
client.php ---> gateway.go(localhost:9981) ---> server.go(localhost:8972)
```