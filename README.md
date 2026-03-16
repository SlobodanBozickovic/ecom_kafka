# OrderFlow — Kafka Microservices (Java / Spring Boot)

Portfolio project for learning Apache Kafka by building production-like event-driven microservices in Java (Spring Boot).

## Repository structure

```text
services/
  order-service/
  inventory-service/
  payment-service/
  notification-service/
infra/
  docker/
docs/
  conventions.md
```

## How to run (initial)

Run `order-service`:

```bash
cd services/order-service
mvn test
mvn spring-boot:run
```

Health check:

```bash
curl -s localhost:8080/actuator/health
```

## License

TBD
