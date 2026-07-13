# High Level Design

## Architecture

                Client
                   |
             REST API
                   |
          Spring Boot Backend
      -----------------------------
      |            |              |
 Payment     AI Service      User Service
 Service
      |            |
 PostgreSQL     OpenAI API
      |
 Redis Cache
      |
 Kafka
      |
 Docker
      |
 Kubernetes
      |
 AWS

---

## Components

- REST Controller
- Service Layer
- Repository Layer
- AI Module
- PostgreSQL
- Redis
- Kafka
