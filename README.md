# Java Test

A minimal Spring Boot project for testing Buildspace AI's plan generation and repository MCP integration.

## Milestone 1: Project Initialization and REST Endpoint

This project contains one REST controller. Its `GET /hello` endpoint returns the hardcoded text `Hello World`.

## Run locally

Requires Java 17 or newer.

```bash
./mvnw spring-boot:run
```

In another terminal:

```bash
curl http://localhost:8080/hello
```

Expected response:

```text
Hello World
```
