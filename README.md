# Hi, I'm Ruslan 👋

**Senior Backend Engineer | Go · .NET | Distributed Systems**

I build backend systems where reliability matters: high-volume background processing,
marketplace integrations, payments, and services that stay correct under retries, crashes, and API limits.

## 💼 What I work on

- Lead a 5-person backend team on an ERP ↔ marketplace integration platform
  (~1.4M jobs/day, peaks of 180K jobs/hour)
- Scaled job processing horizontally across two nodes with queue-based workload distribution
- Cut marketplace API costs by 70% ($4,000 → $1,200/month) with adaptive request batching
- Built Go services for transactions, loyalty, and notifications extracted from a monolith

## 🚀 Featured Project

### [OrderSync Platform](https://github.com/Ruslan131132/ordersync-platform)

Reliable ERP ↔ marketplace order sync in Go: multiple worker replicas, shared rate limits,
and exactly-once remote side effects under retries and crashes.

- Lease-based claiming with `SKIP LOCKED` and fenced completion — no global lock on the hot path
- Shared Redis token bucket per token and method across all replicas
- Three-layer idempotency (marketplace key, sync ledger, HTTP) — 0 duplicate writes under injected ghost writes
- Adaptive batching, transactional outbox, leader election, crash recovery
- Prometheus + Grafana dashboard, pprof, integration tests, CI

*Go · PostgreSQL · Redis · Docker · Prometheus · Grafana*

## 🛠️ Tech

- **Languages:** Go, C# / .NET, PHP
- **Data:** PostgreSQL, MS SQL Server, MongoDB, Redis
- **Messaging & jobs:** Kafka, RabbitMQ, Hangfire
- **Infra & observability:** Docker, Kubernetes, TeamCity CI/CD, Prometheus, Grafana

## 🎓 University

**[Access Control System](https://github.com/Ruslan131132/access-control-system)** — graduation project:
physical access control with one-time QR codes, API verification, mobile client, RabbitMQ event processing.
*Laravel · PHP · RabbitMQ · Docker*

<details>
<summary>More university projects</summary>

- [Drivers & Trusted Computing Labs](https://github.com/Ruslan131132/device-drivers-labs) — FS encryption, software protection, Intel SGX, biometrics. *C · C++ · Qt/QML*
- [Electronic Diary](https://github.com/Ruslan131132/electronic-diary) — school management web app. *PHP · Laravel*
- [Arkanoid Qt](https://github.com/Ruslan131132/arkanoid-qt) — team project, OOP game core. *C++ · Qt*

</details>

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/ruslan-khasanshin-ba12a5420) · [Telegram](https://t.me/ruskhas)
