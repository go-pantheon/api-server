# go-pantheon

**go-pantheon** is a production-ready game server framework designed for building high-performance, highly available game server clusters using microservices architecture.

# api-server

**api-server** defines the API protocol for server clusters using Protocol Buffer IDL, following [Kratos API Definition](https://go-kratos.dev/docs/component/api/) standards.

## Features

- Protocol-first design using Protobuf
- Modular architecture for game services
- High-performance networking layer
- Distributed system ready
- Server compatibility package

## Code Generation

api-server will be introduced as a submodule in projects like janus(gateway) and roma(game server), and the projects will provide tools to generate the corresponding code.

## Contributing

If you have any suggestions or feedback, please feel free to open an issue or submit a `pull request`.

## License

Distributed under the MIT License. See `LICENSE` for more information.
