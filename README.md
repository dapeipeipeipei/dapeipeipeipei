## Wenshuo Pei

**Computer Science (Honours Co-op), Concordia University — BSc expected April 2027.** Montreal, Canada.

I build full-stack systems and applied-ML pipelines, and I spend most of my attention on the seam between
them: getting a model's output to survive contact with real sensors, real users, and a real latency budget.

**Currently** — Software Developer Intern at **HAW Landshut** (Germany), working on *FrostWatch*: a geospatial
frost-risk monitoring module for a Chilean orchard prediction platform. Four heterogeneous data sources
(physical sensor stations, OpenWeatherMap, third-party forecasts, an in-house XGBoost + PCA model) reconciled
over AWS AppSync into a live Leaflet map covering 30+ weather stations.

**Also** — Full-Stack Developer & LLM Research Assistant at **Concordia University** (NSERC USRA / Mitacs),
building an AI travel-planning platform and the evaluation tooling around its LLM itinerary pipeline.

---

### Open to

`2027 New Grad SWE` · `Summer 2027 Internship` · `Winter 2027 Co-op` — Canada, United States, or remote.
Canadian PR, no sponsorship required in Canada. Strongest interest in **applied ML / LLM systems** and
**backend + data infrastructure**.

---

### Public repositories

| Repository | What it is | Stack |
| --- | --- | --- |
| **[EatWhat](https://github.com/dapeipeipeipei/EatWhat)** · [live](https://eat-what-rho.vercel.app) | Full-stack nutrition and fitness planner — meal plans, recipe library, pantry and shopping state, activity logging, statistics, and an LLM assistant over the user's own history. Installable PWA. | Next.js 15, React 19, TypeScript, Prisma 7, PostgreSQL, Supabase Realtime, NextAuth, OpenAI, Tailwind |
| **[schengen-slot-sentinel](https://github.com/dapeipeipeipei/schengen-slot-sentinel)** | Headless watcher for German consulate Schengen appointment slots, with Telegram alerting and an optional guarded auto-booking path. Adversarial tests around the booking flow, because the failure mode here is booking the wrong thing. | Python, Playwright, Telegram Bot API |

Most of my largest systems are university research IP or client work and are not open-sourceable. Those are
summarized below, and written up in more depth in my portfolio.

---

### Work I can't open-source

- **FrostWatch** — geospatial frost-risk map, shipped as an additive React 18 / TypeScript route with zero
  backend schema changes, merged to production through peer-reviewed PRs. Diagnostics engine cross-validates
  the four sources to surface sensor faults, stale data, and micro-climate cold-air pooling that coarse grid
  models miss. 39 unit tests, 5-minute auto-refresh.
- **AI travel-planning platform** — React / Node.js / Flask / PostgreSQL, 1,000+ concurrent users over
  WebSocket; LLM itinerary pipeline serving 500+ daily requests with a 40% inference-latency reduction.
  Fine-tuned transformers on 50,000+ structured reasoning examples; LoRA vs. prefix-tuning comparison, plus
  evaluation workflows for consistency scoring and hallucination detection.
- **Travel-domain RAG pipeline** — chunking, embedding, and ranking ablations that cut irrelevant retrievals
  by 35%.

---

### Technical focus

**Languages** — Python, TypeScript / JavaScript, C / C++, Java, SQL
**ML** — PyTorch, scikit-learn, XGBoost, LLM fine-tuning (LoRA, prefix-tuning), RAG, evaluation and benchmarking
**Web** — React, React Native, Next.js, Node.js, Flask, GraphQL, REST, WebSocket
**Infrastructure** — AWS (Amplify, AppSync, Lambda, DynamoDB, S3), Docker, CI/CD, PostgreSQL, MongoDB, Supabase

---

### Contact

[peiwenshuo@gmail.com](mailto:peiwenshuo@gmail.com) · [LinkedIn](https://www.linkedin.com/in/wenshuo-pei-24890321a/)
