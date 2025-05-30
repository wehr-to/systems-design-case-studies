# 🧱 systems-design-case-studies

This repository contains real-world case studies and architecture breakdowns for various system designs, from internal tools and scalable web apps to event pipelines, authentication layers, and message queues. Each case explores scalability, availability, performance, and security trade-offs.

## 🎯 Why This Repo?

System design isn't just about uptime — it's about making the right trade-offs under business, technical, and security constraints.

This repo helps you:
- **Think like an architect**
- **Design like an engineer**
- **Secure like a defender**

## 📁 Categories

| Folder | Description |
|--------|-------------|
| `web-app-3tier/` | Classic 3-tier design with scalability and HA |
| `internal-tools-design/` | Apps with RBAC, auditing, and organizational boundaries |
| `cloud-native-event-pipeline/` | Pub/sub, stream processing, queues, and fan-out |
| `authentication-system/` | Token flows, OAuth2, session handling, attack surfaces |
| `load-balancer-scenarios/` | Geo-routing, reverse proxying, layer 7 vs layer 4 |
| `dns-infra/` | Failover, split-horizon DNS, custom resolvers |
| `messaging-and-queues/` | Design patterns using SQS, Kafka, RabbitMQ |
| `security-considerations/` | Encryption, trust boundaries, zero trust, layered authz |
| `docs/` | Design philosophy, latency vs throughput, templates, glossary |

## 🛠️ Case Study Format

Each design includes:
- 📐 `diagram.png`: Network or component-level diagram
- 🧩 `components.md`: Layer breakdowns and interfaces
- 🚦 `scalability.md`: Vertical vs horizontal, bottlenecks
- 🛡️ `security.md`: Threat modeling, boundary protections
- ❌ `failure-modes.md`: Known risks, failure scenarios, recovery paths

## 🔐 Security Layering Examples

Many systems are analyzed through a security lens:
- **Where are the trust boundaries?**
- **What happens if this token is stolen?**
- **How is isolation enforced between components?**
- **Can auth bypass occur during scaling events?**

## 🧠 Ideal Use Cases

- Studying for systems design interviews
- Documenting your understanding of real architectures
- Building muscle memory around trade-off analysis
- Demonstrating high-level engineering thinking

