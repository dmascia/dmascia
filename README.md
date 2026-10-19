# 👋 Hi, I'm David Mascia

## Staff Software Development Engineer · Full-Stack · Web · Mobile · AI Platforms

📍 New Jersey, USA (Remote)  
🔗 [LinkedIn](https://www.linkedin.com/in/davidmascia)  
💻 [GitHub](https://github.com/dmascia)  
✍️ [Tech Blog](https://techwithbigd.medium.com)  

---

## 🚀 About Me

I'm a **Staff Software Development Engineer** with **20 years** across web, mobile, and backend. I own architecture end to end on systems serving **1M+ daily users** and **$250M/yr**, and I build the systems behind them: distributed services, native and cross-platform mobile, and HIPAA-compliant generative-AI agents on AWS Bedrock. I work as an individual contributor.

At **Equip Health** I took **MyEquip**, Equip's HIPAA-compliant patient app, from beta to **~4,000 daily sessions** at **99.95% crash-free**, cut code-review turnaround to **under a day** with an AI code-review assistant, and drive agentic AI-assisted development now used across the **~40-engineer org**.

**What I bring**
- **Full-stack architecture:** web, mobile, and backend across healthcare, fintech, and media
- **AI agents:** LLM and agentic systems on AWS Bedrock (AgentCore, Guardrails, Strands Agents SDK)
- **Scale and reliability:** 1M+ users, CDN/edge caching, Redis and read replicas, RUM, load testing
- **Native mobile depth:** React Native, Expo, and Kotlin Turbo Modules on the New Architecture

Open to **Staff / Senior Software Development Engineer** roles.

---

## 📊 Impact & Scale

**Equip Health · Staff Software Development Engineer, Patient Experience (2026)**
- Scaled **MyEquip** (HIPAA-compliant, PHI-handling; iOS, Android, web) from beta to **~4,000 daily sessions** (Mixpanel) at **99.95% crash-free**, zero app freezes, and fast loads on **92.7% of web visits** (Datadog RUM)
- Cut code-review turnaround from **~3 days to under a day** (~57% merged same day) with an AI code-review assistant plus delivery tracking and engineering metrics
- Sped up the delivery cycle **~2x** and cut idea-to-build-ready planning from months to weeks by driving agentic AI-assisted development (Claude Code, GitHub Copilot) across the ~40-engineer org

**Across my career**
- Architected the e-commerce marketplace behind **$250M/yr** in gross revenue
- Scaled a Next.js live-streaming platform to **1M+ daily users**
- Delivered **300+ partner integrations** adding **$5M+/yr**
- Shipped React Native apps that drove **$1M in first-season sales** and lifted watch time **40%** and retention **70%**

---

## 🏆 Career Highlights

### Healthcare AI · HYGIA Health Services
- Architected a greenfield, HIPAA-compliant conversational-AI telehealth platform as an embedded Android app, which helped secure **$1M** in institutional funding
- Built **GIA**, a custom LLM assistant, on the **Strands Agents SDK** and **Amazon Bedrock AgentCore** with Bedrock Guardrails and PHI data policies
- Replaced slow third-party speech-to-text with a custom **Kotlin Turbo Module** (React Native New Architecture, JSI/Codegen), cutting partial-result latency to **~25ms**

### FinTech · Blue Core Capital
- Built a React AI advisor (LLM decision engine on **AWS Bedrock**) serving **~3K customer sessions/week** and lifting conversion **32%**
- Hardened the Bedrock agent backend for production: per-user session isolation, explicit session lifecycle on AWS SDK v3, IAM-role credentials with no hard-coded secrets

### Media / Streaming · Volume
- Scaled a Next.js platform to **1M+ daily users** with SSG/ISR behind a CDN edge cache, Redis and read replicas, and autoscaling GraphQL APIs on serverless functions and microservices
- Increased watch time **40%** and retention **70%** with the company's first React Native app (WebRTC, WebSockets)

### eCommerce · CardCash (acquired by RDE, Inc.)
- Architected the core marketplace behind **$250M/yr** in gross revenue and a **35% YoY** retention gain, plus **300+** white-label partner integrations adding **$5M+/yr**
- Delivered the Checkout MVP behind a **$16M** funding round, then shipped the company's first React Native app to **$1M** in first-season sales

---

## 🛠️ Technology Stack

```text
Languages
└── TypeScript · JavaScript · Python · Java · Kotlin · SQL

Frontend & Mobile
├── React · Next.js (SSG/ISR) · React Native · Expo
├── Turbo Modules (New Architecture, JSI/Codegen) · Redux/RTK
└── Jest/RTL · TDD · HLS live streaming · WebRTC

Backend & Data
├── Node.js · Python/Django · Java/Spring Boot
├── REST & GraphQL APIs · WebSockets · Server-Sent Events
├── distributed systems · event-driven architecture · microservices
└── PostgreSQL · DynamoDB · Redis · RabbitMQ

Cloud & Infra
├── AWS (Bedrock, Lambda, API Gateway) · AWS SDK v3 · GCP
├── Docker · Kubernetes · Terraform · CDN/edge caching
└── GitHub Actions CI/CD · Nx monorepos · Datadog RUM · k6 · feature flags

AI & Compliance
├── Agentic AI · Conversational AI · LLM application architecture
├── AWS Bedrock (Agents, AgentCore, Guardrails) · Strands Agents SDK
└── Claude Code · GitHub Copilot · HIPAA · PHI
```

---

## 🧩 Open Source

- **[aws-bedrock-agentcore-runtime-example](https://github.com/dmascia/aws-bedrock-agentcore-runtime-example)** — production AWS Bedrock AgentCore Runtime reference: typed session lifecycle on AWS SDK v3, IAM-based auth, session isolation
- **[aws-bedrock-agentcore-postman](https://github.com/dmascia/aws-bedrock-agentcore-postman)** — SigV4-signed Postman collection to invoke and debug AgentCore runtimes with dynamic, PII-free sessions
- **[react-native-use-tts](https://github.com/dmascia/react-native-use-tts)** — React Native speech-to-text via a Kotlin Turbo Module (New Architecture, JSI/Codegen) at ~25ms partial latency
