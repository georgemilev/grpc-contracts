# grpc-contracts
Shared gRPC contracts

Build status placeholder
![](https://github.com/<username>/<repo>/workflows/<urlencoded workflow name>/badge.svg)


[Google protocol buffers style guide](https://developers.google.com/protocol-buffers/docs/style)

Generate c# contracts 
~~~
protoc --proto_path ./protos/ --csharp_out=./csharp ./protos/*.proto
~~~