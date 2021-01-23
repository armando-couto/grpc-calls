# Simple G-RPC

Este repositório demonstra o funcionamento de 4 tipos diferentes de APIs, ou seja, API unária, streaming do lado do servidor, streaming do lado do cliente e streaming bidirecional usando HTTP2, buffers de protocolo (proto3) na estrutura gRPC em Golang.

## Install in MAC
```brew install protobuf```

## Run

Remova o comentário / comente as chamadas no arquivo client.go de acordo com a chamada que você deseja fazer.  

```go run greet_server/server.go```  
```go run greet_client/client.go```