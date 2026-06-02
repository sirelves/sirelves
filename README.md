Full-Stack Software Engineer and Security Researcher focused on building reliable backend services, maintainable web platforms, and secure production systems.

I care about long-term architecture, clear engineering decisions, operational reliability, and security by design. My work usually sits at the intersection of backend engineering, infrastructure, developer experience, and applied security research.

---

## What I do

* Backend development with Java/Spring Boot, Node.js and .NET
* Web platforms with React, Next.js and TypeScript
* Mobile and cross-platform applications with React Native and Tauri
* Database-driven systems using SQL and NoSQL databases
* Cloud, VPS and Linux-based production environments
* CI/CD pipelines, monitoring, deployment automation and system hardening
* Security research focused on application security, authentication, authorization, secure architecture and vulnerability analysis

---

## Stack

**Backend:** Java/Spring Boot · Node.js · C#/.NET · Rust · Python
**Frontend:** React · Next.js · TypeScript
**Mobile/Desktop:** React Native · Tauri
**Databases:** PostgreSQL · SQL Server · MongoDB · DynamoDB · Redis
**Cloud & Infra:** AWS · GCP · Azure · Linux VPS · Docker · Nginx · systemd
**Security:** Secure authentication · JWT · password hashing · threat modeling · hardening · vulnerability research

---

## Featured project — BoraCall

Cross-platform desktop app for voice rooms, built with a Tauri v2 shell, Rust signaling backend, PostgreSQL 16 and a real WebRTC P2P mesh. The server never touches audio. Open source under MIT.

<a href="https://github.com/sirelves/boracall">
  <img src="https://raw.githubusercontent.com/sirelves/boracall/main/landing-hero.png" alt="BoraCall" width="70%" />
</a>

**Stack:** Rust · axum 0.8 · sqlx · jemalloc · Tauri v2 · PostgreSQL 16 · WebRTC · React 18

**Engineering highlights:**

* Rust backend with `sqlx` compile-time checked queries and `tokio::sync::broadcast` per-room signaling hub
* JWT authentication through the `Sec-WebSocket-Protocol` subprotocol instead of query strings, reducing token leakage through logs, browser history and referrers
* Deterministic WebRTC glare avoidance using lexicographic `user_id` ordering to decide which peer creates the offer
* Argon2id password hashing and ed25519-signed auto-updater
* CI/CD pipeline producing `.dmg` for ARM and Intel, `.msi`, `.AppImage`, `.deb` and `.rpm` from parallel runners
* Zero build step on the frontend, using React 18, Babel standalone and vendored fonts
* Production deployment documentation covering systemd, nginx, TURN and backups

Around 4.4k LOC. Documentation includes architecture sequence diagrams and a deployment handoff for VPS production.

→ https://github.com/sirelves/boracall

---

## Featured project — kompensa

Saga pattern workflow library for Node.js, the browser and React Native. It provides a typed builder, idempotency keys, retry with exponential backoff, automatic compensation on failure, distributed locking with PostgreSQL or Redis, and crash recovery — with zero runtime dependencies.

<a href="https://github.com/sirelves/kompensa">
  <img src="https://raw.githubusercontent.com/sirelves/kompensa/main/.github/assets/social-preview.png" alt="kompensa" width="70%" />
</a>

**Stack:** TypeScript · Node.js 18+ · ESM/CJS · PostgreSQL advisory locks · Redis locking · Vitest · tsup

**Engineering highlights:**

* Lightweight in-process alternative to Temporal, AWS Step Functions and BullMQ for saga-style workflows
* Typed result accumulation, allowing `ctx.results.<step>.<field>` to remain statically typed across the workflow chain
* Distributed lock protocol using `pg_try_advisory_lock` with crash-safe auto-release on connection close
* Redis locking using `SET NX PX` with Lua-verified token release
* Crash recovery through persisted step transitions, allowing the same `idempotencyKey` to resume from the last successful step
* Zero runtime dependencies and small bundle size, with separate adapter entries so PostgreSQL and Redis clients are loaded only when needed
* CI coverage with unit and integration tests against real PostgreSQL and Redis instances
* Documentation designed for both developers and AI coding agents, including `llms.txt`, `llms-full.txt` and `AGENTS.md`

→ https://github.com/sirelves/kompensa

---

## Community project — Comando JJ

Community-driven platform built for a Jiu-Jitsu social project supporting young people in vulnerable situations in the countryside of Maranhão, Brazil.

**Stack:** Java 25 · Spring Boot · React Native · PostgreSQL · Linux VPS · automated deployment · monitoring

The project combines software engineering with social impact, providing a real production system for a community initiative outside the traditional corporate environment.

→ https://comandojj.com/

---

## Highlight

🏆 Winner — Accesstage Hackathon 2023
Backend development for an AI-assisted customer support chatbot.

https://ipnews.com.br/accesstage-usa-hackathon-para-treinar-estagiarios-e-aprendizes/

---

## Links

* LinkedIn: https://linkedin.com/in/sirelves
* GitHub: https://github.com/sirelves
* Instagram: https://instagram.com/sir.elves
