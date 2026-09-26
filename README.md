# financial-portfolio-feed

Feed de cotações do financial-portfolio: publica preços simulados no Kafka. Spring Boot 4.1, Java 25.

Pré-requisito: infraestrutura de pé (`docker compose up -d` em `financial-portfolio-infra`).

Subir: `./mvnw spring-boot:run`

Health: http://localhost:8081/actuator/health
