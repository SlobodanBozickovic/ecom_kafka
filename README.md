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
## How to run (local)

```bash
docker compose -f infra/docker/docker-compose.yml up -d
```
### Kafka UI
Access Kafka UI at [http://localhost:8081](http://localhost:8081)

### PostgreSQL
- Host: `localhost`
- Port: `5432`
- Username: `orderflow`
- Password: `orderflow`

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
