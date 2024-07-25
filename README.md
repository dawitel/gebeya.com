# Gebeya.com

A distributed microservice backedn for an e-commerce app called gebeya.com. The project is written in Go. This project is only concerned with the backend and infrastructure for the app. 
The services in this project include the following:
- Product Service
- Order Service
- User Service
- Payment Service
- Shipping Service
- Inventory Service
- Search Service
- Recommendation Service
- Notification Service

## The technology being used
- Go
- Kafka
- gRPC
- REST API gateway for clients
- chi router
- Docker

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## MakeFile

run all make commands with clean tests
```bash
make all build
```

build the application
```bash
make build
```

run the application
```bash
make run
```

Create DB container
```bash
make docker-run
```

Shutdown DB container
```bash
make docker-down
```

live reload the application
```bash
make watch
```

run the test suite
```bash
make test
```

clean up binary from the last build
```bash
make clean
```
