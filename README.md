# A repository to create tests in kafka

- docker compose

```bash
cd ./docker
docker compose up -d

```
-  producer

```bash
cd apps/producer

go run main.go

```

- consummer

```bash
cd apps/consumer

go run main.go
```