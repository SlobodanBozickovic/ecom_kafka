# Conventions

## Language & Build

- Java: 21
- Framework: Spring Boot
- Build tool: Maven

## Repository Layout

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

## Branching Strategy

- Default branch: `main`
- Feature branches: `feature/<short-description>`

## Commit Messages (Conventional Commits)

- `feat: ...` — new feature
- `fix: ...` — bug fix
- `chore: ...` — tooling/infra/maintenance
- `docs: ...` — documentation
- `test: ...` — tests
- `refactor: ...` — refactoring

Examples:
- `chore: initialize repository structure and docs`
- `feat(order-service): implement create order endpoint`

## Testing

- Run tests locally:
  - `mvn test`
