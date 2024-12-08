# Emercast Api Specification

This repository contains the API specification for both the REST interface of the backend, as well as the Protobuf definitions that are used to serialize data that is transmitted via BLE.
The OpenAPI specification of this repository is used with the [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) to generate server stubs for the backend and api connectors for the frontend and Android application.
The Protobuf definitions are used by the [Protobuf compiler](https://grpc.io/docs/protoc-installation/) to generate serialization and deserialization code for the backend and the Android application.
