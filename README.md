<div align="center">

**Full-Stack Engineering · Open Source  **

TypeScript / Node.js developer building full-stack applications with a focus on backend systems, reliability, clean architecture and practical frontend engineering.

</div>

---

## Engineering

I enjoy working across the stack, from responsive interfaces and client-side data flows to authentication, networking, concurrency, data consistency and service boundaries.

**Core stack**

`TypeScript` `Node.js` `React` `Express` `C++`  `MongoDB` `Redis` `RabbitMQ` `Docker` `Linux`

---

## Open Source

I contribute production bug fixes, regression tests and reliability improvements to established open-source projects.

### [WebdriverIO](https://github.com/webdriverio/webdriverio)

**15+ pull requests · fixes shipped in multiple releases · ~2M weekly npm downloads**

WebdriverIO is a widely used browser and mobile automation framework in the JavaScript ecosystem.

#### [#15621 — Fixed retained closed browser instances](https://github.com/webdriverio/webdriverio/pull/15621)

Improved browser lifecycle handling by preventing closed browser instances from remaining registered in internal state.

`browser lifecycle` · `state management` · `reliability`

#### [#15620 — Fixed incorrect original module type handling in mock factory](https://github.com/webdriverio/webdriverio/pull/15620)

Corrected module-type preservation in the mocking infrastructure to avoid incorrect runtime behavior when wrapping or restoring modules.

`mocking` · `module systems` · `runtime correctness`

#### [#15617 — Added bounded retries to the Sumo Logic reporter](https://github.com/webdriverio/webdriverio/pull/15617)

Improved reporter reliability by introducing bounded retry behavior for failed synchronization attempts.

`retry logic` · `reporting` · `fault tolerance`

#### [#15552 — Rejected invalid timeout values](https://github.com/webdriverio/webdriverio/pull/15552)

Added validation for invalid timeout inputs to prevent inconsistent runtime behavior and improve API correctness.

`validation` · `error handling` · `runtime reliability`

#### [#15537 — Fixed classic cookie filtering with multiple attributes](https://github.com/webdriverio/webdriverio/pull/15537)

Corrected `browser.getCookies()` filtering so that all supplied attributes must match instead of accepting partial matches.

`browser APIs` · `filtering semantics` · `regression testing`

#### [#15516 — Fixed IPv6 serialization for BiDi WebSocket candidate URLs](https://github.com/webdriverio/webdriverio/pull/15516)

Fixed invalid WebSocket candidate URL generation for IPv6 addresses in WebDriver BiDi connection logic and added regression coverage.

`networking` · `WebDriver BiDi` · `IPv6` · `regression testing`

### [Tapflow](https://github.com/jo-duchan/tapflow)

**5+ pull requests · mobile testing infrastructure · 800+ GitHub stars**

Tapflow is a self-hosted platform for streaming and controlling iOS and Android simulators. 

#### [#656 — Fixed duplicate network-state requests caused by timer/request race conditions](https://github.com/jo-duchan/tapflow/pull/656)

Resolved an overdue timer/request edge case that could trigger duplicate network-state requests.

Added deterministic scheduler tests and integration coverage around relay behavior.

`concurrency` · `timers` · `networking` · `deterministic testing`

[View all contributions →](https://github.com/pulls?q=is%3Apr+author%3AML642)

### Selected Projects

### [Movie Reservation System](https://github.com/ML642/movie-reservation)

Full-stack reservation platform designed around explicit domain boundaries, independently deployable services and a modern client application.

`TypeScript` `Node.js` `Express` `React` `MongoDB` `RabbitMQ` `Docker`

Key engineering points:

* Domain-Driven Design and Ports & Adapters
* API Gateway and service-oriented backend structure
* React-based client application
* client-side routing and asynchronous server-state handling
* OAuth 2.0 with Google and GitHub
* short-lived access tokens and rotating refresh tokens
* hashed refresh tokens with replay protection
* RabbitMQ-based domain events
* MongoDB transactions
* database-level double-booking protection
* unit and integration testing

### MAPABY

Full-stack platform for discovering youth events through an interactive, map-oriented interface.

[Live Demo →](https://frontend-ecru-alpha-77d5ceb795.vercel.app/)

`TypeScript` `React` `Vite` `Node.js` `Express` `MongoDB` `Redis` `Mapbox GL`

Key engineering points:

* responsive React interface for browsing and discovering events
* interactive map-based event exploration
* filtering, search and event discovery flows
* TanStack Query for server-state management and caching
* Google OAuth authentication
* REST API built with Node.js and Express
* MongoDB-backed event storage
* Redis-backed caching and backend infrastructure
* responsive layouts and mobile-oriented UI behavior
* Docker-based deployment setup

---

## Competitive Programming

I practice algorithms and data structures in **C++**, with a focus on **Codeforces** and **ICPC-style** contests.

Current areas:

`graphs` · `dynamic programming` · `greedy` · `binary search` · `trees` · `number theory`

---

## Tech

| Area           | Tools                                                |
| -------------- | ---------------------------------------------------- |
| Languages      | TypeScript, JavaScript, C++, Java, Python, SQL       |
| Backend        | Node.js, Express, REST, OAuth 2.0, JWT               |
| Frontend       | React, Vite, TanStack Query, React Router, Mapbox GL |
| Databases      | MongoDB, Redis, SQL                                  |
| Messaging      | RabbitMQ                                             |
| Infrastructure | Docker, Docker Compose, Linux, Git, GitHub Actions   |

---

<div align="center">

### Build the interface. Trace the failure mode. Fix the abstraction.

</div>
