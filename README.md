# systems-design-case-studies

# System Design: Messaging App

## 🧩 Problem Statement
Design a scalable, fault-tolerant messaging system like Slack or WhatsApp.

## 📦 Core Components
- Client
- WebSocket/API Gateway
- Messaging queue (e.g., Kafka)
- Message service
- Database (e.g., Cassandra, PostgreSQL)

## ⚖️ Key Considerations
- Real-time delivery
- Message persistence
- User presence
- Offline support

## 🔁 Data Flow
1. Client sends message → API gateway
2. Gateway pushes to Kafka queue
3. Message service reads from Kafka → writes to DB + pushes to recipient

## 🔐 Security
- TLS encryption
- JWT auth
- Rate limiting per client

## 🛠️ Tradeoffs
- Kafka vs RabbitMQ
- SQL vs NoSQL for message store
- Push vs polling for delivery

## 🧠 Lessons Learned
- Use idempotent message IDs to avoid duplicates
- DB writes should be async if latency matters
