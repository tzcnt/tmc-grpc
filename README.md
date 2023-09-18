## tmc-grpc
This is where the planned [TooManyCooks](https://github.com/tzcnt/TooManyCooks/) - gRPC integration will be. There's nothing here yet...

### TODO
- Provide awaitables for accepting connections, sending and receiving messages.
- Ensure that simultaneous access to gRPC resources (e.g. when multiple coroutines are sending responses over a single gRPC stream) are sufficiently protected.
