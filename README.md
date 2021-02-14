# gRPC-go

## Prerequisites

``` BASH
export GO111MODULE=on
go get google.golang.org/protobuf/cmd/protoc-gen-go \
         google.golang.org/grpc/cmd/protoc-gen-go-grpc
```

## Greet ProtoBuffer API

- Greeting Message
  - first_name
  - last_name

- GreetRequest
  - Greeting

- GreetResponse
  - result
