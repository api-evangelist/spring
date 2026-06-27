---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 introduces a new spring-boot-starter-batch-data-mongodb autoconfiguration that stores Spring Batch JobRepository metadata in MongoDB instead of requiring a SQL database. The post demonstrates a complete ETL example that reads from a CSV file, uses MongoDB for batch job tracking, and writes data to PostgreSQL, and also covers GraalVM native image support and lazy datasource connections.
