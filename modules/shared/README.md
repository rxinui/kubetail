# Kubetail Shared Go Libraries

Go module containing shared go libraries

## Dependencies

```console
brew install protobuf protoc-gen-go protoc-gen-go-grpc
```

## gRPC

To run the gRPC code generator use the `go generate` command:

```console
go generate ./...
```

## Test

To run the test suite execute this command:

```console
go test ./...
```
