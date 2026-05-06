<h1 align="center">Fullstack Developer</h1>
<p align="center"><strong>Senior Fullstack Developer</strong> focused on product impact, system architecture, and shipping end-to-end.</p>
<p align="center">Go • TypeScript • React • PostgreSQL • Realtime • Telegram Mini Apps • TON</p>
<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP" />
</p>

## About

- 7+ years in development and 3+ years building commercial products across crypto, gaming, prediction markets, and ecommerce.
- Strong in Go and React/TypeScript, with deep focus on realtime systems, Telegram Mini Apps, and TON ecosystem integrations.
- Led architecture and delivery on several Telegram Mini App products, including a P2P NFT marketplace, a prediction market, and a high-load gaming platform with 20+ domain modules.
- Comfortable owning a feature end-to-end: schema, API, UI, deploy, observability. Equally at home shipping a high-throughput WebSocket orderbook and a polished UI for the same product.
- Author of `asyngo`, an open-source Go library for generating AsyncAPI 3.0 specs from code annotations.
- Open to senior fullstack, backend, and platform-focused opportunities.

Background includes lead-level work across BitGift, Durov Caps, Pick, Asseco, and Accenture.

## Core Expertise

- Backend: Go, Chi, Gin, REST, WebSocket, JWT, pgx, sqlc, goose, River
- Frontend: TypeScript, React, Next.js, Vue, Vite, TanStack Query, Zustand, Zod, Tailwind
- Architecture: DDD, clean architecture, realtime systems, event-driven design, idempotent flows
- Databases: PostgreSQL, Redis, AlloyDB, ClickHouse, MongoDB, MySQL
- Quality: integration testing with Testcontainers, CI/CD, observability with Sentry and Prometheus
- Integrations: Telegram Bot API, Telegram Mini Apps, MTProto, TON, TON Connect, MinIO
- Infrastructure: Docker, Docker Compose, GitLab CI, GCP, nginx, systemd

## Selected Work

### TON P2P NFT Marketplace
`Commercial case study` · `Lead Fullstack Developer` · `Go, React, TypeScript, PostgreSQL, WebSocket, TON`

- Led architecture for a P2P NFT marketplace built on the TON blockchain inside a Telegram Mini App.
- Designed a high-throughput orderbook in Go with realtime updates over WebSocket, reducing perceived transaction latency for end users.
- Implemented a hardened blockchain integration layer with idempotent on-chain operations to prevent duplicated deposits.
- Built the data layer on PostgreSQL and sqlc, with Testcontainers-based integration tests to keep release stability high while shipping fast.
- Delivered the Telegram Mini App and admin SPA in React/TypeScript with a focus on conversion-critical flows.

### Realtime Gaming Platform
`Commercial case study` · `Lead Backend Developer` · `Go, PostgreSQL, Redis, WebSocket, GCP`

- Designed and grew a Go backend for a Telegram Mini App gaming product as a DDD monolith with 20+ domain modules: economy, balances, cases, PvP, marketplace, referrals, levels, seasonal mechanics.
- Built the realtime layer over WebSocket for live game state, balances, and broadcasts, removing the need for client polling.
- Integrated with the Telegram ecosystem at three levels: Bot API, business bot, and MTProto userbot for gift deposits and payment flows.
- Hardened the platform with circuit breakers, retry/backoff, Redis-based rate limiting, structured Sentry reporting, and Prometheus metrics.
- Migrated the project's infrastructure from DigitalOcean to GCP, preparing the platform for a more mature operational environment.
- Designed `asyngo`, an internal engineering tool for AsyncAPI 3.0 spec generation, later open-sourced.

### Prediction Market Platform
`Commercial case study` · `Lead Fullstack Developer` · `Go, React, TypeScript, PostgreSQL`

- Designed and delivered a Polymarket-style prediction market as a Telegram Mini App, where users participate in event markets and interact with trading logic inside Telegram.
- Built the product end-to-end as the primary engineer: frontend, backend, architectural decisions, product flows, integrations, and the technical foundation.
- Modeled the core domain entities and user flows that turned an abstract idea into a working Telegram product with a clear interaction model.
- Owned technical leadership for the project, making the key engineering calls and driving the product to a shippable state without separate frontend and backend teams.

### asyngo
`Public project` · `Go`

- Open-source Go library that generates AsyncAPI 3.0 specifications from code annotations, automating documentation for WebSocket and event-driven APIs.
- Used in production as an internal engineering tool, replacing manual maintenance of async API docs and making realtime contracts more systematic.
- Repository: [github.com/polanski13/asyngo](https://github.com/polanski13/asyngo)

### sCore
`Public project` · `Go, React, TypeScript, PostgreSQL`

- Community-driven ratings and reviews platform for the Telegram ecosystem: Mini Apps, bots, services, and teams.
- Frontend on React 19 + TypeScript + Vite with public ranking, voting, comments, issues, an SEO layer, and a rich animation system.
- REST API on Go + Chi + PostgreSQL covering reviews, comments, moderation, issues, and notifications.
- Telegram OIDC and initData authentication, Partner API, MinIO-backed media, goose migrations, and Testcontainers integration tests.

## How I Work

- Simple over clever. Working over elegant.
- Migrations, observability, and rollback paths are part of the feature, not an afterthought.
- I'd rather ship a smaller thing this week than a perfect thing next quarter.
- Comfortable taking technical leadership across the full stack without splitting the work into frontend and backend silos.

## Contact

- Email: [a_polanski@wolfram.id](mailto:a_polanski@wolfram.id)
- Languages: English (B2) · Russian (Native) · Polish (B1) · Danish (A1)

If you are hiring for a senior fullstack, backend, or platform role with strong product ownership and a realtime or Telegram/TON dimension, I would be glad to connect.
