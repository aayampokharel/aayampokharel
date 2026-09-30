<h1 align="center">Hi, I'm Aayam Pokharel 👋</h1>

<p align="center">
  <b>Backend Engineer · Go · PostgreSQL · Distributed Systems</b><br/>
  Kathmandu, Nepal 🇳🇵
</p>

<p align="center">
  <a href="https://safaltopper.com"><img src="https://img.shields.io/badge/Live-SafalTopper-2ea44f?style=for-the-badge" alt="SafalTopper"/></a>
  <a href="https://aayampokharel.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-visit-blue?style=for-the-badge" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/aayam-pokharel-434ba6205/"><img src="https://img.shields.io/badge/LinkedIn-connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:aayam.pokharel@gmail.com"><img src="https://img.shields.io/badge/Email-write%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 👨‍💻 About me

I'm a backend engineer who writes Go for a living and for fun. I've spent **1+ years building production backends** (REST APIs, caching, query optimization, Docker/CI-CD), and outside work I build and ship my own systems: a live EdTech platform, a Byzantine-fault-tolerant blockchain written from scratch, and real-time multiplayer backends.

- 🔭 Interested in **concurrency, distributed systems, consensus, and real-time systems**
- 🌱 Currently deepening: **system design, gRPC, and observability**
- 🎓 BSc CSIT graduate, St. Xavier's College
- 💬 Ask me about: Go, clean architecture, PostgreSQL, WebSockets, deploying on a VPS

---

## 🛠️ Tech I use

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=go,postgres,mysql,redis,docker,githubactions,linux,nginx,bash,git&perline=10" alt="backend stack"/>

**Also**
<br/>
<img src="https://skillicons.dev/icons?i=python,dart,flutter,html,css&perline=10" alt="other stack"/>

`Gin` · `Huma (OpenAPI)` · `GORM` · `gRPC / Protobuf` · `WebSockets` · `JWT / OAuth2` · `Zap` · `Atlas migrations` · `Dokploy` · `Hetzner Cloud`

---

## 🚀 Featured projects

### 🎓 [SafalTopper](https://safaltopper.com) — live EdTech platform
`Go` `Gin` `Huma` `GORM` `PostgreSQL` `JWT` `Google OAuth2` `Docker` `GitHub Actions` `Dokploy` `Hetzner`

Entrance-exam preparation platform for BSc CSIT aspirants, running in production.
- Typed, auto-validated REST APIs with OpenAPI docs (Gin + Huma)
- Stateless auth with JWT and Google OAuth2
- Clean Architecture: domain logic decoupled from GORM and the delivery layer
- Structured logging (Zap) and custom middleware
- CI/CD with Docker + GitHub Actions, deployed on Hetzner via Dokploy

### ⛓️ [DocSniff](https://github.com/aayampokharel/fyp_backend) — academic certificate blockchain
`Go` `PostgreSQL` `TCP` `PBFT` `PoW` `RSA` `SHA-256` `Flutter` `Python`

A private, permissioned consortium blockchain for issuing and verifying academic certificates, built from scratch (my final-year project).
- Hybrid **simplified PoW + PBFT** consensus (Pre-Prepare → Prepare → Commit → Execute); a 4-node network tolerates 1 Byzantine node
- Custom **raw-TCP peer-to-peer** layer for block propagation and consensus messages
- RSA-signed consensus messages; **SHA-256 Merkle trees** with inclusion proofs
- PostgreSQL persistence (8 normalized tables), Go reverse proxy for public QR-code verification
- Python background-removal step (called from Go) for institution logos and signatures
- Frontend: [Flutter dashboard](https://github.com/aayampokharel/fyp_frontend)

---

## 📁 All projects

### Go / backend
| Project | What it is | Stack |
|---|---|---|
| [fyp_backend](https://github.com/aayampokharel/fyp_backend) | DocSniff blockchain core | Go, PostgreSQL, TCP |
| [gartic_backend](https://github.com/aayampokharel/gartic_backend) | Real-time multiplayer drawing game server: rooms, turn rotation, timers, word selection, spectators | Go, WebSockets |
| [SE_drive_backend](https://github.com/aayampokharel/SE_drive_backend) | Cloud storage backend: multipart upload/download, FFmpeg media pipeline | Go, MySQL, FFmpeg |
| [messenger](https://github.com/aayampokharel/messenger) | Real-time chat app with Go backend | Go, WebSockets, MySQL, Flutter |

### Flutter / mobile
| Project | What it is | Stack |
|---|---|---|
| [fyp_frontend](https://github.com/aayampokharel/fyp_frontend) | DocSniff admin and institution dashboard | Flutter Web |
| [gartic_frontend](https://github.com/aayampokharel/gartic_frontend) | Client for the drawing game | Flutter |
| [bat_app](https://github.com/aayampokharel/bat_app) | Cricket bat catalogue with search, filters, wishlist | Flutter |
| [todo_list](https://github.com/aayampokharel/todo_list) | To-do app with MySQL sync and in-memory state | Flutter, MySQL |

---

## 💼 Experience

**Backend Developer (Go)** · AsterGaze Technologies · May 2025 – 2026
- Built modular services with Feature-First Clean Architecture
- Shipped REST APIs with Gin + Huma (typed, OpenAPI-compliant)
- Removed N+1 queries in GORM using targeted preloading
- Added a Redis cache-aside layer to cut database read load
- Containerized services with Docker and supported automated deployments

---

## 📊 GitHub stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=aayampokharel&hide_border=true" alt="GitHub streak"/>
</p>
<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=aayampokharel&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aayampokharel&layout=compact&hide_border=true" alt="Top languages"/>
</p>

---

## 🤝 Let's talk

Open to backend / Go roles and interesting collaborations. Best way to reach me is **[aayam.pokharel@gmail.com](mailto:aayam.pokharel@gmail.com)**.

<p align="center"><i>Building backend systems, one goroutine at a time.</i></p>
