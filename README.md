# Spring Framework

Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, messaging, cloud-native patterns, and AI integrations. Spring Boot enables rapid application development with embedded servers and auto-configuration.

**Website:** [spring.io](https://spring.io)
**GitHub:** [github.com/spring-projects](https://github.com/spring-projects)
**Documentation:** [docs.spring.io](https://docs.spring.io)
**Maintainer:** Spring Team at VMware

## APIs

| API | Description | OpenAPI |
|---|---|---|
| Spring Boot Actuator API | Production-ready management endpoints for monitoring and operations | [openapi](openapi/spring-boot-actuator-openapi.yml) |
| Spring Initializr API | Project generation API for bootstrapping Spring Boot projects | [openapi](openapi/spring-initializr-api-openapi.yml) |
| Spring Data REST API | Automatic hypermedia REST API exposure for Spring Data repositories | — |
| Spring Cloud Gateway API | Reactive API gateway with routing and filtering | — |
| Spring Authorization Server API | OAuth 2.1 and OpenID Connect 1.0 authorization server | — |
| Spring AI API | Unified AI model integration with ChatClient API | — |

## Artifacts

### OpenAPI Specifications

- [spring-boot-actuator-openapi.yml](openapi/spring-boot-actuator-openapi.yml) — Spring Boot Actuator endpoints: health, metrics, info, environment, loggers, mappings, thread dump, beans
- [spring-initializr-api-openapi.yml](openapi/spring-initializr-api-openapi.yml) — Spring Initializr project generation and metadata API

### Spectral Rules

- [spring-rules.yml](rules/spring-rules.yml) — Spectral ruleset for Spring API conventions including actuator content type, camelCase operation IDs, and Title Case summaries

### JSON Schema

- [spring-boot-application-schema.json](json-schema/spring-boot-application-schema.json) — Schema for Spring Boot project descriptor (Initializr parameters)
- [spring-actuator-health-schema.json](json-schema/spring-actuator-health-schema.json) — Schema for Spring Boot Actuator health response

### JSON Structure

- [spring-boot-application-structure.json](json-structure/spring-boot-application-structure.json) — Field documentation for Spring Boot project descriptor

### JSON-LD

- [spring-context.jsonld](json-ld/spring-context.jsonld) — JSON-LD context for Spring Framework vocabulary aligned with schema.org and DOAP

### Examples

- [spring-initializr-generate-example.json](examples/spring-initializr-generate-example.json) — Generate a Spring Boot project with web, JPA, security, and actuator starters
- [spring-actuator-health-example.json](examples/spring-actuator-health-example.json) — Retrieve application health status with component details

### Vocabulary

- [spring-vocabulary.yml](vocabulary/spring-vocabulary.yml) — Spring Framework domain vocabulary (Spring Boot, Actuator, Data REST, Security, Cloud Gateway, AI)

## Key Projects

- **[Spring Boot](https://spring.io/projects/spring-boot)** — Rapid application development with auto-configuration and embedded servers
- **[Spring Data REST](https://spring.io/projects/spring-data-rest)** — Automatic HATEOAS REST APIs from Spring Data repositories
- **[Spring Cloud Gateway](https://spring.io/projects/spring-cloud-gateway)** — Reactive API gateway
- **[Spring Authorization Server](https://spring.io/projects/spring-authorization-server)** — OAuth 2.1 / OIDC 1.0 authorization server
- **[Spring AI](https://spring.io/projects/spring-ai)** — AI application framework with unified LLM client API

## Tags

AI, Cloud Native, Enterprise, Framework, Java, Microservices, Open Source, REST, Spring Boot
