# Cao Thai Bao — Backend Developer Portfolio 🚀

> **Systems Architecture • Database Concurrency • Multi-Modal AI Integrations**  
> *Final-Year Software Engineering Student at SaiGon University ('26) | IELTS 6.0*

[![GitHub](https://img.shields.io/badge/GitHub-BaotheParo-181717?style=flat-square&logo=github)](https://github.com/BaotheParo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bao_Cao-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/bao-cao-ab8854252/)
[![Email](https://img.shields.io/badge/Email-tanthaibao123%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:tanthaibao123@gmail.com)
[![Status](https://img.shields.io/badge/Status-Available_for_Hire-success?style=flat-square)]()

---

## 🌟 Live Pages & Architecture Overview

This portfolio is built with a **Pastel Aurora Editorial Design System**, featuring frosted glassmorphism, responsive Bento grids, Plus Jakarta Sans & Inter typography, and a synchronized client-side **English / Vietnamese (`EN` | `VI`)** bilingual toggle.

| Page | File | Description |
| :--- | :--- | :--- |
| **1. About Me (Homepage)** | [`index.html`](index.html) | Executive introduction, flagship metrics, engineering principles, and interactive Java concurrency IDE preview. |
| **2. Projects & Case Studies** | [`projects.html`](projects.html) | 3 in-depth systems case studies, C4 architectural specs, interactive category filtering, and architectural decision pillars. |
| **3. Skills & Proof-of-Work** | [`skills.html`](skills.html) | 4 core engineering domains, competency deep-dives, and an interactive 3-tab production code snippet viewer. |
| **4. Interactive Resume / CV** | [`resume.html`](resume.html) | Official LaTeX-synchronized Curriculum Vitae with privacy redaction badges and print-optimized (`@media print`) A4 export. |

---

## 🛠️ Core Tech Stack & Competencies

```
Backend Frameworks     : Java 21, Spring Boot 3.x, Spring Data JPA, Spring Security (JWT), Python (FastAPI), Pydantic v2
Databases & Caching    : PostgreSQL (JSONB), MySQL, Redis (Pub/Sub, Caching, SSE), HikariCP Pool Tuning
Concurrency & Async    : ConcurrentHashMap, CompletableFuture, Spring @Async, Thread-Safe Request Coalescing
Resilience & AI        : Resilience4j Circuit Breakers, Fallback Routing, Google Gemini 2.5 Flash, Groq Whisper
DevOps & Governance    : Docker, Docker Compose, GitHub Actions (CI/CD), Linux CLI, JUnit 5, Mockito, OpenAPI 3.1
```

---

## 🚀 Featured Engineering Systems

### 1. IELTS Automated Evaluation Engine (ENGONOW EdTech)
- **Role:** Backend Engineer Intern (Jun 2026 – Aug 2026)
- **Stack:** Java 21, Spring Boot 3.x, FastAPI, Redis Pub/Sub, SSE, Gemini 2.5 Flash, Groq Whisper-large-v3, Docker.
- **Key Metrics:**
  - **-85% Polling Traffic:** Real-time test progress delivered via Redis Pub/Sub and Server-Sent Events (SSE).
  - **Zero Score Drift:** Enforced deterministic Cambridge half-band score rounding via high-precision `BigDecimal`.
  - **Circuit Breaker Resilience:** Fault-tolerant AI router with automatic fallback for API rate limits and network degradation.

### 2. Street Voice Backend Platform
- **Repo:** [github.com/doanhdai/street-voice-backend](https://github.com/doanhdai/street-voice-backend.git)
- **Stack:** Spring Boot 3.x, Java 21, Python, PostgreSQL, Docker.
- **Key Metrics:**
  - **+300% Throughput Boost:** Offloaded heavy text transformations to worker threads via Spring `@Async`.
  - **12ms Median Latency:** In-flight request deduplication via thread-safe `RequestCoalescingService` using `ConcurrentHashMap` and `CompletableFuture`.

### 3. University Admission System (Hệ Thống Tuyển Sinh Đại Học)
- **Repo:** [github.com/BaotheParo/app-tuyensinh](https://github.com/BaotheParo/app-tuyensinh.git)
- **Stack:** Spring Boot, Java, MySQL, HikariCP, In-Memory Caching.
- **Key Metrics:**
  - **Zero Deadlocks:** Handled 50,000+ candidate batches by enforcing deterministic lexicographical record ordering before batch writes via `JdbcTemplate.batchUpdate()`.
  - **<500ms Total Runtime:** Replaced N+1 query loops with O(1) in-memory indexed cache lookups.

---

## 📦 How to Push and Deploy to GitHub Pages

### 1. Initialize Git and Push to Remote
```bash
# 1. Initialize git repository if not already done
git init

# 2. Add all files
git add .

# 3. Commit changes
git commit -m "feat: complete Cao Thai Bao engineering portfolio with bilingual EN/VI toggle"

# 4. Set main branch
git branch -M main

# 5. Add remote origin
git remote add origin https://github.com/BaotheParo/caothaibao.git

# 6. Push to GitHub
git push -u origin main --force
```

### 2. Enable GitHub Pages
1. Go to your repository on GitHub: `https://github.com/BaotheParo/caothaibao/settings/pages`
2. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
3. Under **Branch**, select `main` and folder `/ (root)`.
4. Click **Save**.
5. Your portfolio will be live at: `https://baotheparo.github.io/caothaibao/`

---

## 📬 Contact & Recruiter Outreach

- **Developer:** Cao Thai Bao
- **Email:** [tanthaibao123@gmail.com](mailto:tanthaibao123@gmail.com)
- **Location:** Ho Chi Minh City, Vietnam
- **LinkedIn:** [linkedin.com/in/bao-cao-ab8854252](https://www.linkedin.com/in/bao-cao-ab8854252/)
- **GitHub:** [github.com/BaotheParo](https://github.com/BaotheParo)

---
*© 2026 Cao Thai Bao. Built with precision, resilience, and clean architecture.*
