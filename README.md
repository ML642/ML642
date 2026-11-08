
<div align="center">

**Software Engineering · Full-Stack Development · Open Source**


</div>

## Engineering

I enjoy working across the stack, from responsive interfaces and client-side data flows to authentication, networking, concurrency, data consistency, and service boundaries.

**Core stack:** `TypeScript` `JavaScript` `C++` `Node.js` `React` `Express` `MongoDB` `PostgreSQL` `Redis` `RabbitMQ` `Docker` `Linux`

## Open Source

I contribute bug fixes, regression tests, and reliability improvements to established open-source projects. I enjoy investigating unexpected behavior, understanding existing abstractions, and working with maintainers to find solutions that fit the codebase.

### [WebdriverIO](https://github.com/webdriverio/webdriverio)

**17 merged pull requests · Browser automation and testing infrastructure**

WebdriverIO is an open-source framework for browser and mobile automation. My contributions span browser lifecycle management, networking, asynchronous execution, mocking, and runtime correctness.

#### [#15621 — Browser lifecycle and resource cleanup](https://github.com/webdriverio/webdriverio/pull/15621)

Closed browser instances could remain registered in internal state even after their sessions ended. I corrected the lifecycle handling so that stale instances are removed when a browser closes, preventing the framework from retaining references to resources that are no longer active.

#### [#15617 — Bounded retries and failure handling](https://github.com/webdriverio/webdriverio/pull/15617)

The Sumo Logic reporter could repeatedly retry failed synchronization attempts during persistent failures. I introduced bounded retry behavior so that temporary failures could be retried without allowing the reporter to continue indefinitely when recovery was not possible.

#### [#15516 — IPv6 support in WebDriver BiDi connections](https://github.com/webdriverio/webdriverio/pull/15516)

WebDriver BiDi connection fallback could generate invalid WebSocket URLs when an address contained IPv6 syntax. I fixed URL serialization to handle IPv6 addresses correctly and added regression tests for the affected connection paths.

[View all WebdriverIO contributions →](https://github.com/webdriverio/webdriverio/pulls?q=is%3Apr+author%3AML642)

### [Faker.js](https://github.com/faker-js/faker)

**2 merged pull requests · Test data generation**

Faker.js is a JavaScript and TypeScript library for generating realistic test data. My contributions focused on edge cases that could produce invalid results or prevent generation from completing.

#### Git branch generation with locale-specific input

Git branch generation could produce invalid output when source data contained unexpected whitespace. I corrected the handling of multi-word locale values so that generated branch names remained valid under these conditions.

#### [#4088 — Preventing an infinite loop in currency generation](https://github.com/faker-js/faker/pull/4088)

The `currencySymbol()` method could become stuck when the available currency data contained no usable symbols. I addressed this edge case to prevent non-terminating execution and make the behavior predictable for unusual locale configurations.

[View Faker.js contributions →](https://github.com/faker-js/faker/pulls?q=is%3Apr+author%3AML642)

### [Tapflow](https://github.com/jo-duchan/tapflow)

**5 merged pull requests · Mobile testing infrastructure**

Tapflow is a self-hosted platform for streaming and controlling iOS and Android simulators. My contributions involved asynchronous scheduling, application behavior, and regression coverage.

#### [#656 — Race condition in network-state requests](https://github.com/jo-duchan/tapflow/pull/656)

An overdue timer could overlap with an in-flight request and trigger duplicate network-state operations. I fixed the scheduling edge case and added deterministic tests to verify the behavior without relying on timing-sensitive execution.

#### [#777 — Correct password-reset URLs](https://github.com/jo-duchan/tapflow/pull/777)

Password-reset emails could use an incorrect URL instead of the application's configured public address. I updated the relay to use the configured URL, ensuring that reset links point to the intended deployment.

#### [#694 — Regression tests for dashboard reset behavior](https://github.com/jo-duchan/tapflow/pull/694)

I expanded dashboard test coverage around reset behavior when the active agent changes. These tests help detect regressions in state transitions that could otherwise be missed by ordinary interaction tests.

[View all Tapflow contributions →](https://github.com/jo-duchan/tapflow/pulls?q=is%3Apr+author%3AML642)

[Explore all my open-source pull requests →](https://github.com/pulls?q=is%3Apr+author%3AML642)

## Selected Projects

### [Movie Reservation System](https://github.com/ML642/movie-reservation)

A full-stack reservation platform built around explicit domain boundaries, independently deployable backend services, and a React client application.

`TypeScript` `Node.js` `Express` `React` `MongoDB` `RabbitMQ` `Docker`

**Key engineering points:**
- Domain-Driven Design and Ports & Adapters
- API Gateway and service-oriented backend architecture
- Identity, Reservation, and Engagement services
- Google and GitHub OAuth 2.0, JWT authentication, and rotating refresh tokens
- Hashed refresh tokens with replay protection
- RabbitMQ-based domain events and asynchronous communication
- MongoDB transactions and database-level double-booking protection
- Unit and integration testing

### MAPA Event Discovery Platform

A full-stack platform for discovering youth events through an interactive, map-oriented interface.

`TypeScript` `React` `Vite` `Node.js` `Express` `MongoDB` `Redis` `Mapbox GL`

**Key engineering points:**
- Responsive React interface with interactive event maps
- Search, filtering, and event discovery workflows
- REST API and Google OAuth authentication
- TanStack Query for asynchronous server-state management
- MongoDB-backed event storage and Redis caching
- Docker-based deployment

[Live Demo →](https://frontend-ecru-alpha-77d5ceb795.vercel.app/)

## Experience & Achievements

**Software Developer Intern — Innowise (2026)**  
Worked with backend development technologies including Node.js, NestJS, PostgreSQL, REST APIs, and Docker.

**Top 3 — Google Student AI Hackathon Warsaw 2026**  
Collaborated in a five-person team to develop a multi-agent web accessibility auditing platform using Gemini, browser automation, and Google Cloud.


## Competitive Programming

I practice algorithms and data structures in **C++**, including Codeforces and ICPC-style problems.

`Graphs` · `Dynamic Programming` · `Greedy` · `Binary Search` · `Trees` · `Number Theory`

## Tech

| Area | Technologies |
| --- | --- |
| Languages | TypeScript, JavaScript, C++, C, C#, SQL |
| Backend | Node.js, NestJS, Express, REST, OAuth 2.0, JWT |
| Frontend | React, Vite, TanStack Query, React Router, Mapbox GL |
| Databases | PostgreSQL, MongoDB, Redis |
| Messaging | RabbitMQ, WebSockets |
| Infrastructure | Docker, Docker Compose, Linux, Git, GitHub Actions, Google Cloud |
