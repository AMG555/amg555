<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!--           AMAL GEORGE (AMG555) — PROFILE README            -->
<!-- ═══════════════════════════════════════════════════════════ -->

<a href="https://github.com/AMG555">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=2600&pause=1100&color=38BDF8&center=true&vCenter=true&width=760&lines=Amal+George+%C2%B7+Product+Engineer;AI-Native+Builder+%C2%B7+Full-Stack+%2F+Systems;Architecture+%E2%86%92+Infrastructure+%E2%86%92+Deployment;SaaS+%C2%B7+Multi-Tenant+Systems+%C2%B7+Rust+%C2%B7+Edge+AI" alt="Typing SVG Banner" />
</a>

<p align="center">
  <b>Product Engineer · AI-Native Builder · Full-Stack / Systems</b><br>
  <sub>Independent Builder · Systems & SaaS Architecture</sub>
</p>

<p align="center">
  <i>"I architect and ship products end-to-end — bridging system design, distributed data isolation, and resilient backend infrastructure into high-polish user software."</i>
</p>

<p align="center">
  <a href="https://github.com/AMG555"><img src="https://img.shields.io/badge/Status-Actively_Building_Products-10b981?style=flat-square&logo=git&logoColor=white" alt="Status" /></a>
  <a href="#-01-dormico--production-multi-tenant-hostel-management-saas"><img src="https://img.shields.io/badge/Flagship-Dormico.in-f59e0b?style=flat-square&logo=google-chrome&logoColor=white" alt="Dormico Flagship" /></a>
  <a href="https://github.com/AMG555/VoxForge"><img src="https://img.shields.io/badge/Systems-VoxForge_(Rust)-orange?style=flat-square&logo=rust&logoColor=white" alt="VoxForge Rust" /></a>
  <a href="https://github.com/amg555/smart-dustbin"><img src="https://img.shields.io/badge/Edge_AI-Smart_Bin-blue?style=flat-square&logo=raspberrypi&logoColor=white" alt="Smart Bin" /></a>
  <a href="mailto:amgt503@gmail.com"><img src="https://img.shields.io/badge/Signal-Open_To_Engineering_Roles-a855f7?style=flat-square" alt="Open To Roles" /></a>
</p>

</div>

---

### ◈ What I Build

<table width="100%">
<tr>
<td width="50%" valign="top">

`🏢 MULTI-TENANT SAAS & PLATFORMS`  
**Data Isolation · Billing Workflows · Reconciliation**  
Production systems built around strict tenant boundaries (PostgreSQL RLS), automated recurring payment lifecycles, UPI AutoPay / e-mandate integration, and operational state machines.

</td>
<td width="50%" valign="top">

`⚙️ SYSTEMS & PIPELINE RUNTIMES`  
**Rust Workspaces · DAG Runners · Hardware Auto-Dispatch**  
Modular, low-latency runtimes, directed acyclic graph (DAG) task execution, SIMD / GPU accelerator detection, and standards-compliant API surfaces.

</td>
</tr>
<tr>
<td width="50%" valign="top">

`🤖 EDGE AI & HARDWARE INTEGRATION`  
**Computer Vision · Embedded Linux · Physical Sorting**  
Real-time object detection on edge devices (YOLO + Raspberry Pi), electromechanical actuation, sensor telemetry, and offline-first edge compute loops.

</td>
<td width="50%" valign="top">

`⚡ AI-NATIVE EXECUTION`  
**Augmented Velocity · Human Architectural Ownership**  
Leveraging intelligent agentic workflows to accelerate exploratory prototyping and eliminate repetitive code, while maintaining rigorous human judgment on boundaries, security, and schema invariants.

</td>
</tr>
</table>

---

### ◈ Selected Work

Depth over breadth. Three projects demonstrating product delivery, systems engineering, and hardware-software integration.

<br/>

<!-- ── PROJECT 1: DORMICO (FLAGSHIP) ── -->

<table width="100%">
<tr>
<td colspan="2">
  <div align="left">
    <h3>✦ 01. Dormico — Production Multi-Tenant Hostel Management SaaS</h3>
  </div>
  <p><b>Commercial multi-tenant platform automating end-to-end hostel operations, occupancy tracking, and recurring financial reconciliation. Independently architected, developed, and deployed to production.</b></p>
  <div>
    <a href="https://dormico.in"><img src="https://img.shields.io/badge/Deployment-Live_Production-10b981?style=flat-square&logo=vercel&logoColor=white" alt="Live Production" /></a>
    <img src="https://img.shields.io/badge/Traction-35%2B_Registered_Users-38bdf8?style=flat-square" alt="35+ Registered Users" />
    <img src="https://img.shields.io/badge/Platform-Web_%2B_Android-f59e0b?style=flat-square&logo=android&logoColor=white" alt="Web and Android" />
    <img src="https://img.shields.io/badge/Source-Private_(Commercial)-475569?style=flat-square" alt="Commercial Source" />
  </div>
</td>
</tr>
<tr>
<td width="55%" valign="top">

<h4>Architecture & Capabilities</h4>

- **Multi-Tenant Boundary Isolation:** Database-level isolation built on Supabase PostgreSQL with strict Row-Level Security (RLS) policies, guaranteeing ironclad data separation across tenant contexts.
- **Automated Billing & Reconciliation:** Recurring billing pipeline integrated with UPI AutoPay (e-mandates), handling automated invoicing, payment state transitions, and reconciliation.
- **Dynamic Operations & Pricing:** Operational state machine tracking rooms, beds, resident onboarding/offboarding lifecycles, and occupancy-based dynamic rate adjustments.
- **Full-Stack Delivery:** Production Next.js web application paired with a cross-platform React Native Android mobile client.

```
Next.js Web & React Native App
      │ HTTPS / JWT Auth
      ▼
┌──────────────────────────────────────────┐
│            DORMICO ECOSYSTEM             │
│  ┌────────────────────────────────────┐  │
│  │ Supabase PostgreSQL + RLS Policies │  │
│  │ (Strict Multi-Tenant Isolation)    │  │
│  └───────┬────────────────────┬───────┘  │
│          ▼                    ▼          │
│  ┌───────────────┐    ┌───────────────┐  │
│  │ UPI AutoPay   │    │  Dynamic Bed  │  │
│  │ Mandate Engine│    │ State Machine │  │
│  └───────────────┘    └───────────────┘  │
└──────────────────────────────────────────┘
```

</td>
<td width="45%" valign="top">

<h4>Technical Profile</h4>

- **Web Interface:** Next.js, React, Tailwind CSS
- **Mobile Client:** React Native / Expo (Android)
- **Data & Auth:** PostgreSQL, Supabase (RLS), Supabase Auth
- **Payments:** UPI AutoPay, Mandate Workflows, Webhook Handlers
- **State & Cloud:** REST APIs, Cloud Functions, Edge CDN

<br/>

<div align="center">
  <a href="https://dormico.in"><b>🔗 Explore Live Platform (dormico.in) →</b></a>
</div>

</td>
</tr>
</table>

<br/>

<!-- ── PROJECT 2 & 3: VOXFORGE & SMART BIN ── -->

<table width="100%">
<tr>
<td width="50%" valign="top">

<h3>✦ 02. VoxForge</h3>
<b>Self-Hostable Multi-Engine TTS Platform</b>

<p>
  <a href="https://github.com/AMG555/VoxForge"><img src="https://img.shields.io/badge/Status-Feature_Complete_v0.2.0_Beta-blue.svg" alt="Pre-v1.0 Status" /></a
  <a href="https://github.com/AMG555/VoxForge"><img src="https://img.shields.io/badge/Repo-AMG555%2FVoxForge-blue?style=flat-square&logo=github&logoColor=white" alt="VoxForge Repo" /></a>
</p>

Modular speech synthesis server and visual workflow runner. Unifies 10+ local and cloud speech engines behind a single Rust core with zero-latency streaming.

- **Modular Rust Workspace:** Decoupled crates (`voxforge-api`, `voxforge-hardware`, `voxforge-pipeline`, `voxforge-cli`) powered by Axum.
- **Hardware-Aware Adaptive Dispatch:** Auto-detects CPU vector extensions (AVX2, AVX-512, NEON) and GPU acceleration (CUDA, Apple MPS, DirectML) to dynamically allocate optimal engine models.
- **DAG Pipeline Runner:** Node-based directed acyclic graph builder to chain multi-speaker audio graphs, prosody controls, and pause markers.
- **Tri-Tier Storage:** Zero-dependency SQLite (WAL mode) for desktop, PostgreSQL for Docker self-hosting, and Supabase RLS for multi-tenant deployments.
- **API & Security:** OpenAI-compatible `/v1/audio/speech` endpoint, token-bucket rate limiting, and granular scope permissions (`tts:read`, `tts:write`, `pipeline:admin`).

```
Client App (Web / OpenAI SDK)
      │ HTTP / WebSocket
      ▼
┌──────────────────────────────────────────┐
│             VOXFORGE DAEMON              │
│  ┌────────────────┐  ┌─────────────────┐ │
│  │  voxforge-api  │  │voxforge-hardware│ │
│  │ (Axum 0.8/Auth)│  │ (CUDA/MPS/AVX)  │ │
│  └───────┬────────┘  └────────┬────────┘ │
│          ▼                    ▼          │
│  ┌────────────────────────────────────┐  │
│  │          DAG Audio Runner          │  │
│  │ (Piper / Kokoro / Edge-TTS Relays) │  │
│  └────────────────────────────────────┘  │
└──────────────────────────────────────────┘
```

**Stack:** `Rust` · `Axum` · `React 19` · `TypeScript` · `Docker` · `SQLite/PostgreSQL`

<br/>

<div align="center">
  <a href="https://github.com/AMG555/VoxForge"><b>View VoxForge Repository →</b></a>
</div>

</td>
<td width="50%" valign="top">

<h3>✦ 03. Smart Bin</h3>
<b>AI-Powered Waste Segregation</b>

<p>
  <a href="https://github.com/amg555/smart-dustbin"><img src="https://img.shields.io/badge/Type-Hardware--Software_System-10b981?style=flat-square" alt="System Type" /></a>
  <a href="https://github.com/amg555/smart-dustbin"><img src="https://img.shields.io/badge/Repo-amg555%2Fsmart--dustbin-blue?style=flat-square&logo=github&logoColor=white" alt="Smart Bin Repo" /></a>
</p>

Automated waste classification and physical mechanical routing system engineered for real-time edge execution.

- **Edge Computer Vision:** Custom-trained YOLOv11 model running locally on Raspberry Pi 4 for real-time item detection and 4-way stream classification (*Plastic, Metal, Paper, Glass*).
- **Physical Actuation:** Dual-axis servo mechanical guide powered by a PCA9685 16-channel PWM driver and high-torque MG996R servos.
- **Sub-2-Second Cycle:** IR proximity sensor triggers image capture only on insertion, completing inference and mechanical sorting in under 2 seconds.
- **Telemetry & Monitoring:** Four HC-SR04 ultrasonic sensors track fill levels per compartment with automated alert thresholds.
- **Offline-First Resilience:** Self-contained edge inference runs without requiring persistent cloud network connectivity.

```
Waste Insertion ──► IR Trigger ──► Pi Camera Module
                                          │
                                          ▼
┌──────────────────────────────────────────────────┐
│           EDGE RUNTIME (RASPBERRY PI 4)          │
│  YOLOv11 Tensor Inference (<2s Latency)          │
│  [Plastic]     [Metal]     [Paper]     [Glass]   │
└─────────────────────────┬────────────────────────┘
                          ▼
             PCA9685 PWM Servo Mechanism
```

**Stack:** `Python` · `YOLOv11` · `Raspberry Pi 4` · `OpenCV` · `PCA9685/PWM` · `Sensors`

<br/>

<div align="center">
  <a href="https://github.com/amg555/smart-dustbin"><b>View Smart Bin Repository →</b></a>
</div>

</td>
</tr>
</table>

---

### ◈ The AI-Native Workflow

I leverage artificial intelligence as an **execution multiplier**, not a cognitive substitute. AI increases implementation throughput; engineering judgment directs architecture and ensures correctness.

<table width="100%">
<tr>
<td width="50%" valign="top">

<h4>⚡ AI-Amplified Execution</h4>

- Rapid exploratory prototyping and API contract mocking.
- Elimination of repetitive boilerplate across client/server boundaries.
- Generating edge-case test vectors and synthetic validation scenarios.
- Accelerated documentation and structural refactoring.

</td>
<td width="50%" valign="top">

<h4>🧠 Human Engineering Ownership</h4>

- Multi-tenant data isolation and security boundary design.
- Database schema modeling and strict invariant validation.
- Concurrency, memory profiling, and low-level performance tradeoffs.
- Critical path debugging, telemetry instrumentation, and failure-mode analysis.

</td>
</tr>
</table>

---

### ◈ Defensible Technical Arsenal

Technologies grounded in shipped repositories and real-world architectures:

<table width="100%">
<tr>
<td width="25%" valign="top">

**Product & Interfaces**
- Next.js
- React
- React Native / Expo
- TypeScript
- Tailwind CSS

</td>
<td width="25%" valign="top">

**Backend & Data**
- Node.js / Express
- FastAPI / Python
- PostgreSQL
- Supabase (RLS)
- Redis

</td>
<td width="25%" valign="top">

**Systems & Infra**
- Rust (Axum, Cargo)
- Docker / Multi-Arch
- Linux Environments
- Cloudflare Workers / Edge
- CI/CD & Git Automation

</td>
<td width="25%" valign="top">

**AI & Edge**
- YOLO (Computer Vision)
- OpenCV
- OpenAI API Architecture
- Raspberry Pi (GPIO / PWM)
- Embedded Linux Telemetry

</td>
</tr>
</table>

---

### ◈ Engineering Principles

- **Build complete systems, not orphaned features.** A feature is only done when it has data invariants, automated error recovery, telemetry, and a clear user interface.
- **Enforce boundaries at the data and type level.** UI validation is for ergonomics; database constraints, RLS policies, and strict types are for truth.
- **Automate what repeats; deeply audit what is critical.** Use machines to accelerate mechanical plumbing so human attention is concentrated on architecture and reliability.
- **Ship to real environments early.** Software in production teaches you more in 24 hours than speculative whiteboard design does in a month.

---

### ◈ Connect & Signal

<p align="center">
  <b>Actively building products · Open to building high-impact systems with ambitious engineering teams.</b>
</p>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-AMG555-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AMG555)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amal_George-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amal-george-740036320)
[![Email](https://img.shields.io/badge/Email-amgt503%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amgt503@gmail.com)
[![Dormico](https://img.shields.io/badge/Platform-Dormico.in-D97706?style=for-the-badge&logo=google-chrome&logoColor=white)](https://dormico.in)

</div>

<br/>

<div align="center">
  <sub>Built & maintained by Amal George · AMG555</sub>
</div>
