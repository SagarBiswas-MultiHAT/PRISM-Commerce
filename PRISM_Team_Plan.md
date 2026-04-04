# PRISM Commerce V4.0 — Team Plan
### Team Structure · Roles · Ownership · 15-Month Execution Plan

---

| Field | Detail |
|---|---|
| **Team** | 4 CSE Students (No External Hires) |
| **Timeline** | 15 Months · 6 Phases · April 2026 |
| **Mission** | Bangladesh's first Bangla-native, AI-agentic multi-vendor marketplace |
| **Document** | PRISM Commerce Team Plan v1.0 · April 2026 |

---

> *This document defines every role, task, ownership percentage, and month-by-month target for the four-person student team building PRISM Commerce V4.0 from scratch. Fill in the real names of Member B, Member C, and Member D at the top of each section.*

---

## Table of Contents

1. [Section 1 — Team Overview](#section-1--team-overview)
2. [Section 2 — Individual Role Deep-Dives](#section-2--individual-role-deep-dives)
   - [Sagar Biswas — Full-Stack Architect & AI Lead (45%)](#sagar-biswas--full-stack-architect--ai-lead-45)
   - [Member B — Frontend Lead & Mobile Developer (20%)](#member-b--frontend-lead--mobile-developer-20)
   - [Member C — Backend Dev: Payments, Compliance & Logistics (20%)](#member-c--backend-dev-payments-compliance--logistics-20)
   - [Member D — QA Engineer & Growth / Business Dev (15%)](#member-d--qa-engineer--growth--business-dev-15)
3. [Section 3 — Month-by-Month Plan & Targets](#section-3--month-by-month-plan--targets)
4. [Section 4 — Milestones, Revenue Gates & Key Decisions](#section-4--milestones-revenue-gates--key-decisions)
5. [Section 5 — Collaboration, Git Workflow & Team Rules](#section-5--collaboration-git-workflow--team-rules)

---

## Section 1 — Team Overview

The PRISM Commerce team is made up of four CSE students. Every person wears multiple hats, but each person has a **clear primary domain they own fully**. Overlap is intentional — code reviews, feature discussions, and cross-domain help are encouraged. The split below reflects each person's estimated contribution to the overall platform in terms of complexity, hours, and criticality of the domain.

### 1.1 Team Composition

| Member | Role Title | Primary Domain | Ownership |
|---|---|---|---|
| **Sagar Biswas** | Full-Stack Architect & AI Lead | Architecture · NestJS Core · All 15 AI Modules · DevOps | **45%** |
| **Member B** *(Your Name)* | Frontend Lead & Mobile Developer | Next.js 15 · React Native · UI/UX · PWA · i18n | **20%** |
| **Member C** *(Your Name)* | Backend Dev: Payments, Compliance & Logistics | All Payment Gateways · Escrow · KYC · 3PL · WhatsApp API | **20%** |
| **Member D** *(Your Name)* | QA Engineer & Growth / Business Dev | Testing Suite · Vendor Acquisition · PRISM Academy · Marketing | **15%** |

---

### 1.2 Why These Ownership Percentages?

Ownership is **not** a simple 25/25/25/25 split because the domains are not equal in complexity, risk, or hours. Here is the full reasoning:

| Member | % | Justification |
|---|---|---|
| **Sagar Biswas** | 45% | Carries the heaviest technical load: system architecture decisions, all 15 AI/ML modules (the core differentiator), CQRS/Event Sourcing, database design (50+ tables with RLS/pgvector), Docker/CI-CD/monitoring stack, and the full backend skeleton. The AI layer alone (GBR ONNX, Sahayak agentic mode, RAG, Opportunity Engine) represents 30–45% of PRISM's unique value. |
| **Member B** | 20% | The frontend spans two frameworks (Next.js 15 + React Native), three rendering strategies (RSC, PPR, Client), full bilingual UI (Bengali/English), live commerce overlays, short-form video feed, POS PWA, and the entire vendor and buyer dashboard experience. This is a very large surface area. |
| **Member C** | 20% | Payment integration is where the money flows — and where bugs are catastrophic. Owns bKash, Nagad, SSLCommerz, Bangla QR, Rocket, escrow accounting, KYC pipeline, WhatsApp templates, all five 3PL APIs, COD intelligence, BNPL, and VAT reporting. Legal/regulatory liability sits here. |
| **Member D** | 15% | Testing, vendor acquisition, and PRISM Academy are essential but involve less raw engineering complexity. Member D's QA work protects the whole team, and their BD work fills the platform with real users — but the domain carries less technical risk than the others. |

> ⚠️ **IMPORTANT — Founders' Agreement:**
> This is a **founding equity split, not a salary**. Every member works for free during development. Once the platform generates revenue, distribution follows this split. The team should formalize this in a written **Founders' Agreement** (a simple one-page document) signed by all four members **before Month 2**. Member D is responsible for drafting the first version in Month 1.

---

## Section 2 — Individual Role Deep-Dives

Each role card below shows the primary domains owned, and a phase-by-phase breakdown of every major task that person is responsible for across the 15-month project.

**"Responsible for" means:** you design it, build it, test it, and deploy it — though we, the teammates will review your code and help when you get stuck.

---

## Sagar Biswas — Full-Stack Architect & AI Lead (45%)

### Primary Domains

| Domain A | Domain B |
|---|---|
| Monorepo & project scaffolding (Turborepo) | NestJS modular monolith architecture |
| CQRS + Event Sourcing (`@nestjs/cqrs`) | PostgreSQL 16 schema (50+ tables, RLS, pgvector) |
| Redis 7 + BullMQ (cache, queues, pub/sub) | All 15 AI/ML modules (GBR ONNX, Sahayak, RAG, Opportunity Engine, Bundle AI) |
| Docker + Docker Compose + CI/CD (GitHub Actions) | Grafana + Prometheus + Loki + OpenTelemetry |
| Security architecture (RBAC, JWT, rate limiting, RLS) | Meilisearch + hybrid search (semantic + full-text) |
| Performance optimization & infrastructure scaling | Technical code review for all PRs across the team |

---

### Sagar — Phase 1: Foundation & Compliance (Months 1–3)

- Create Turborepo monorepo with Next.js 15 + NestJS workspaces
- Design and implement all 50+ PostgreSQL tables with Prisma schema
- Set up `pgvector` extension and `IVFFlat` index for RAG
- Implement 8-role RBAC with Auth.js + JWT + refresh tokens + MFA
- Configure Docker + Docker Compose for all services
- Set up Redis 7 + BullMQ event bus architecture
- Build CQRS foundation: Command handlers, Query handlers, Event Store
- Implement PgBouncer connection pooling
- Set up GitHub Actions CI/CD (lint, test, build, deploy pipelines)
- Configure OpenTelemetry + Grafana Tempo distributed tracing
- Set up Grafana + Prometheus + Loki + Sentry observability stack
- Configure API Gateway with rate limiting (`@nestjs/throttler`)
- Implement Row-Level Security (RLS) policies in PostgreSQL

### Sagar — Phase 2: Revenue & Trust (Months 4–5)

- Build subscription billing engine (5-tier: Free to Enterprise)
- Implement commission tracking system per transaction
- Build PRISM Wallet backend (cashback, refunds, balance, withdrawal)
- Implement Flash Sale engine backend with countdown + limited stock logic
- Build promoted listings auction system
- Create admin analytics API endpoints (GMV, revenue, orders, users)

### Sagar — Phase 3: AI & GenAI (Months 6–8)

- Train GBR model (scikit-learn) on BD retail + synthetic dataset
- Export GBR to ONNX format; integrate `onnxruntime-node` for <80ms inference
- Build **Module 01** — Forecast engine (13-feature GBR per product: 7/14/30-day forecasts)
- Build **Module 02** — Smart Reorder Point calculator (festival + weather multipliers)
- Build **Module 03** — Sales Velocity Momentum Ranker (exponential smoothing)
- Seed `festival_calendar` table (8+ BD festivals with surge data)
- Integrate OpenWeatherMap API with 6h Redis cache
- Build **Module 04** — AI Coupon Optimizer (optimal discount formula)
- Build **Module 05** — Order Anomaly Detector (Z-score + 6 signals + COD history score)
- Build **Module 06** — Vendor Performance Score (VPS) calculator (5-component weighted score)
- Build **Module 14** — Opportunity Engine (15-min CRON scan, 4 alert types)
- Build **Module 15** — Bundle Recommendation Engine (co-purchase matrix, weekly computation)
- Cross-vendor category velocity CRON (hourly aggregation, min 3 vendors for privacy)
- ML feedback loop: `forecast_accuracy` table + weekly retrain trigger
- Deploy Ollama (Llama 3.2-8B) on VPS with GPU if available
- Build RAG pipeline: product embeddings (MiniLM-L6-v2) + pgvector cosine search
- Build **Module 12** — Sahayak V1 (advisor mode with RAG context)
- Build **Module 12** — Sahayak V2 (agentic mode with 9 function calls: `search_products`, `get_forecast`, `create_coupon`, `add_to_cart`, `apply_coupon`, `get_order_status`, `set_discount`, `get_analytics`, `go_live`)
- Integrate Web Speech API + Whisper model for Bangla voice commands
- Implement reciprocal rank fusion (RRF) for hybrid Meilisearch + semantic search results
- Build cold-start seed system (`synthetic_sales_seed` table + 3-tier bootstrap)

### Sagar — Phase 4: Communication & Commerce (Months 9–10)

- Build in-app chat backend with WebSocket (Socket.io)
- Build AI auto-response engine for common buyer queries
- Implement multi-channel notification center backend (WhatsApp, in-app, email)
- Build support ticket system backend with escalation logic
- Integrate LiveKit (WebRTC SFU) for live commerce streaming
- Build shoppable product overlay system for live streams
- Build short-form video feed ranking algorithm (interests + trending + recency)
- Build live Q&A and emoji reaction backend

### Sagar — Phase 5: Logistics & Mobile (Months 11–12)

- Build 3PL intelligent routing engine (cost + ETA + reliability scoring)
- Build COD fraud scoring algorithm (address + phone + buyer history → risk 0–100)
- Build COD history score (per buyer, increments on successful COD delivery)
- Build COD-to-digital incentive system (৳20 off for bKash switch at checkout)
- Build POS mode backend (barcode → inventory update → sale record)
- Build POS offline queue + sync on reconnect
- Build referral/affiliate system backend with commission tracking
- Build advanced analytics API (category breakdown, delivery metrics, attribution)

### Sagar — Phase 6: Polish, Launch & Scale (Months 13–15)

- Conduct full security audit: OWASP ZAP + manual pentest of all endpoints
- Implement API versioning (`/api/v1/`) + schema governance documentation
- Run k6 load test: optimize bottlenecks to achieve <200ms p95 at 10K concurrent users
- Prepare K8s manifests for Phase 3 scaling (future infrastructure)
- Set up production VPS on Hetzner/DigitalOcean with Cloudflare CDN
- Prepare investor pitch technical slides (if needed) — architecture diagrams, AI demo
- Post-launch monitoring, hotfixes, and infrastructure auto-scaling
- Architect plan for Chattogram + Sylhet expansion
- Document K8s migration path for Phase 3 scale

---

## Member B — Frontend Lead & Mobile Developer (20%)

### Primary Domains

| Domain A | Domain B |
|---|---|
| Next.js 15 App Router + Partial Pre-Rendering (PPR) | shadcn/ui + Tailwind CSS design system |
| next-intl bilingual routing (EN + Bengali) | Zustand (cart/offline) + React Query (server state) |
| Recharts + Nivo for analytics dashboards | PWA (service worker, offline POS, installable app) |
| React Native (Expo) mobile app | Short-form video reel feed UI |
| LiveKit live commerce shoppable UI | WCAG 2.1 AA accessibility compliance |
| SEO: Schema.org JSON-LD, sitemap, meta tags | Bengali Hind Siliguri font + Bengali numerals |

---

### Member B — Phase 1: Foundation & Compliance (Months 1–3)

- Set up Next.js 15 App Router with TypeScript in Turborepo workspace
- Configure shadcn/ui + Tailwind CSS + Radix primitives design system
- Set up next-intl with EN (`/en/`) and Bengali (`/bn/`) routing + locale auto-detect
- Build base layout components: Navbar, Sidebar, Footer, Bottom Nav (mobile)
- Build vendor dashboard shell with tab navigation (responsive)
- Build buyer homepage layout (mobile-first, 375px breakpoint)
- Implement Hind Siliguri Bengali font with conditional loading for `bn` locale
- Build product listing page (grid/list toggle, filters, Bangla search input)
- Build product detail page with image gallery, variants, add-to-cart
- Set up Zustand cart store (persistent, offline-capable with localStorage)
- Build Auth pages: Login, Register, Password Reset (Auth.js integration)
- Set up React Query for all server state (products, orders, user)

### Member B — Phase 2: Revenue & Trust (Months 4–5)

- Build Subscription tier selection UI (5 tiers, feature comparison table)
- Build vendor KYC document upload UI (NID, Trade License, TIN — drag & drop)
- Build PRISM Wallet UI (balance, top-up, withdrawal, transaction history)
- Build vendor onboarding wizard (step-by-step in Bangla + English)
- Build Flash Sale UI: countdown timer, limited stock indicator, push badge
- Build promoted listings management panel for vendors
- Build PRISM Verified tier badge display on product and vendor pages
- Build PRISM Protect information pages + eligibility indicator
- Build product catalog page with Schema.org JSON-LD for SEO

### Member B — Phase 3: AI & GenAI (Months 6–8)

- Build AI Forecast Dashboard: 7/14/30-day chart (Recharts area chart), confidence gauge
- Build Reorder Alert panel with weather and festival overlays on forecast chart
- Build What-If Scenario Planner UI (interactive sliders for GBR features)
- Build Opportunity Engine alert cards (4 types: red/yellow/green/blue)
- Build Anomaly Alert Dashboard for admin (Z-score flagged orders table)
- Build VPS Leaderboard UI (tier badges: Platinum/Gold/Silver/Watch)
- Build Bundle Recommendation suggestion cards for vendor dashboard
- Build Sahayak chat UI for vendors (floating panel, Bangla/English toggle)
- Build Sahayak chat UI for buyers (embedded in product/search pages)
- Build Bangla voice command button + Web Speech API integration on frontend
- Connect Meilisearch + semantic search to product search bar (type-ahead)

### Member B — Phase 4: Communication & Commerce (Months 9–10)

- Build in-app chat UI: buyer-seller message thread with real-time WebSocket
- Build notification bell + notification center (read/unread, multi-channel)
- Build support ticket submission and tracking UI
- Build PRISM Academy UI: video grid, module progress tracker, certification badge
- Build LiveKit live stream viewer UI: shoppable overlay, Q&A panel, reactions, viewer count
- Build vendor "Go Live" studio UI: start stream, add products, manage comments
- Build short-form video reel feed (TikTok-style vertical swipe, auto-play)
- Build reel recording UI: in-app camera, filters, text overlay, product tag selector
- Build "Explore" tab with reel + live stream discovery

### Member B — Phase 5: Logistics & Mobile (Months 11–12)

- Build order tracking UI with 3PL delivery status timeline and map (optional)
- Build 3PL comparison UI showing cost + ETA for each partner
- Build COD fraud warning UI for vendors (high-risk order flags)
- Build POS mode PWA: barcode scanner (camera API), item list, total, accept Bangla QR
- Build POS mode offline sync indicator and queue display
- Build React Native Expo mobile app: browse, search, product detail, buy flow
- Build React Native: in-app chat, order tracking, short-form video feed
- Build React Native: vendor dashboard (forecast, alerts, basic orders)
- Build referral system UI: referral link share, reward history
- Build advanced analytics dashboard: Recharts charts, date range picker, CSV export

### Member B — Phase 6: Polish, Launch & Scale (Months 13–15)

- Run full WCAG 2.2 AA audit: fix contrast ratios, keyboard nav, screen reader labels
- Build content moderation review UI for admin (product listing queue, review flags)
- Polish all onboarding flows based on beta vendor feedback
- Build investor-facing landing page (optional) and marketing pages
- Fix all bugs found during beta testing (Month 14) in UI/UX
- Optimize image loading (`next/image`), lazy loading, and bundle sizes
- Record demo video / screenshots for PRISM Academy and marketing
- Create social media visuals for launch (Facebook + TikTok)
- Final polish pass on all UI after beta learnings

---

## Member C — Backend Dev: Payments, Compliance & Logistics (20%)

### Primary Domains

| Domain A | Domain B |
|---|---|
| bKash PGW + Nagad PGW + SSLCommerz integration | Bangla QR (Bangladesh Bank mandate, June 2026) |
| Rocket + PRISM Wallet payment flows | Escrow system (regulatory — all prepaid orders) |
| Vendor KYC + compliance document verification pipeline | PRISM Protect buyer guarantee + dispute resolution |
| WhatsApp Cloud API (12 templates, EN + Bengali) | Pathao + RedX + Paperfly + Steadfast + eCourier APIs |
| COD intelligence (fraud scoring + history score) | BNPL partner integration (ShopUp / IDLC) |
| VAT computation + monthly VAT reports | Social commerce APIs: Facebook Shops, TikTok Shop, YouTube Shopping |

---

### Member C — Phase 1: Foundation & Compliance (Months 1–3)

- Research and set up developer accounts for bKash, Nagad, SSLCommerz, Rocket
- Submit WhatsApp Business API application + Meta business verification *(start early — takes 2–4 weeks)*
- Implement Bangla QR integration with 3+ bank APIs *(test well before June 2026 mandate)*
- Integrate bKash PGW: payment initiation, redirect flow, webhook server-side verification
- Integrate Nagad PGW: same flow (idempotent webhook handling)
- Integrate SSLCommerz: card + net banking + MFS fallback
- Integrate Rocket MFS payment
- Implement server-side payment webhook verification for **ALL** gateways *(security critical)*
- Build vendor KYC document upload handler (S3-compatible storage for NID, trade license)
- Build compliance document verification workflow (admin review queue)
- Build escrow system: separate ledger table, hold on payment, dual-approval for manual release
- Implement double-entry escrow accounting with daily automated reconciliation

### Member C — Phase 2: Revenue & Trust (Months 4–5)

- Build PRISM Verified 3-tier verification pipeline (Basic NID → Business Trade License → Premium Brand)
- Build vendor approval workflow: KYC review → admin approve/reject → email notification
- Implement vendor disbursement engine: post-escrow-release → payout queue → bKash/Nagad transfer
- Build PRISM Protect backend: 7-day return window, dispute claim submission, resolution SLA timers
- Build PRISM protection pool: 0.5% per transaction → fund pool → refund disbursement
- Build flash sale scheduling backend: start/end times, stock reservation, post-sale analytics

### Member C — Phase 3: AI & GenAI (Months 6–8)

- Complete all 12 WhatsApp templates (stock alerts, order updates, festival pre-surge, Sahayak summaries)
- Submit all 12 templates to Meta for approval in **English AND Bengali**
- Build WhatsApp dispatch service: BullMQ job → Meta Cloud API → delivery status tracking
- Connect stock-below-ROP alert → WhatsApp notification trigger
- Connect Opportunity Engine critical (red) alerts → WhatsApp push
- Build WhatsApp weekly digest: automated report of key vendor metrics
- Integrate Sahayak tool endpoints owned by Member C: `get_forecast`, `get_analytics`, `get_order_status`, `create_coupon`, `set_discount`, `add_to_cart`, `apply_coupon`, `search_products`, `go_live` trigger
- OpenAI GPT-4o fallback setup (for Pro+ tier only)

### Member C — Phase 4: Communication & Commerce (Months 9–10)

- Build Facebook Shops API integration: product catalog sync, order sync
- Build TikTok Shop API integration: catalog push, order pull + fulfillment
- Build YouTube Shopping integration: live stream product linking
- Build cross-platform sales attribution tracking (which channel drove which order)
- Handle WebSocket reconnection + message delivery guarantees for in-app chat
- Build AI auto-response engine: detect common queries → template replies → vendor override

### Member C — Phase 5: Logistics & Mobile (Months 11–12)

- Integrate Pathao Courier API: quote, book, track, webhook for status updates
- Integrate RedX API: same flow + COD reconciliation webhook
- Integrate Paperfly API: sub-district routing + tracking
- Integrate Steadfast API: bulk rate negotiation endpoint
- Integrate eCourier API: same-day Dhaka delivery option
- Build intelligent routing engine: score 3PL options, auto-assign, auto-failover to backup
- Build COD fraud scoring algorithm (address + phone + buyer history → risk 0–100)
- Build COD history score (increments on each successful COD delivery)
- Build COD-to-digital incentive (৳20 discount coupon if switching to bKash at checkout)
- Integrate BNPL: ShopUp and/or IDLC Capital API for 3/6/12-month EMI
- Build VAT computation module (15% auto on applicable transactions) + monthly VAT report generator
- Build Finance Admin dashboard APIs: escrow monitor, disbursement queue, commission reconciliation

### Member C — Phase 6: Polish, Launch & Scale (Months 13–15)

- Conduct escrow system audit: verify all edge cases (timeout, dispute, partial refund)
- Stress test all payment gateways in staging with simulated failures
- Verify full Bangla QR compliance before June 2026 mandate deadline
- Handle all payment-related bugs found during beta (Month 14)
- Review and implement any new Bangladesh Bank regulatory requirements
- Prepare compliance documentation: escrow ledger reports, VAT statements
- Support vendor payments and logistics queries during public launch (Month 15)
- Begin Chattogram 3PL partnership outreach
- Set up ops runbook for common payment/logistics issues

---

## Member D — QA Engineer & Growth / Business Dev (16%)

### Primary Domains

| Domain A | Domain B |
|---|---|
| Jest unit tests for all NestJS services (80%+ coverage) | Supertest integration tests for all API endpoints |
| Playwright E2E tests for 8 critical user flows | k6 load testing (10K concurrent users) |
| OWASP ZAP security scanning + manual pentest support | GBR model accuracy validation vs. WMA baseline |
| PRISM Academy: Bangla video scripts + content calendar | Vendor acquisition: field sales in Dhaka markets |
| Project documentation (README, API docs, onboarding guides) | PostHog + Grafana dashboard configuration for analytics |
| Social media management (Facebook, TikTok, YouTube for PRISM) | Beta support: vendor onboarding assistance + feedback collection |

---

### Member D — Phase 1: Foundation & Compliance (Months 1–3)

- Set up Jest test framework and testing conventions for NestJS
- Set up Playwright for E2E tests with test environment configuration
- Write unit tests for auth flows (login, register, JWT refresh, MFA)
- Write integration tests for all Phase 1 API endpoints (auth, vendors, products)
- Set up test database seeding scripts (consistent test data)
- Configure GitHub Actions to run tests on every PR (test gate)
- Write RLS isolation tests: verify vendors cannot access each other's data
- Set up PostHog for product analytics tracking
- Set up UptimeRobot for external uptime monitoring + alerting
- Create Notion project workspace: task board, meeting notes, decision log
- Write `README.md` for the monorepo with setup instructions for the team
- Draft the Founders' Agreement document *(to be signed before Month 2)*
- Open 5 developer accounts / API keys needed by Member C (assist)

### Member D — Phase 2: Revenue & Trust (Months 4–5)

- Write integration tests for all payment flows (mock bKash, Nagad, SSLCommerz)
- Write E2E test: full buyer checkout flow (browse → cart → checkout → confirmation)
- Write E2E test: vendor onboarding flow (register → KYC → product listing)
- Write escrow lifecycle tests (hold → release → dispute → refund paths)
- Begin identifying first real vendor contacts in Dhaka (Chawkbazar, Mirpur, Uttara)
- Set up Facebook Group presence for PRISM (vendor education content)
- Write Gate 1 tracking report: Are we on track for 20 vendors by Month 4?

### Member D — Phase 3: AI & GenAI (Months 6–8)

- Write GBR model smoke tests: validate inference output format + ranges
- Validate GBR vs. WMA baseline: GBR must not diverge by >50% on test data
- Write festival feature injection tests (verify `is_festival_week` flag triggers correctly)
- Write weather impact tests (verify `precipitation_mm` feature changes forecast output)
- Write integration tests for all AI module endpoints (Modules 01–06, 14, 15)
- Write integration tests for Sahayak agentic tool calls (all 9 tools)
- Write RAG semantic search tests with Bangla queries (verify correct product returns)
- Write Opportunity Engine tests (verify 4 alert types fire under correct conditions)
- Script and record first 3 PRISM Academy tutorial videos in Bangla (product listing, AI forecast, how to go live)
- Set up YouTube channel and Facebook page for PRISM Academy content

### Member D — Phase 4: Communication & Commerce (Months 9–10)

- Write E2E test: live commerce flow (vendor goes live → buyer joins → buys product during stream)
- Write integration tests for WhatsApp dispatch (all 12 templates, mock Meta API)
- Write integration tests for in-app chat (send, receive, AI auto-response)
- Write integration tests for social commerce sync (FB Shops, TikTok Shop)
- Record PRISM Academy videos: WhatsApp notification setup, using Sahayak, live streaming guide
- Begin active vendor outreach: visit 20 shops in Dhaka, demo the platform, sign up first vendors
- Collect vendor feedback via Google Form after each demo
- Gate 3 tracking report: Are we at 100 vendors and ৳150K revenue?

### Member D — Phase 5: Logistics & Mobile (Months 11–12)

- Write E2E test: POS mode (scan barcode → process sale → inventory update → Bangla QR accept)
- Write 3PL failover tests (primary 3PL rejection → auto-assign backup)
- Write COD fraud scoring tests (high-risk phone/address patterns)
- Write BNPL flow integration tests
- Set up k6 load test scripts: simulate 10K concurrent users on checkout, search, dashboard endpoints
- Run preliminary k6 load tests and report bottlenecks to Sagar
- Test React Native app on Android + iOS (Expo Go) for core flows
- Write POS offline sync tests (queue orders offline → sync on reconnect)
- Record PRISM Academy videos: 3PL and delivery guide, POS mode tutorial
- Expand vendor acquisition: target frustrated Daraz sellers via Facebook Groups
- Gate 4 tracking report: Are we at 500 vendors and ৳350K revenue?
- ৳20 COD-to-digital incentive field test with vendors

### Member D — Phase 6: Polish, Launch & Scale (Months 13–15)

- Run full k6 load test suite (10K concurrent): document results, pass/fail criteria
- Run OWASP ZAP security scan on all endpoints; report critical and high findings
- Assist Sagar with manual pentest: payment webhook replay attacks, RLS bypass attempts
- Run all 8 Playwright E2E flows and confirm 100% pass before beta launch
- Support 50 beta vendors in Dhaka (Month 14): onboarding calls, bug reports, feedback
- Compile beta feedback report and prioritize bugs for Members A, B, C
- Record PRISM Academy complete module set (target: 10 videos total)
- Build "PRISM Certified Seller" certification quiz and badge system (with Member B)
- Run vendor acquisition sprint for public launch (Month 15): target 500 vendors
- Manage social media launch campaign: Facebook, TikTok, YouTube
- Set up vendor WhatsApp group for community building
- Write Gate 5 report: public launch metrics dashboard
- Prepare Seed round pitch materials (if applicable)

---

## Section 3 — Month-by-Month Plan & Targets

The 15-month plan is divided into 6 phases. Each month shows the goal, the milestone target, and a side-by-side view of each team member's primary tasks. This is the shared sprint board — **hold weekly meetings to track progress against these**.

---

## PHASE 1 — Foundation & Compliance (Months 1–3)

---

### Month 1 — Foundation

> **Goal:** Working monorepo, database schema, Auth system, Docker up, CI/CD live

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Create Turborepo monorepo (Next.js 15 + NestJS) | Next.js 15 App Router + TypeScript setup | Open bKash, Nagad, SSLCommerz dev accounts | Set up Jest + Playwright testing frameworks |
| 2 | Design all 50+ PostgreSQL tables (Prisma schema) | shadcn/ui + Tailwind CSS design system | Submit WhatsApp Business API application | Configure GitHub Actions test gate on PRs |
| 3 | Set up pgvector + IVFFlat index | next-intl EN/BN routing setup | Research Bangla QR bank API documentation | Set up PostHog + UptimeRobot |
| 4 | 8-role RBAC with Auth.js + JWT + MFA | Base layout components (Navbar, Sidebar, Footer) | Implement KYC document upload backend | Create Notion project board for team |
| 5 | Docker Compose all services | Auth pages (Login, Register) | Begin escrow system database design | Write monorepo README + setup guide |
| 6 | GitHub Actions CI/CD pipeline | Zustand cart store + React Query setup | Set up S3-compatible storage for documents | Draft Founders' Agreement document |

---

### Month 2 — Backend Core

> **Goal:** Redis + BullMQ live, CQRS foundation, Escrow system, Bangla QR started, Meilisearch up

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Redis 7 + BullMQ event bus setup | Vendor dashboard shell with tab nav | Escrow system: ledger tables + hold logic | Write auth unit + integration tests |
| 2 | CQRS: CommandBus, QueryBus, Event Store | Buyer homepage (mobile-first 375px) | Double-entry escrow accounting design | Write RLS isolation tests (cross-vendor) |
| 3 | PgBouncer connection pooling | Product listing page (filters + Bangla search) | Bangla QR API research + initial integration | Write escrow hold/release unit tests |
| 4 | Meilisearch setup + product index | Hind Siliguri Bengali font integration | Test Bangla QR with 3 bank test environments | Set up test data seeding scripts |
| 5 | WebSocket (Socket.io) foundation | Product detail page (gallery, variants, cart) | KYC document verification workflow (admin queue) | Weekly meeting notes + decision log |
| 6 | Basic API routing structure | Responsive bottom navigation (mobile) | Compliance document type definitions | Research 5 Dhaka markets for future field sales |

---

### Month 3 — Payments & Observability

> **Goal:** All payment gateways live (test mode), KYC pipeline, OpenTelemetry, i18n complete

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | API Gateway + Redis rate limiting | Vendor onboarding wizard (Bangla + English) | bKash PGW: initiate + redirect + webhook verify | Integration tests: all payment webhook flows |
| 2 | OpenTelemetry + Grafana Tempo tracing | Product listing form with variants | Nagad PGW: same flow + idempotency | Integration tests: vendor KYC pipeline |
| 3 | Grafana + Prometheus + Loki + Sentry | Category browsing + filter sidebar | SSLCommerz: card + net banking + fallback | Integration tests: product CRUD endpoints |
| 4 | Append-only audit_logs with RLS | Bengali numeral formatting (`Intl.NumberFormat`) | Rocket MFS integration | E2E test: vendor registration + onboarding |
| 5 | API versioning `/api/v1/` structure | Bengali date formatting | Bangla QR: payment flow + QR code generation | E2E test: buyer product browsing + cart |
| 6 | Security headers (CORS, HSTS, CSRF) | Mobile-first checkout page layout | Server-side webhook security for all gateways | Manual security check: JWT expiry, CORS |

---

## PHASE 2 — Revenue & Trust (Months 4–5)

> **Revenue Gates to hit:**
> - **Gate 1** = 20 vendors on platform by end of Month 4
> - **Gate 2** = First ৳50K revenue month by end of Month 6

---

### Month 4 — Billing & Verification

> **Goal:** Subscription billing live, PRISM Wallet, PRISM Verified 3-tier KYC, first 20 vendors onboarded

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Subscription billing engine (5-tier SaaS) | Subscription plan selection UI (5 tiers) | PRISM Verified 3-tier KYC pipeline backend | Gate 1 tracking: target 20 real vendors |
| 2 | Commission tracking per transaction (%) | KYC document upload UI (drag & drop) | NID verification handler (Basic tier) | Field sales: visit Chawkbazar + Mirpur shops |
| 3 | PRISM Wallet backend (balance, cashback, withdraw) | PRISM Wallet UI (balance, history, withdraw) | Trade License + TIN verification (Business tier) | Demo the platform on tablet to shop owners |
| 4 | Admin analytics API (GMV, revenue, users) | PRISM Verified tier badge on listings | Brand authorization verification (Premium tier) | E2E test: subscription purchase flow |
| 5 | Vendor approval state machine | Vendor approval status page | KYC rejection → vendor notification flow | Integration tests: KYC pipeline all 3 tiers |

---

### Month 5 — Trust & Commerce

> **Goal:** PRISM Protect live, Flash Sales, Promoted Listings, Schema.org SEO, Vendor Disbursements

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | PRISM Protect backend (protection pool 0.5%) | Flash Sale UI (countdown, stock badge, push) | Vendor disbursement: escrow release → payout | E2E test: full checkout with escrow + delivery confirm |
| 2 | Dispute resolution SLA timers | Product catalog with Schema.org JSON-LD | PRISM Protect refund flow (buyer → vendor chargeback) | E2E test: PRISM Protect dispute → refund flow |
| 3 | Flash Sale engine (countdown + stock reservation) | PRISM Protect info + eligibility indicator UI | Return window enforcement (7-day timer) | Integration tests: flash sale create + run |
| 4 | Promoted listings auction system | Dispute submission form (buyer side) | Protection pool fund management | Gate 2 progress check: ৳50K revenue path |
| 5 | Vendor disbursement engine (post-escrow) | Admin dispute resolution panel | Flash sale backend scheduling + analytics | Vendor feedback survey (first 20 vendors) |

---

## PHASE 3 — AI & GenAI (Months 6–8)

> **⚡ This is the core differentiator phase.** The GBR ONNX model, Sahayak agentic assistant, and RAG pipeline make PRISM unique. **Budget the most time here.**

---

### Month 6 — GBR + Forecast AI

> **Goal:** GBR ONNX model deployed (<80ms inference), Modules 01–03 live, Festival + Weather features injected, cold-start system

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Train GBR on BD retail + synthetic dataset | AI Forecast Dashboard (Recharts 7/14/30-day) | Submit all 12 WhatsApp templates to Meta | GBR smoke tests (output format + value ranges) |
| 2 | Export to ONNX; integrate onnxruntime-node | Confidence gauge + feature importance chart | WhatsApp dispatch service (BullMQ → Meta API) | GBR vs. WMA baseline validation (<50% diverge) |
| 3 | Module 01: Forecast (13-feature GBR per product) | Festival surge overlay on forecast chart | Stock-below-ROP → WhatsApp alert trigger | Festival feature injection test |
| 4 | Module 02: Smart Reorder Point calculator | Weather overlay (monsoon warning indicator) | Festival pre-surge WhatsApp notification | Weather feature impact test |
| 5 | Module 03: Sales Velocity Momentum Ranker | What-If Scenario Planner (interactive sliders) | WhatsApp weather alert (monsoon + category) | WhatsApp dispatch integration tests |
| 6 | Seed `festival_calendar` (8+ BD festivals) | Reorder alert notification panel | — | — |
| 7 | OpenWeatherMap integration (6h Redis cache) | — | — | — |
| 8 | Cold-start seed system (`synthetic_sales_seed`) | — | — | — |
| 9 | Redis 24h cache for AI forecast results | — | — | — |

---

### Month 7 — Intelligent Engines

> **Goal:** Modules 04–06, Opportunity Engine (15-min CRON), Bundle Engine, cross-vendor category velocity CRON, ML feedback loop

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Module 04: AI Coupon Optimizer | Opportunity Engine alert cards (4 types) | WhatsApp digest: weekly vendor metrics report | Integration tests: all AI module endpoints |
| 2 | Module 05: Order Anomaly Detector (Z-score) | Anomaly Alert Dashboard for admin | Opportunity Engine critical alert → WhatsApp push | Opportunity Engine alert tests (4 types) |
| 3 | Module 06: Vendor Performance Score (VPS) | VPS Leaderboard (Platinum/Gold/Silver/Watch) | Coupon auto-creation tool API endpoint | Category velocity min-3-vendor privacy test |
| 4 | Module 14: Opportunity Engine (15-min CRON) | Bundle suggestion cards (vendor dashboard) | Coupon bulk create + management backend | VPS score calculation tests |
| 5 | Module 15: Bundle Recommendation Engine | Category velocity heatmap (optional viz) | — | Gate 3 progress: target 100 vendors path |
| 6 | Category velocity CRON (hourly aggregation) | — | — | — |
| 7 | ML feedback loop (forecast_accuracy + retrain) | — | — | — |

---

### Month 8 — Sahayak & RAG

> **Goal:** Ollama deployed, RAG pipeline (pgvector), Sahayak V1 (advisor) + V2 (agentic), Bangla voice commands

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Deploy Ollama (Llama 3.2-8B) on VPS | Sahayak chat UI (vendor floating panel) | API endpoints Sahayak can call as tools: `get_forecast`, `get_analytics`, `get_order_status` | Sahayak agentic tool call integration tests |
| 2 | Build RAG: product embeddings (MiniLM-L6-v2) | Sahayak chat UI (buyer embedded in search) | `create_coupon`, `set_discount`, `add_to_cart` | RAG Bangla query tests ("ঈদের লাল শাড়ি" etc.) |
| 3 | IVFFlat index + cosine similarity search | Voice command button + Bangla microphone UI | `apply_coupon`, `search_products`, `go_live` trigger | Voice command accuracy testing (Bangla) |
| 4 | Reciprocal rank fusion (Meilisearch + semantic) | Real-time Sahayak response streaming UI | OpenAI GPT-4o fallback (for Pro+ tier only) | Script PRISM Academy video: using Sahayak |
| 5 | Sahayak V1: advisor mode with RAG context | Bangla/English auto-toggle indicator | — | Script: live streaming guide for vendors |
| 6 | Sahayak V2: agentic mode (9 function calls) | — | — | Record and upload 3 Academy videos |
| 7 | Web Speech API + Whisper Bangla voice input | — | — | — |
| 8 | Sahayak rate limiting by subscription tier | — | — | — |
| 9 | Sahayak conversation audit log | — | — | — |

---

## PHASE 4 — Communication & Commerce (Months 9–10)

---

### Month 9 — Chat, Notifications & Academy

> **Goal:** WhatsApp all 12 templates live, in-app chat, notification center, support tickets, PRISM Academy MVP (5 videos)

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | In-app chat backend (WebSocket, Socket.io) | In-app chat UI (buyer-seller thread) | All 12 WhatsApp templates live and approved | WhatsApp dispatch integration tests (all 12) |
| 2 | AI auto-response engine for chat | Notification bell + notification center UI | WhatsApp notification for all trigger events | In-app chat E2E test (send/receive/AI reply) |
| 3 | Multi-channel notification center backend | Support ticket submission + tracking UI | In-app chat notification routing (WhatsApp fallback) | Begin field sales in Uttara + Gulshan markets |
| 4 | Support ticket system with escalation logic | PRISM Academy UI (video grid, progress tracker) | Support ticket routing + SLA timers | Gate 3 report: 100 vendors + ৳150K revenue? |
| 5 | Notification preferences per user | Certification badge display system | — | Produce 5 PRISM Academy Bangla videos |
| 6 | — | — | — | Publish Academy on YouTube + Facebook |

---

### Month 10 — Live Commerce & Social

> **Goal:** LiveKit live streaming, shoppable overlays, short-form reel feed, TikTok Shop sync, Facebook Shops

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | LiveKit WebRTC SFU integration | LiveKit viewer UI (overlay, Q&A, reactions, count) | Facebook Shops API: catalog + order sync | E2E: go live → buyer joins → buys during stream |
| 2 | Shoppable video overlay system (live streams) | Vendor "Go Live" studio UI (stream controls) | TikTok Shop API: catalog push + order pull | E2E: reel upload → product tagged → buyer buys |
| 3 | Live Q&A + emoji reaction backend | TikTok-style reel feed (vertical swipe, auto-play) | YouTube Shopping: live stream product linking | Social commerce sync tests (FB + TikTok) |
| 4 | Short-form video feed ranking algorithm | Reel recording UI (camera, filters, product tag) | Cross-platform sales attribution tracking | Expand vendor acquisition: target TikTok/FB sellers |
| 5 | HLS recording for live stream replays | "Explore" tab: reels + live stream discovery | AI auto-response custom override for vendors | Record PRISM Academy: live streaming guide |

---

## PHASE 5 — Logistics & Mobile (Months 11–12)

---

### Month 11 — Logistics & COD Intelligence

> **Goal:** 5 3PL partners live, intelligent routing engine, COD fraud scoring, BNPL integration

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Intelligent 3PL routing engine (score + rank) | Order tracking UI with delivery status timeline | Pathao Courier REST API: quote + book + track | 3PL failover test (simulate primary rejection) |
| 2 | Auto-failover to backup 3PL on rejection | 3PL partner comparison UI (cost + ETA) | RedX API: same + COD reconciliation webhook | COD fraud scoring unit tests |
| 3 | COD fraud scoring algorithm (0–100 score) | COD fraud warning UI for high-risk orders | Paperfly API: sub-district routing + tracking | BNPL flow integration tests |
| 4 | COD history score (per buyer, grows over time) | BNPL installment option at checkout UI | Steadfast API: bulk rate negotiation | k6 load test scripts setup (10K concurrent) |
| 5 | COD-to-digital ৳20 discount incentive system | — | eCourier API: same-day Dhaka delivery | Preliminary load test run + bottleneck report |
| 6 | — | — | BNPL: ShopUp and/or IDLC Capital EMI integration | Vendor acquisition: target frustrated Daraz sellers |
| 7 | — | — | VAT computation module (15% auto on txns) | — |

---

### Month 12 — POS Mode & Mobile App

> **Goal:** POS PWA (barcode + Bangla QR), React Native MVP, Referral system, Advanced Analytics

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | POS mode backend: barcode → inventory → sale | POS mode PWA UI: barcode scanner (camera API) | VAT monthly report generator (vendor-facing) | POS offline sync tests + barcode scanner tests |
| 2 | POS offline queue + sync on reconnect | POS UI: item list, total, Bangla QR accept | Finance Admin dashboard APIs (escrow, disbursement) | React Native app on Android + iOS (Expo Go) |
| 3 | Referral/affiliate system backend + commission | POS offline sync indicator + queue display | BNPL post-launch support + edge case handling | Advanced analytics dashboard validation |
| 4 | Advanced analytics API endpoints | React Native: browse, search, product detail, buy | Monthly VAT record storage + `vat_records` table | Gate 4 report: 500 vendors + ৳350K revenue? |
| 5 | — | React Native: in-app chat, order tracking | — | Record PRISM Academy: POS mode tutorial |
| 6 | — | React Native: short-form video feed | — | ৳20 COD-to-digital incentive field test with vendors |
| 7 | — | React Native: vendor dashboard (basic) | — | — |
| 8 | — | Referral link share UI + reward history | — | — |
| 9 | — | Advanced analytics dashboard with date range picker | — | — |

---

## PHASE 6 — Polish, Launch & Scale (Months 13–15)

---

### Month 13 — Security Audit & Performance

> **Goal:** OWASP ZAP pentest, k6 10K load test passed, WCAG 2.2 AA, content moderation tools, VAT reports ready

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Full OWASP ZAP scan on all API endpoints | WCAG 2.2 AA audit: contrast, keyboard nav, ARIA | Escrow edge case audit (dispute timeout, partial) | Run full k6 load test suite → document results |
| 2 | Manual pentest: JWT attacks, RLS bypass, payment replay | Fix all accessibility failures found in audit | Payment gateway stress test (simulated failures) | Run OWASP ZAP security scan → triage findings |
| 3 | Fix all critical/high security findings | Content moderation review UI (product queue) | Verify Bangla QR full compliance before June 2026 | Assist manual pentest (payment replay attempts) |
| 4 | k6 load optimization to <200ms p95 @ 10K concurrent | Admin review flagging + takedown controls | VAT reporting final implementation + test reports | Run all 8 Playwright E2E flows → 100% pass |
| 5 | API versioning + schema governance docs | PRISM Academy remaining modules UI | Finance Admin dashboard: escrow + disbursement | Confirm all integration test suites pass |
| 6 | Production VPS: Hetzner/DigitalOcean + Cloudflare | Fix all UI bugs from pre-beta internal testing | — | Content moderation backend integration tests |

---

### Month 14 — Beta Launch (50 Vendors)

> **Goal:** 50 Dhaka vendors onboarded in beta, real orders flowing, bug fixes from feedback, performance tuning

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Monitor production metrics (Grafana dashboards) | Fix UI/UX bugs from beta vendor feedback | Handle 3PL issues from real beta orders | Onboard and hand-hold all 50 beta vendors |
| 2 | Fix critical backend bugs from beta feedback | Optimize onboarding flow (reduce drop-off) | Fix payment edge cases (refunds, partial pays) | Daily: collect feedback via WhatsApp + form |
| 3 | Performance tune based on real traffic patterns | Polish mobile experience (PWA + React Native) | Escrow dispute resolution for any beta disputes | Compile prioritized bug list for the team |
| 4 | Scale VPS resources as needed | Improve Bengali font rendering edge cases | Monitor WhatsApp template delivery rates | Record vendor success stories for marketing |
| 5 | Handle any payment webhook failures in prod | Add missing loading states / error messages | — | Finalize all PRISM Academy 10 videos |
| 6 | — | — | — | Build vendor WhatsApp community group |

---

### Month 15 — Public Launch (Dhaka)

> **Goal:** Public launch in Dhaka · Target: 500 vendors, ৳500K+ monthly revenue · Marketing sprint · Scale to Chattogram + Sylhet

| # | **Sagar** | **Member B** | **Member C** | **Member D** |
|---|---|---|---|---|
| 1 | Public launch: scale infrastructure for real traffic | Launch marketing landing page (prism.com.bd) | Handle all payment and logistics ops on launch day | Vendor acquisition sprint: target 500 vendors total |
| 2 | Monitor all systems 24/7 during launch week | Create social media visuals (Facebook + TikTok) | Monitor escrow + disbursement queues | Field sales in Dhaka (Chawkbazar, Mirpur, Uttara, Gulshan) |
| 3 | Prepare investor technical materials (if applicable) | Record PRISM demo video for ads | Set up ops runbook for common issues | Facebook Group + TikTok content marketing push |
| 4 | Architect plan for Chattogram + Sylhet expansion | Final polish pass on all UI after beta learnings | Begin Chattogram 3PL partnership outreach | PRISM Academy launch on YouTube |
| 5 | Document K8s migration path for Phase 3 scale | — | — | Gate 5 report: public launch metrics dashboard |
| 6 | — | — | — | Prepare Seed round pitch materials (if applicable) |

---

## Section 4 — Milestones, Revenue Gates & Key Decisions

These are the 5 **"Go / No-Go"** gates from the PRISM V4 plan. At each gate, the team evaluates whether the project is on track. If the milestone is not met, the team **pivots strategy before spending more time**.

### Revenue Gates

| Gate | Month | Target | Decision If Missed |
|---|---|---|---|
| **Gate 1** | Month 4 | 20 vendors actively using the platform | Pivot acquisition strategy — try different market or channel |
| **Gate 2** | Month 6 | First ৳50,000 revenue month (commissions + subscriptions) | Re-evaluate pricing; consider launching on more Dhaka markets |
| **Gate 3** | Month 9 | 100 vendors, ৳150,000 revenue month — product-market fit signal | Evaluate whether AI features are resonating; simplify if needed |
| **Gate 4** | Month 12 | 500 vendors, ৳350,000 revenue month — decide: self-fund vs. raise | Either pivot to a narrower niche OR seek angel investment |
| **Gate 5** | Month 15 | Public launch, ৳500,000+ monthly revenue, profitable unit economics | Decide Seed round path OR extend self-funding runway |

---

### Monthly Revenue Projections

These are the realistic projections from the PRISM V4 financial model. The team should **track actual vs. projected every month**.

| Period | Cumulative Cost (৳) | Cumulative Revenue (৳) | Net Position |
|---|---|---|---|
| Month 3 | ৳27,000 | ৳22,300 | −৳4,700 |
| Month 6 | ৳2,73,000 | ৳1,13,550 | −৳1,59,450 |
| Month 12 | ৳15,39,000 | ৳7,35,000 | −৳8,04,000 |
| Month 15 | ৳25,74,000 | ৳18,50,000 | −৳7,24,000 |
| **Month 18** *(post-launch scale)* | ৳36,09,000 | ৳42,60,000 | **+৳6,51,000 ✅ Break-even** |

---

### Phase-by-Phase Cost Summary (4-Member Student Team)

Since we are four students building without salaries, the main costs are **infrastructure and tools**. The original plan assumed a solo founder + part-time hires; this table adjusts for a 4-person volunteer team.

| Phase | Period | Monthly Infra Cost | Total Cost | Note |
|---|---|---|---|---|
| Phase 1–2 | Months 1–3 | ৳6,000 (~$50) | ৳18,000 | Hetzner VPS + Cloudflare free tier |
| Phase 3–4 | Months 4–6 | ৳12,000 (~$100) | ৳36,000 | Redis Cloud / bigger VPS + Ollama on VPS |
| Phase 5 | Months 7–12 | ৳18,000 (~$150) | ৳1,08,000 | Read replica + MinIO/R2 for media storage |
| Phase 6 | Months 13–15 | ৳30,000 (~$250) | ৳90,000 | Production scale + CDN + monitoring |
| **TOTAL** | **15 Months** | — | **~৳2,52,000** | **~$2,100 USD — ~$525/person split 4 ways** |

---

## Section 5 — Collaboration, Git Workflow & Team Rules

Four developers working on the same codebase need clear rules to avoid stepping on each other. These guidelines will save dozens of hours of painful merge conflicts and miscommunication.

---

### 5.1 Git Branch Strategy

| Branch | Owner | Purpose |
|---|---|---|
| `main` | **Sagar (gatekeeper)** | Production-ready code only. Never commit directly. Always via PR. |
| `develop` | **Shared** | Integration branch. All feature branches merge here first. CI/CD runs here. |
| `feature/sagar/*` | Sagar | AI modules, backend core, DevOps. e.g. `feature/sagar/onnx-gbr-model` |
| `feature/memberb/*` | Member B | Frontend, React Native. e.g. `feature/memberb/reel-feed-ui` |
| `feature/memberc/*` | Member C | Payments, logistics, compliance. e.g. `feature/memberc/bkash-webhook` |
| `feature/memberd/*` | Member D | Tests, Academy. e.g. `feature/memberd/e2e-checkout-flow` |
| `hotfix/*` | Any | Critical production bugs only. PR → `main` → back-merge to `develop`. |

---

### 5.2 Pull Request Rules

Every PR **must** follow these rules before it can be merged into `develop` or `main`:

- **Minimum 1 reviewer approval** required (prefer 2 for payment-related code)
- **All CI checks must pass:** lint (ESLint), TypeScript compile, unit tests, integration tests
- **PR description must include:** What changed · Why · How to test · Screenshots (for UI changes)
- **No PR larger than 450 lines** of code changes — break large features into smaller PRs
- **Payment and escrow code** requires Sagar AND Member C to both approve before merge
- **Security-sensitive code** (auth, RLS, webhook verification) requires Sagar to approve
- Delete feature branch after merging — keep the repo clean
- **Do not merge your own PR** — have someone else merge it

---

### 5.3 Weekly Team Routine

| Day / Time | Activity | Duration | Who Leads |
|---|---|---|---|
| **Sunday 9pm** | Weekly sync: progress, blockers, plan for the week | 45 min | Rotating (each week a different member) |
| **Wednesday 9pm** | Mid-week check-in: any blockers? PR reviews due? | 20 min | Sagar (keeps it short) |
| **End of month** | Monthly retrospective: what worked, what to improve | 60 min | All four — equal voice |
| **Anytime** | Blocker? Post in team WhatsApp group immediately. 24h response SLA. | Async | Anyone can ask; anyone can help |

---

### 5.4 Decision-Making Protocol

Not every decision needs a meeting. Use this tiered approach to avoid analysis paralysis:

| Decision Type | Who Decides | Process |
|---|---|---|
| My own domain, small change | **You decide alone** | Just do it. Mention in next sync. |
| My domain, significant change | **You + your reviewer** | Post in WhatsApp. If no objection in 24h, proceed. |
| Cross-domain (affects 2+ people) | **Affected members** | Short call or WhatsApp thread. Majority rules. |
| Architecture change (DB schema, new service) | **Sagar has final say** | Sagar proposes → team reviews → Sagar decides |
| Business decision (pricing, launch timing) | **All 4 equally** | Vote. 3/4 majority needed. If 2–2, delay 1 week. |
| Equity / team membership change | **All 4 equally — unanimous** | Unanimous vote only. Document in writing. |

---

### 5.5 Shared Tools & Access

| Tool | Purpose | Who Has Access |
|---|---|---|
| **GitHub** (private repo) | Source code, PRs, CI/CD | All 4 — Sagar is admin |
| **Notion** | Task board, meeting notes, decisions | All 4 — Member D manages |
| **WhatsApp Group** | Daily communication | All 4 |
| **Figma** (free) | UI designs, wireframes | Member B primary, all can view |
| **Postman / Insomnia** | API testing during development | All 4 |
| **Hetzner VPS** | Production + staging server | Sagar primary, Member C co-admin |
| **Cloudflare** | CDN, DNS, WAF | Sagar primary |
| **bKash / Nagad merchant** | Production payment accounts | Member C + Sagar (financial admin) |
| **Google Analytics / PostHog** | User analytics | All 4 — Member D manages dashboards |
| **PRISM social media accounts** | Facebook, TikTok, YouTube | Member D primary, Member B for design assets |

---

> **Good luck to the PRISM Commerce team. We are building something genuinely new for Bangladesh. Ship it.**

---

*PRISM Commerce Team Plan v1.0 · April 2026 | Document prepared for 4-person CSE student founding team*
