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

<!-- Uncomment once the repo is public:
<a href="https://github.com/sirelves/boracall">
  <img src="https://raw.githubusercontent.com/sirelves/boracall/main/landing-hero.png" alt="BoraCall" width="70%" />
</a>
-->

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

## Highlight

🏆 Winner — **Accesstage Hackathon 2023**  
Backend for an AI-assisted customer support chatbot  
https://ipnews.com.br/accesstage-usa-hackathon-para-treinar-estagiarios-e-aprendizes/

---

## Links

- LinkedIn: https://linkedin.com/in/sirelves  
- Instagram: https://instagram.com/sir.elves
