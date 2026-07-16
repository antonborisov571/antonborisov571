# Привет, я Антон 👋

Бэкенд-разработчик. Днём пишу высоконагруженный HR-tech на C#, вечерами копаю распределённые системы — интереснее всего то, как они ломаются и что с этим делать.

## Стек

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%2010-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=trpc&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

## Проекты

### Распределённые системы

| Проект | О чём | На чём |
|---|---|---|
| **[orderflow](https://github.com/antonborisov571/orderflow)** | Event-driven платформа обработки заказов: CQRS и event sourcing без фреймворков, сага на Kafka с компенсациями, 6 сервисов, live-дашборд, полная наблюдаемость. В README — графики реальных нагрузочных прогонов | .NET 10, Kafka, gRPC, React, OTel, Helm |
| **[hoard](https://github.com/antonborisov571/hoard)** | Распределённый LRU-кэш: consistent hashing с virtual nodes, асинхронная репликация primary/replica, бенчмарки ~20 нс/оп | Go, gRPC |
| **[lnk](https://github.com/antonborisov571/lnk)** | Горизонтально шардированный URL shortener: своё hash ring, failover по кольцу, встраиваемое хранилище | Rust, axum, sled |
| **[chatbus](https://github.com/antonborisov571/chatbus)** | Масштабируемый WebSocket-чат: fan-out между нодами через Kafka, presence в Redis, деградация до одной ноды без внешних зависимостей | Node/TS, Fastify |

### Надёжность и наблюдаемость

| Проект | О чём | На чём |
|---|---|---|
| **[shakedown](https://github.com/antonborisov571/shakedown)** | Chaos-эксперименты по YAML-сценарию: toxiproxy + k6, отчёт с дельтами деградации к baseline. Обкатан на живом orderflow | Go |
| **[toll](https://github.com/antonborisov571/toll)** | Rate limiter: четыре алгоритма с честным сравнением, Redis-режим для кластера, reverse proxy с метриками | Go |
| **[drift](https://github.com/antonborisov571/drift)** | Поиск аномалий в метриках Prometheus: сезонный z-score и Isolation Forest, отчёты с графиками | Python, sklearn |
| **[obskit](https://github.com/antonborisov571/obskit)** | Observability-стек одним compose: OTel Collector, Jaeger, Prometheus, Loki, Grafana + сквозной трейс через демо на трёх языках | OTel, Grafana |

### Библиотеки и инструменты

| Проект | О чём | На чём |
|---|---|---|
| **[eventual](https://github.com/antonborisov571/eventual)** | Event sourcing библиотека, выросшая из orderflow: агрегаты, снапшоты, Postgres event store, транзакционный outbox, бенчмарки | .NET 10 |
| **[mksvc](https://github.com/antonborisov571/mksvc)** | CLI-скаффолдер микросервисов: шаблоны Go/.NET/Node/compose/CI, dry-run, тесты собирают сгенерированные проекты | Go |

## Статистика

<img alt="Метрики GitHub" src="github-metrics.svg" width="100%">

