<h1 align="center">Elves Santos</h1>

<p align="center">
  <b>Full-Stack Software Engineer · Security Researcher · Sistemas / Swift</b>
</p>

<p align="center">
  Engenharia profunda: do backend resiliente ao runtime nativo.<br/>
  <i>Deep engineering: from resilient backends to native runtimes.</i>
</p>

<p align="center">
  <a href="#-português">🇧🇷 Português</a> &nbsp;|&nbsp; <a href="#-english">🇺🇸 English</a>
</p>

<p align="center">
  <a href="mailto:elvesdev@proton.me"><img src="https://img.shields.io/badge/Email-elvesdev@proton.me-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white" alt="Email"/></a>
  <a href="https://linkedin.com/in/sirelves"><img src="https://img.shields.io/badge/LinkedIn-sirelves-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://instagram.com/sir.elves"><img src="https://img.shields.io/badge/Instagram-sir.elves-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
</p>

---

## 🇧🇷 Português

> **Engenheiro de software full-stack que constrói o que a maioria prefere apenas consumir** — de plataformas web e mobile a runtimes nativos de baixo nível.

Sou **Elves Santos**, **Full-Stack Software Engineer** e **Security Researcher** focado em serviços de backend confiáveis, plataformas web sustentáveis e sistemas de produção seguros. Me importo com **arquitetura de longo prazo**, decisões de engenharia claras, confiabilidade operacional e **segurança desde o design**.

Não me contento com a camada superficial — gosto de entender **como as coisas funcionam por dentro**: semântica de linguagens, modelos de layout, concorrência e protocolos de rede. É essa busca por **profundidade técnica** que orienta cada projeto que assino.

### O que eu faço
- Backend com **Java/Spring Boot**, **Node.js** e **.NET**
- Plataformas web com **React**, **Next.js** e **TypeScript**
- Mobile e cross-platform com **React Native**, **Expo**, **Tauri** e **Swift**
- Sistemas data-driven com bancos **SQL e NoSQL**
- Ambientes de produção em **Cloud, VPS e Linux** — CI/CD, monitoramento, automação de deploy e hardening
- **Pesquisa de segurança**: appsec, autenticação/autorização, arquitetura segura e análise de vulnerabilidades

### 🚀 Projetos em destaque

#### 🎓 Agiliza Educa — *produto principal* &nbsp;![Em produção](https://img.shields.io/badge/em%20produção-22C55E?style=flat-square)
Plataforma **full-stack de educação**, arquitetada de ponta a ponta: **web** (Next.js + TypeScript), **backend** (Spring Boot · Java 25) e **mobile** (React Native + Expo 55). Parte do ecossistema **athmos-services**, que inclui ainda um *middleware de borda* de reconhecimento facial (Python) para integração com terminais físicos — validação, sanitização e despacho assíncrono de eventos. Repositórios privados.

#### 🧬 [SwiftDroid](https://github.com/sirelves/SwiftDroid) — *flagship técnico · open source*
**Runtime compatível com SwiftUI para Android, escrito em Swift puro.** Sem transpilação, sem JVM, sem ponte JavaScript: escreva a UI uma vez em Swift e compile **nativamente** para iOS *e* Android (ARM nativo + Jetpack Compose como backend de renderização).

Arquitetura de três camadas — *Core* agnóstico de plataforma (reatividade `@State`/`@Binding`/`@ObservedObject` e protocolo `View`), adaptadores de plataforma e pipeline Android (engine de layout, bridge swift-java, render Compose). Implementa fielmente o modelo *propose/respond* de layout do SwiftUI, preservando a semântica exata da linguagem.

`Swift 6` · `SwiftUI` · `Swift Package Manager` · `Jetpack Compose` — *Phases 0–3 concluídas (Foundation, Reatividade, View Protocol, Layout Engine), 64 testes passando; renderer Android e adapter iOS em andamento.*

#### 🌱 GrowApp — Plataforma de monitoramento agrícola &nbsp;![Em produção](https://img.shields.io/badge/em%20produção-22C55E?style=flat-square)
Plataforma completa de monitoramento de pragas e produção para o agronegócio, arquitetada de ponta a ponta: **mobile** offline-first (Expo / React Native + SQLite com sincronização), **web** (Next.js) e **backend** (Node.js / Express / TypeScript, Prisma + PostgreSQL, Redis + Bull para filas assíncronas).

🔗 [Web](https://app.fgconsultoria.agr.br/) · [Android](https://app.fgconsultoria.agr.br/android) · [iOS](https://app.fgconsultoria.agr.br/ios)

#### 📞 [BoraCall](https://github.com/sirelves/boracall)
App desktop cross-platform de salas de voz: shell **Tauri v2**, backend de signaling em **Rust** (axum + sqlx), **PostgreSQL 16** e **mesh WebRTC P2P** real — o servidor nunca toca no áudio. Auth JWT via subprotocolo WebSocket (menos vazamento de token), Argon2id, auto-updater assinado com ed25519 e CI gerando `.dmg`/`.msi`/`.AppImage`/`.deb`/`.rpm`. Open source (MIT).

#### 🔁 [kompensa](https://github.com/sirelves/kompensa)
Biblioteca de workflow com **saga pattern** para Node.js, browser e React Native: builder tipado, idempotência, retry com backoff, compensação automática, locking distribuído (PostgreSQL advisory locks / Redis) e recuperação de falhas — **zero dependências de runtime**.

#### 🥋 [Comando JJ](https://comandojj.com/) &nbsp;![Em produção](https://img.shields.io/badge/em%20produção-22C55E?style=flat-square)
Projeto **comunitário em produção**: plataforma para um projeto social de Jiu-Jitsu que apoia jovens em situação de vulnerabilidade no interior do Maranhão. **Java 25 · Spring Boot · React Native · PostgreSQL** — engenharia com impacto social, fora do ambiente corporativo tradicional. 🔗 [comandojj.com](https://comandojj.com/)

### 🏆 Destaque
**Vencedor do Hackathon Accesstage 2023** — backend de um chatbot de atendimento ao cliente assistido por IA. [Notícia](https://ipnews.com.br/accesstage-usa-hackathon-para-treinar-estagiarios-e-aprendizes/)

---

## 🇺🇸 English

> **A full-stack engineer who builds what most people only consume** — from web and mobile platforms to low-level native runtimes.

I'm **Elves Santos**, a **Full-Stack Software Engineer** and **Security Researcher** focused on reliable backend services, maintainable web platforms, and secure production systems. I care about **long-term architecture**, clear engineering decisions, operational reliability, and **security by design**.

I'm not satisfied with the surface layer — I want to understand **how things actually work underneath**: language semantics, layout models, concurrency, and network protocols. That drive for **technical depth** shapes every project I put my name on.

### What I do
- Backend with **Java/Spring Boot**, **Node.js**, and **.NET**
- Web platforms with **React**, **Next.js**, and **TypeScript**
- Mobile & cross-platform with **React Native**, **Expo**, **Tauri**, and **Swift**
- Data-driven systems across **SQL and NoSQL** databases
- Production environments on **Cloud, VPS, and Linux** — CI/CD, monitoring, deploy automation, and hardening
- **Security research**: appsec, authentication/authorization, secure architecture, and vulnerability analysis

### 🚀 Featured projects

#### 🎓 Agiliza Educa — *main product* &nbsp;![Live](https://img.shields.io/badge/live-22C55E?style=flat-square)
A **full-stack education platform**, architected end to end: **web** (Next.js + TypeScript), **backend** (Spring Boot · Java 25), and **mobile** (React Native + Expo 55). Part of the **athmos-services** ecosystem, which also includes an *edge middleware* for facial recognition (Python) integrating with physical terminals — validating, sanitizing, and dispatching events asynchronously. Private repositories.

#### 🧬 [SwiftDroid](https://github.com/sirelves/SwiftDroid) — *technical flagship · open source*
**A SwiftUI-compatible runtime for Android, written in pure Swift.** No transpilation, no JVM, no JavaScript bridge: write your UI once in Swift and compile it **natively** to iOS *and* Android (native ARM + Jetpack Compose as the render backend).

A three-tier architecture — a platform-agnostic *Core* (reactivity: `@State`/`@Binding`/`@ObservedObject` and the `View` protocol), platform adapters, and an Android pipeline (layout engine, swift-java bridge, Compose renderer). It faithfully implements SwiftUI's *propose/respond* layout model and preserves exact Swift semantics.

`Swift 6` · `SwiftUI` · `Swift Package Manager` · `Jetpack Compose` — *Phases 0–3 complete (Foundation, Reactivity, View Protocol, Layout Engine), 64 tests passing; Android renderer and iOS adapter in progress.*

#### 🌱 GrowApp — Agricultural monitoring platform &nbsp;![Live](https://img.shields.io/badge/live-22C55E?style=flat-square)
An end-to-end pest and production monitoring platform for agribusiness, architected across every layer: **offline-first mobile** (Expo / React Native + SQLite with sync), **web** (Next.js), and **backend** (Node.js / Express / TypeScript, Prisma + PostgreSQL, Redis + Bull for async queues).

🔗 [Web](https://app.fgconsultoria.agr.br/) · [Android](https://app.fgconsultoria.agr.br/android) · [iOS](https://app.fgconsultoria.agr.br/ios)

#### 📞 [BoraCall](https://github.com/sirelves/boracall)
A cross-platform desktop app for voice rooms: a **Tauri v2** shell, a **Rust** signaling backend (axum + sqlx), **PostgreSQL 16**, and a real **WebRTC P2P mesh** — the server never touches audio. JWT auth over the WebSocket subprotocol (less token leakage), Argon2id, an ed25519-signed auto-updater, and CI producing `.dmg`/`.msi`/`.AppImage`/`.deb`/`.rpm`. Open source (MIT).

#### 🔁 [kompensa](https://github.com/sirelves/kompensa)
A **saga-pattern** workflow library for Node.js, the browser, and React Native: a typed builder, idempotency keys, retry with backoff, automatic compensation, distributed locking (PostgreSQL advisory locks / Redis), and crash recovery — **zero runtime dependencies**.

#### 🥋 [Comando JJ](https://comandojj.com/) &nbsp;![Live](https://img.shields.io/badge/live-22C55E?style=flat-square)
A **community project, live in production**: a platform for a Jiu-Jitsu social project supporting young people in vulnerable situations in the countryside of Maranhão, Brazil. **Java 25 · Spring Boot · React Native · PostgreSQL** — engineering with social impact, outside the traditional corporate environment. 🔗 [comandojj.com](https://comandojj.com/)

### 🏆 Highlight
**Winner — Accesstage Hackathon 2023** — backend for an AI-assisted customer-support chatbot. [Article](https://ipnews.com.br/accesstage-usa-hackathon-para-treinar-estagiarios-e-aprendizes/)

---

## 🧰 Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=for-the-badge&logo=swift&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)

**Databases & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://stats.siasagiliza.net/stats.svg" alt="Dev stats — todas as orgs · all orgs" width="480"/>
</p>

> Card próprio, **auto-hospedado**: estatísticas reais agregando **todas as organizações** (incl. privadas) — algo que os widgets públicos não capturam.<br/>
> <i>Self-hosted custom card: real stats across **all organizations** (incl. private) — which public widgets can't capture.</i>


---

## 📫 Contato · Contact

- ✉️ **Email:** elvesdev@proton.me
- 💼 **LinkedIn:** [in/sirelves](https://linkedin.com/in/sirelves)
- 📸 **Instagram:** [sir.elves](https://instagram.com/sir.elves)

<p align="center"><i>Construindo em profundidade. · Building in depth.</i></p>
