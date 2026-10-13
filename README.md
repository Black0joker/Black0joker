# Hi, I'm George Kamal Tawfic 👋

**Junior .NET Backend Developer** — Minya, Egypt

Student at the **Higher Institute of Management and Information Technology in Minya** (expected graduation **2027**). I build RESTful APIs with **C#, ASP.NET Core, EF Core, and SQL Server**, and integrate them with **Angular** clients (HTML, CSS, JavaScript/TypeScript).

## What I work with

- **Backend:** ASP.NET Core Web API, REST, DI, middleware, DTOs, validation, logging
- **Data:** EF Core, SQL Server, LINQ, migrations, indexes, pagination, transactions
- **Architecture:** Clean Architecture, CQRS + MediatR, DDD aggregates & state machines, outbox pattern, FluentValidation
- **Auth:** JWT access tokens, rotating hashed refresh tokens, RBAC
- **Messaging:** Redis (cache, Lua, rate limiting, Streams) · **RabbitMQ + MassTransit** (queues, exchanges, retry, DLQ, outbox)
- **Frontend:** Angular 22 (standalone components, signals, NgRx signals, routing, reactive forms, HttpClient, guards, interceptors, CDK, Tailwind), RxJS/Observables, runtime & Ivy concepts
- **DevOps:** Docker (Engine, images, containers, volumes, networks, DNS/NAT), Docker Compose, Prometheus metrics, health checks
- **Testing:** xUnit, WebApplicationFactory integration tests

## Featured projects

### 📋 [Task Management API + Angular Frontend](https://github.com/Black0joker/TaskManagement)
Production-grade project/task API: Clean Architecture + CQRS, JWT with hashed refresh tokens, Owner/Admin/Member roles, task workflow governance (`Todo → InProgress → InReview → Done/Cancelled`), pagination/filtering/sorting/search, ProblemDetails errors, rate limiting, structured logging, xUnit tests — plus an Angular 22 SPA with Kanban board, silent-refresh auth, and dark mode.
Frontend: [TaskManagementAngularFrontend](https://github.com/Black0joker/TaskManagementAngularFrontend)

### ⚙️ [JobQueueSystem](https://github.com/Black0joker/JobQueueSystem)
Background job processing with **RabbitMQ + MassTransit 8.5**: `202 Accepted` API, transactional outbox, idempotency keys, optimistic concurrency, retry with exponential backoff, dead-letter queue, scheduled jobs, stuck-job recovery, Prometheus metrics, Docker Compose with scalable workers.

### 💳 [PaymentSystem](https://github.com/Black0joker/PaymentSystem)
E-commerce payment platform (12 phases, **147/147 tests passing**): DDD, Stripe + fake provider, HMAC webhooks, layered idempotency, resilience decorator, refunds, reconciliation worker, Redis cache/lock/rate-limiting, MassTransit fan-out consumers (enrollment, notification, analytics).

### 🔗 [URL Shortener](https://github.com/Black0joker/URL-SHORTNER)
Redis-backed rate limiting (Lua atomic counters, sliding window) and Redis Streams click analytics aggregated into SQL Server.

## Currently learning

Automated testing depth, SQL performance tuning, Docker Compose deployments, Kubernetes basics, OpenTelemetry, and system design.

## Connect

- 📧 georgekamal4521@gmail.com
- 💻 [github.com/Black0joker](https://github.com/Black0joker)
- 📍 Minya, Egypt · Arabic (native) · English (intermediate)
