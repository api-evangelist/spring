# Spring Framework (spring)

Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, messaging, cloud-native patterns, and AI integrations. Spring Boot enables rapid application development with embedded servers and auto-configuration. Spring is maintained by VMware and hosted under the Spring Projects GitHub organization.

**APIs.json:** [https://spring.io](https://spring.io)

## Tags

- AI
- Cloud Native
- Enterprise
- Framework
- Java
- Microservices
- Open Source
- REST
- Spring Boot

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Spring Boot Actuator API

The Spring Boot Actuator API provides production-ready endpoints for monitoring and managing Spring Boot applications. It exposes health checks, metrics, environment information, thread dumps, HTTP traces, and application info via REST endpoints. The Actuator API is OpenAPI-documented and follows standard HTTP REST conventions.

#### Tags

- Monitoring
- Actuator
- Operations
- Spring Boot

#### Properties

- [Documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)
- [OpenAPI](openapi/spring-boot-actuator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-boot-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Git Hub](https://github.com/spring-projects/spring-boot)
- [Getting Started](https://spring.io/guides/gs/spring-boot/)
- [JSON Schema](json-schema/spring-actuator-health-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/spring-rules.yml)
- [Vocabulary](vocabulary/spring-vocabulary.yml)

### Spring Initializr API

The Spring Initializr REST API enables programmatic generation of Spring Boot project scaffolding. It provides endpoints for listing available dependencies, project types, and boot versions, as well as generating ready-to-use project archives in zip or tar.gz format. Used by IDEs (IntelliJ IDEA, Eclipse STS, VS Code) and CLI tools to bootstrap new Spring projects.

#### Tags

- Bootstrap
- Code Generation
- Developer Tools
- Project Generator

#### Properties

- [Documentation](https://docs.spring.io/initializr/docs/current/reference/html/)
- [OpenAPI](openapi/spring-initializr-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-initializr-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Open A P I Upstream](https://start.spring.io/v3/api-docs)
- [Git Hub](https://github.com/spring-io/initializr)
- [Web Interface](https://start.spring.io)
- [JSON Schema](json-schema/spring-boot-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/spring-boot-application-structure.json)
- [JSON-LD](json-ld/spring-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Spring Data REST API

Spring Data REST automatically exports Spring Data repository interfaces as RESTful hypermedia-driven APIs using HAL (Hypertext Application Language). It enables CRUD operations on domain entities through discoverable REST endpoints without writing controller code. The API supports HATEOAS linking, projections, validation, and event hooks.

#### Tags

- CRUD
- Data
- HATEOAS
- Hypermedia
- REST

#### Properties

- [Documentation](https://docs.spring.io/spring-data/rest/docs/current/reference/html/)
- [API Reference](https://docs.spring.io/spring-data/rest/docs/current/api/)
- [Git Hub](https://github.com/spring-projects/spring-data-rest)
- [H A L Browser](https://docs.spring.io/spring-data/rest/docs/current/reference/html/#tools.hal-explorer)
- [Postman Collection](collections/spring-boot-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-initializr-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Cloud Gateway API

Spring Cloud Gateway provides an API Gateway built on Spring WebFlux and Reactor. It offers route configuration, request/response filtering, load balancing, circuit breaking, rate limiting, and retry capabilities via a fluent Java DSL or YAML configuration. The Actuator endpoint exposes live route and filter information.

#### Tags

- API Gateway
- Cloud
- Load Balancing
- Routing
- Security

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-gateway)
- [Samples](https://github.com/spring-cloud/spring-cloud-gateway/tree/main/spring-cloud-gateway-sample)
- [Postman Collection](collections/spring-boot-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-initializr-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Authorization Server API

Spring Authorization Server provides a full OAuth 2.1 and OpenID Connect 1.0 authorization server implementation built on Spring Security. It supports authorization code flow, client credentials, device authorization, token introspection, and token revocation. Exposes standard OAuth 2 endpoints.

#### Tags

- Authorization
- OAuth 2.0
- OpenID Connect
- Security

#### Properties

- [Documentation](https://docs.spring.io/spring-authorization-server/reference/)
- [Git Hub](https://github.com/spring-projects/spring-authorization-server)
- [O Auth Guide](https://spring.io/guides/tutorials/spring-boot-oauth2/)
- [Postman Collection](collections/spring-boot-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-initializr-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring AI API

Spring AI provides a Spring-friendly API and abstractions for building AI-powered applications. It offers a unified ChatClient API for interacting with AI models (OpenAI, Anthropic, Google Gemini, Ollama, and others), along with vector store integrations, prompt templates, output parsers, and function calling support. Follows portable, modular Spring design principles.

#### Tags

- AI
- Chatbot
- GenAI
- LLM
- Machine Learning

#### Properties

- [Documentation](https://docs.spring.io/spring-ai/reference/)
- [Git Hub](https://github.com/spring-projects/spring-ai)
- [Getting Started](https://docs.spring.io/spring-ai/reference/getting-started.html)
- [Postman Collection](collections/spring-boot-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-initializr-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spring.io)
- [Git Hub](https://github.com/spring-projects)
- [Documentation](https://docs.spring.io)
- [Blog](https://spring.io/blog)
- [Community](https://spring.io/community)
- [Guides](https://spring.io/guides)
- [Events](https://spring.io/events)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework)
- [Releases](https://github.com/spring-projects/spring-framework/releases)

## Maintainers

**Email:** spring-team@vmware.com
**URL:** https://spring.io/team
