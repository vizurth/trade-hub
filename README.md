# TradeHub

**TradeHub** is a microservices-driven online auction platform built with Go. It demonstrates:

- **Real-time bidding and lot management** via gRPC
- **Event streaming** using Kafka for actions like "new bid" or "lot sold"
- **Asynchronous task processing** with RabbitMQ for notifications and background jobs
- **Caching** frequently accessed data (current prices, recent bids) with Redis
- **Containerized deployment** using Docker for all services, databases, and brokers
- **Monitoring and observability** via Prometheus and Grafana

TradeHub is ideal for showcasing scalable architecture, real-time event handling, and production-ready microservices patterns.

