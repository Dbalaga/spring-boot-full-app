# spring-boot-full-app
# Spring Boot Full App - Microservice Architecture

This is a full-stack Spring Boot microservice application featuring:
- Spring Web, Spring Data JPA, Spring Security
- Spring Cloud: Eureka, Config Server, Gateway
- JWT Authentication
- Centralized Config, Logging, Monitoring
- Kafka Messaging (Spring Cloud Stream)
- Docker + Docker Compose

## Modules

- `config-server` - Central configuration service
- `eureka-server` - Service registry for discovery
- `api-gateway` - Edge routing and auth filtering
- `auth-service` - JWT-based login and token management
- `user-service` - User management APIs
- `product-service` - Product catalog
- `common-lib` - Shared DTOs, utilities, aspects

## Run the application

```bash
./mvnw clean install
docker-compose up --build

