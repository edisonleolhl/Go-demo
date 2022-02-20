# README

## Introduction

go-demo is just for learning how to constructing go project, along with grpc and protobuf.

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
