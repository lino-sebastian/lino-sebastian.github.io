# Lino Sebastian

### Senior Software Engineer · Java · Spring Boot · AWS · Distributed Systems

**Nottingham, UK**  
[LinkedIn](#) · [GitHub](#) · [Email](mailto:lino.lsebastian@gmail.com)

---

## Building systems that scale with confidence

I’m a **Senior Software Engineer with 6+ years of experience** designing and delivering scalable, cloud-native software across **banking, insurance and travel**.

My core expertise is in **Java, Spring Boot, AWS, microservices and distributed/event-driven architectures**, with experience owning features end-to-end — from technical design and implementation through testing, CI/CD deployment and production support.

I enjoy solving complex engineering problems, improving system resilience and observability, and helping teams build software that is reliable, maintainable and ready to scale.

---

## Engineering at a glance

| | |
|---|---|
| **6+ Years** | Software Engineering Experience |
| **Java 17** | Backend Development |
| **AWS** | Cloud-Native Engineering |
| **Microservices** | Distributed Architecture |
| **95%+** | Test Coverage Achievement |
| **Global Teams** | UK, US & Distributed Engineering |

---

# What I do

### Backend Engineering

I build production-grade backend services using:

- Java 17
- Spring Boot
- Kotlin
- Python
- REST APIs
- Microservices
- Event-driven architectures

### Cloud & Distributed Systems

I design cloud-native solutions with a focus on:

- Scalability
- Resilience
- Availability
- Performance
- Loose coupling
- Asynchronous processing
- Multi-tenant architectures

My AWS experience includes:

- AWS Lambda
- Amazon SQS
- Amazon EventBridge
- Amazon DynamoDB

### Engineering & Delivery

I have hands-on experience with:

- Docker
- Kubernetes
- Jenkins
- CI/CD pipelines
- Agile/Scrum
- TDD
- Unit testing
- Integration testing
- Code reviews
- System design
- SDLC

### Data & Messaging

- PostgreSQL
- MySQL
- MongoDB
- Cassandra
- RabbitMQ

### Observability

- ELK
- Production dashboards
- PagerDuty
- Monitoring
- Alerting
- Production support

---

# Professional Experience

## Senior Software Engineer

### UST · Client: Capital One, UK

**2024 — Present**

Designing and implementing scalable AWS serverless microservices supporting high-volume financial transaction processing.

### Key responsibilities & impact

- Design and implement scalable **AWS serverless microservices** supporting high-volume financial transaction processing.
- Translate functional requirements into component-level technical designs for distributed, event-driven systems.
- Own feature delivery end-to-end, from design discussions through implementation, testing, CI/CD deployment and production delivery.
- Architect event-driven workflows using **Amazon SQS and EventBridge** to provide loose coupling and resilient asynchronous processing.
- Collaborate with geographically distributed engineering teams across the **UK and US**.
- Participate in agile ceremonies, technical discussions and design reviews.
- Mentor junior engineers on cloud-native design patterns, engineering practices and code quality.

**Technology:**  
`Java` `Spring Boot` `AWS` `Lambda` `SQS` `EventBridge` `DynamoDB` `Microservices` `CI/CD`

---

## Senior System Engineer

### IBM · Client: Atradius

**2021 — 2024**

Worked on enterprise-grade, multi-tenant software and distributed microservices.

### Key responsibilities & impact

- Developed enterprise-grade **multi-tenant microservices using Spring Boot**.
- Led migration from a monolithic architecture to a **distributed microservices architecture**.
- Implemented continuous integration and deployment pipelines using **Jenkins**.
- Containerised services using **Docker and Kubernetes**.
- Participated in architecture discussions and technical design activities.
- Conducted code reviews and contributed to engineering and code-quality standards.
- Worked closely with globally distributed teams to communicate complex technical solutions clearly.

**Technology:**  
`Java` `Spring Boot` `Microservices` `Docker` `Kubernetes` `Jenkins` `CI/CD`

---

## Senior Software Engineer

### IBS Software · Client: Egencia

**2018 — 2021**

Built scalable travel-booking services supporting business travellers globally.

### Key responsibilities & impact

- Built scalable **travel-booking microservices** supporting global business travellers.
- Led implementation of loyalty/subscription card selection at checkout, eliminating fraudulent reward claims.
- Integrated **GDS booking systems** and delivered an MVP **two sprints ahead of schedule**.
- Developed event-driven integrations using **RabbitMQ** for asynchronous processing.
- Improved production observability using **ELK dashboards and PagerDuty alerts**.
- Revamped unit and integration testing practices, achieving **95%+ test coverage**.

**Technology:**  
`Microservices` `RabbitMQ` `ELK` `PagerDuty` `Unit Testing` `Integration Testing`

---

# Architecture & Engineering

## Designing for resilience

My approach to distributed systems is centred around designing for failure rather than assuming that every component will always be available.

A representative architecture pattern from my cloud-native experience:

```text
                    ┌─────────────────┐
                    │    REST API     │
                    │  Request Layer  │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   Spring Boot   │
                    │ Business Logic  │
                    └────────┬────────┘
                             │
                             ▼
                  ┌──────────────────────┐
                  │   Event / Messaging  │
                  │  SQS / EventBridge   │
                  └──────────┬───────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   Data Layer    │
                    │ AWS / Databases │
                    └─────────────────┘
