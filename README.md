# protoc-gen-go-gin
根据proto生成gin controller

## 

```bash

go install github.com/hongshengjie/protoc-gen-go-gin@latest

protoc -I. -I/usr/local/include --go-gin_out=. --go_out=. --go-grpc_out=. proto/user.api.proto
```

## TODO

- [ ](参数可校验)
- [ ](自定义http method，GET)
- [ ](除了json 可以支持form等类型的参数)