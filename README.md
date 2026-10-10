# Hi, I'm Sahuri Abqori 👋
### Principal Software Engineer & FinTech Architect

I am a veteran Software Engineer with nearly 20 years of experience specializing in building secure, high-availability, and highly scalable distributed systems for the **Banking** and **Insurance** industries.

- 🏦 **Expertise**: Core Banking Integrations, Loan Disbursement Systems, High-Volume Payment Gateways (VA, Credit Card, QRIS).
- 🚀 **Current Focus**: High-concurrency optimization using **Java 21 Virtual Threads** and Event-Driven Architectures with **Apache Kafka**.
- 🛠️ **Roles**: Software Architect | Tech Lead | Scrum Master.

---

### 🧰 Tech Stack & Tools

- **Languages**: Java (1.8, 11, 17, 21), SQL
- **Frameworks**: Spring Boot 3.x, Spring Cloud, Hibernate, Spring Data JPA
- **Event Streaming & Messaging**: Apache Kafka
- **Concurrency**: Virtual Threads (Project Loom), Advanced Multi-threading
- **Architecture**: Microservices, Event-Driven Architecture (EDA), Domain-Driven Design (DDD)
- **Databases**: PostgreSQL, MySQL, Oracle

---
### 🏗️ Featured Technical Showcases & Architecture

*As most of my enterprise production work falls under strict financial NDAs, I use this personal space to benchmark, experiment, and share open-source simulations of core backend patterns.*

- 🤖 **[payment-agent-system](https://github.com/Sahuri/payment-agent-system)**: A three-service Spring Boot monorepo that puts an **LLM on top of payment data**. Payment operations are exposed as **Spring AI `@Tool`** methods and consumed over **MCP**, with **OpenRouter** as the model gateway — a natural-language question becomes a tool call instead of yet another hand-written REST endpoint. Explores how agentic AI can sit on top of a FinTech domain safely.
- 🚀 **[multithreading-technique](https://github.com/Sahuri/multithreading-technique)** *(formerly `ThreadTest`)*: A high-concurrency benchmarking laboratory focused on performance tuning. It simulates **1 to 100,000 parallel API calls**, switching between a dynamically sized `ExecutorService` pool and `ForkJoinPool.commonPool()` based on load, synchronized with `CountDownLatch` and guarded against overlapping `@Scheduled` executions. It explores modern Java concurrency models — including **Java 21 Virtual Threads (Project Loom)** — for optimizing massive transaction throughput.
- 🛡️ **[JavaAopFilter](https://github.com/Sahuri/JavaAopFilter)**: A production-ready architectural pattern showcasing decoupled cross-cutting concerns using **Spring AOP and Custom Filters**. Essential for FinTech applications to handle centralized logging, security auditing, and request validation without cluttering core business logic.
- 📡 **[SpringEventListener](https://github.com/Sahuri/SpringEventListener)**: Asynchronous, **event-driven transaction processing** with `ApplicationEventPublisher` and `@EventListener`. The controller returns `202 Accepted` immediately while processing continues off the request thread — the decoupling pattern behind high-throughput payment intake.
- 📊 **[flink-csv-mssql](https://github.com/Sahuri/flink-csv-mssql)**: A high-performance Big Data pipeline project utilizing **Apache Flink 1.19** to ingest, process, and stream large-scale CSV datasets into **Microsoft SQL Server** via JDBC. Demonstrates expertise in stream processing and data integration patterns crucial for enterprise analytics.

---

### 🤝 Connect with Me
- 💼 LinkedIn: [linkedin.com/in/sahuri-abqori-b58696aa](https://www.linkedin.com/in/sahuri-abqori-b58696aa)
- 📧 Open to global remote opportunities, architectural consultations, and technical leadership roles.
