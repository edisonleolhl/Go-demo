# README

## Introduction

go-demo是个人学习Google开源的gRPC与protobuf的Demo，用Go语言编写

## Walk Through

Generate protobuf:

```shell
cd protos
./gen_pb.sh
```

Start server & client:

```shell
cd src
go run server.go
# Another terminal
cd src
go run client.go
```

Then, you will see output in client terminal.

## Reference

<https://www.liwenzhou.com/posts/Go/gRPC/>

<https://lixueduan.com/post/grpc/02-hello-world/>
