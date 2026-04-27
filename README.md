Full-Stack Software Engineer focused on building reliable backend services
and maintainable web platforms.

I prioritize long-term architecture, clarity and production-quality delivery.

---

## What I do

- Backend development (Node.js, .NET, Java/Spring)
- Web applications with React, Next.js and TypeScript
- Database-driven systems (SQL and NoSQL)
- Cloud and infrastructure fundamentals (AWS, VPS environments)

---

## Stack

**Backend:** Node.js · C#/.NET · Java/Spring · Python  
**Frontend:** React · Next.js · TypeScript  
**Databases:** PostgreSQL · SQL Server · MongoDB · DynamoDB  
**Cloud:** AWS · GCP · Azure

---

## Featured project — BoraCall

Cross-platform desktop app for voice rooms. Tauri v2 shell, Rust signaling
backend, Postgres 16, and a real WebRTC P2P mesh — the server never touches
audio. Open source under MIT.

<a href="https://github.com/sirelves/boracall">
  <img src="https://raw.githubusercontent.com/sirelves/boracall/main/landing-hero.png" alt="BoraCall" width="70%" />
</a>

**Stack:** Rust (axum 0.8, sqlx, jemalloc) · Tauri v2 · Postgres 16 · WebRTC · React 18 (no build step)

**Engineering highlights:**
- Rust backend with sqlx compile-time checked queries and `tokio::sync::broadcast` per-room signaling hub
- JWT authentication via `Sec-WebSocket-Protocol` subprotocol — never via query string (prevents token leakage in logs, history, referers)
- Deterministic WebRTC glare avoidance (lexicographic `user_id` decides who creates the offer)
- Argon2id password hashing, ed25519-signed auto-updater
- CI/CD pipeline producing `.dmg` (ARM + Intel), `.msi`, `.AppImage`, `.deb`, `.rpm` from 4 parallel runners
- Zero build step on the frontend — React 18 + Babel standalone, vendored fonts

Around 4.4k LOC. Documentation covers [architecture with sequence diagrams](https://github.com/sirelves/boracall/blob/main/ARCHITECTURE.md) and a [deployment handoff](https://github.com/sirelves/boracall/blob/main/HANDOFF.md) for VPS production (systemd, nginx, TURN, backups).

→ [github.com/sirelves/boracall](https://github.com/sirelves/boracall)

---

## Featured project — kompensa

Saga pattern workflow library for Node.js, the browser and React Native.
Typed builder, idempotency keys, retry with exponential backoff, automatic
compensation on failure, distributed locking (Postgres / Redis) and crash
recovery — with **zero runtime dependencies**.

<a href="https://github.com/sirelves/kompensa">
  <img src="https://raw.githubusercontent.com/sirelves/kompensa/main/.github/assets/social-preview.png" alt="kompensa" width="70%" />
</a>

**Stack:** TypeScript · Node.js 18+ · ESM + CJS · `pg` advisory locks · `ioredis` Redlock-style · `vitest` · `tsup`

**Engineering highlights:**
- In-process, lightweight alternative to Temporal / Step Functions — saga semantics without the worker fleet
- Typed result accumulation — `ctx.results.<step>.<field>` is statically typed across the chain via inference, no codegen
- Distributed lock protocol on top of `pg_try_advisory_lock` (auto-release on connection close — crash-safe) and Redis `SET NX PX` with Lua-verified token release
- Crash recovery: every step transition is persisted; the next invocation with the same `idempotencyKey` resumes from the last successful step
- Zero runtime dependencies, ~20 KB minzipped, separate bundler entries per storage adapter so `pg` / `ioredis` are loaded only when used
- 73 tests in CI (50 unit + 23 integration against real Postgres 17 and Redis 7) — covers concurrency, `pg_terminate_backend` mid-flow, lock TTL expiry, token-safe release, resume-after-crash
- Ships with `llms.txt` / `llms-full.txt` / `AGENTS.md` so AI assistants and coding agents can recommend it accurately

[npm](https://www.npmjs.com/package/kompensa) · [docs](https://github.com/sirelves/kompensa/tree/main/docs) · [comparison vs Temporal / Step Functions / BullMQ](https://github.com/sirelves/kompensa/blob/main/docs/comparison.md)

→ [github.com/sirelves/kompensa](https://github.com/sirelves/kompensa)

---

## Highlight

🏆 Winner — **Accesstage Hackathon 2023**  
Backend for an AI-assisted customer support chatbot  
https://ipnews.com.br/accesstage-usa-hackathon-para-treinar-estagiarios-e-aprendizes/

---

## Links

- LinkedIn: https://linkedin.com/in/sirelves  
- Instagram: https://instagram.com/sir.elves
