### Привет

Пишу бэкенд на C# и Go, днём — HR-tech (высоконагруженный ATS), вечерами — распределённые системы ради интереса к тому, как они ломаются.

Что посмотреть:

- **[orderflow](https://github.com/antonborisov571/orderflow)** — event-driven платформа обработки заказов: CQRS и event sourcing без фреймворков, сага на Kafka с компенсациями, 6 сервисов на .NET 10, React-дашборд с live-обновлениями, OpenTelemetry, Helm, k6-прогоны с графиками в README
- **[eventual](https://github.com/antonborisov571/eventual)** — event sourcing библиотека для .NET, выросшая из orderflow: снапшоты, Postgres event store, транзакционный outbox, бенчмарки
- **[toll](https://github.com/antonborisov571/toll)** — rate limiter на Go: четыре алгоритма, Redis-режим для кластера, reverse proxy, бенчмарки на десятки наносекунд
- **[shakedown](https://github.com/antonborisov571/shakedown)** — chaos-тестирование HTTP-стеков: toxiproxy + k6 по декларативному сценарию, отчёт с деградацией
- **[hoard](https://github.com/antonborisov571/hoard)** — распределённый LRU-кэш с consistent hashing и асинхронной репликацией (Go, gRPC)
- **[lnk](https://github.com/antonborisov571/lnk)** — шардированный URL shortener на Rust: своё hash ring с virtual nodes
- **[chatbus](https://github.com/antonborisov571/chatbus)** — горизонтально масштабируемый WebSocket-чат: fan-out через Kafka между нодами (Node/TS)
- **[drift](https://github.com/antonborisov571/drift)** — поиск аномалий в метриках Prometheus: сезонный z-score и Isolation Forest (Python)
- **[obskit](https://github.com/antonborisov571/obskit)** — готовый observability-стек одним compose: OTel Collector, Jaeger, Prometheus, Loki, Grafana + примеры инструментирования на трёх языках
- **[mksvc](https://github.com/antonborisov571/mksvc)** — CLI для скаффолдинга микросервисов из шаблонов (Go)

Стек: .NET / ASP.NET Core, Go, Kafka, Postgres, Redis, gRPC, Kubernetes, OpenTelemetry, React/TypeScript.
