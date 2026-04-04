# 🚀 PRISM Commerce — V4.0 (Production-Grade Startup Edition)
## Predictive Retail Intelligence & Stock Management

> **Type:** Production-Grade Startup Business Plan & Technical Architecture  
> **Version:** 4.0 (Competitive Platform — Regulatory-Compliant, AI-Agentic, Market-Ready)  
> **Date:** April 2026  
> **Author:** Sagar Biswas  
> **Mission:** Build Bangladesh's first Bangla-native, AI-agentic, live commerce-enabled multi-vendor marketplace with regulatory compliance and marketplace trust infrastructure

---

```
Stack:    Next.js 15 · NestJS · PostgreSQL 16 · Redis 7 · ONNX GBR · Docker
AI:       11 REST Engines + 1 ONNX GBR Model + Agentic GenAI Assistant (LLM) + RAG Search
          + Opportunity Engine + Bundle Recommender
V4 New:   Agentic Commerce · Bangla QR · Escrow System · PRISM Verified · PRISM Protect
          Opportunity Engine · Short-Form Video · POS Mode · TikTok Shop · PRISM Academy
          CQRS + Event Sourcing · Voice Commands · Flash Sales · COD Intelligence
V3 Core:  Live Commerce · Social Commerce · GenAI Sahayak · PRISM Wallet · BNPL
          3PL Logistics · Multi-Tenant SaaS · In-App Chat · Influencer System
Local:    Bengali (বাংলা) · Festival Intelligence · Weather-Aware · bKash/Nagad/SSLCommerz/Bangla QR
```

---

## 📋 Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Market Analysis & Opportunity (2026)](#2-market-analysis--opportunity-2026)
3. [Competitive Landscape — 12-Dimension Analysis](#3-competitive-landscape--12-dimension-analysis)
4. [Problem Statement — 12 Core Failure Modes](#4-problem-statement--12-core-failure-modes)
5. [Unique Value Proposition — 22 Differentiators](#5-unique-value-proposition--22-differentiators)
6. [Business Model & Monetization](#6-business-model--monetization)
7. [User Architecture — 8 Roles](#7-user-architecture--8-roles)
8. [System Architecture — V4](#8-system-architecture--v4)
9. [Core Feature Set](#9-core-feature-set)
10. [AI Intelligence Layer — 15 Modules](#10-ai-intelligence-layer--15-modules)
11. [New Strategic Modules (A–L)](#11-new-strategic-modules-al)
12. [Bangladesh-Native Integrations](#12-bangladesh-native-integrations)
13. [Technology Stack — V4](#13-technology-stack--v4)
14. [Database Schema](#14-database-schema)
15. [Key API Endpoints](#15-key-api-endpoints)
16. [UI Wireframes & Screens](#16-ui-wireframes--screens)
17. [Security Architecture](#17-security-architecture)
18. [Performance & Observability](#18-performance--observability)
19. [Regulatory & Legal Compliance](#19-regulatory--legal-compliance)
20. [Development Roadmap — 15-Month Plan](#20-development-roadmap--15-month-plan)
21. [Team & Hiring Plan](#21-team--hiring-plan)
22. [Risk Register & Mitigation](#22-risk-register--mitigation)
23. [Novelty & Emergence Argument](#23-novelty--emergence-argument)
24. [Testing Strategy](#24-testing-strategy)
25. [Accessibility & Inclusivity](#25-accessibility--inclusivity)
26. [Financial Projections (Realistic)](#26-financial-projections-realistic)
27. [Investor Pitch Summary (Optional Path)](#27-investor-pitch-summary-optional-path)
28. [Self-Funding Viability Plan](#28-self-funding-viability-plan)
29. [Growth Playbook](#29-growth-playbook)
30. [Glossary](#30-glossary)
31. [Diagram Clarification Spec (Batch A: IDs 1-11)](#31-diagram-clarification-spec-batch-a-ids-1-11)
32. [Diagram Clarification Spec (Batch B: IDs 12-22)](#32-diagram-clarification-spec-batch-b-ids-12-22)
33. [Diagram Clarification Spec (Batch C: IDs 23-34)](#33-diagram-clarification-spec-batch-c-ids-23-34)
34. [Diagram Clarification Spec (Batch D: IDs 35-45)](#34-diagram-clarification-spec-batch-d-ids-35-45)
35. [Diagram Clarification Spec (Batch E: IDs 46-56)](#35-diagram-clarification-spec-batch-e-ids-46-56)
36. [Diagram Clarification Spec (Batch F: IDs 57-67)](#36-diagram-clarification-spec-batch-f-ids-57-67)
37. [Diagram Clarification Spec (Batch G: IDs 68-75)](#37-diagram-clarification-spec-batch-g-ids-68-75)
38. [Diagram Clarification Spec (Batch H: IDs 76-84)](#38-diagram-clarification-spec-batch-h-ids-76-84)

---

## 1. Executive Summary

PRISM Commerce is a **Predictive Retail Intelligence and Stock Management** platform that unifies e-commerce operations with an AI-driven inventory intelligence layer, an agentic GenAI shopping assistant, live commerce, social commerce, short-form video commerce, and marketplace trust infrastructure — purpose-built for the Bangladeshi market as a production-grade startup platform with full regulatory compliance.

### The Vision

> Build the platform that makes Daraz, Shopify, and Netstock unnecessary for Bangladeshi SMEs — by combining Daraz's marketplace reach, Shopify's SaaS power, Netstock's forecasting intelligence, sManager's offline POS capability, and the local relevance that none of them have — with an agentic AI layer that can execute actions autonomously for vendors and buyers.

### Who is it for?

**Primary:** Small-to-mid-scale businesses (SMEs) in Bangladesh — the 8 million+ micro-merchants who currently rely on intuition, spreadsheets, Facebook pages, or nothing at all to manage their inventory and sales.

**Secondary:** Buyers across Bangladesh who want a trusted, Bangla-first shopping experience with AI-powered discovery, live commerce, short-form video shopping, and modern payment options including Bangla QR.

> **Real-world analogy:** Imagine a shop owner in Chawkbazar who sells fabric. Every year before Eid, she guesses how much to buy. With PRISM, she gets a WhatsApp alert in Bangla saying "আপু, আগামী ১৪ দিনে তোমার লাল শাড়ি ৫০ পিস শেষ হবে, এখনই অর্ডার দাও!" — powered by AI that learns from her sales, the entire fabric market on PRISM, the weather forecast, and the festival calendar. She can also go LIVE on the platform, create 60-second shoppable reels, chat with buyers directly, accept Bangla QR payments at her physical shop, and get paid instantly via bKash — all protected by PRISM Protect buyer guarantee and escrow.

### What makes V4 a production platform, not a project?

| Dimension | V3 (Startup Plan) | V4 (Production Platform) |
|---|---|---|
| Revenue Model | Hybrid SaaS + Commission | Hybrid SaaS + Commission + **5-tier pricing** |
| Scale Target | 10K+ vendors, 1M+ users | Same, with **realistic 15-month ramp** |
| AI Depth | GBR + GenAI Assistant + RAG | GBR + **Agentic AI** + RAG + **Opportunity Engine** + **Bundle AI** |
| Commerce | Live Commerce + Social | Live + Social + **Short-Form Video** + **TikTok Shop** + **YouTube Shopping** |
| Payments | bKash + Nagad + SSLCommerz | + **Bangla QR** + **Escrow** + Rocket + EMI |
| Trust | VPS score only | **PRISM Verified** + **PRISM Protect** + **Brand Stores** + **Escrow** |
| Logistics | 3PL integration | **Intelligent routing** + **COD fraud scoring** + **warehouse partnerships** |
| Compliance | Partial | **Full: Escrow, Bangla QR, VAT, BTRC, Trade License** |
| Offline | None | **POS Mode** for physical stores |
| Architecture | Modular monolith | Modular monolith + **CQRS** + **Event Sourcing** + **Distributed Tracing** |
| Timeline | 12 months (aggressive) | **15 months (realistic)** |
| Funding | External only | **Self-funding viable** + optional external |

### At a Glance

| Dimension | Detail |
|---|---|
| Category | AI-Agentic Multi-Vendor E-Commerce Marketplace + SaaS |
| Stack | Next.js 15, NestJS, PostgreSQL 16, Redis 7, ONNX, Docker |
| Target Market | Bangladesh (~$8B+ e-commerce market, 75%+ mobile-first) |
| User Roles | 8: Super Admin, Vendor, Buyer, Support, Delivery, Affiliate, Finance Admin, **Content Moderator** |
| AI Modules | 15 total: 11 REST + 1 ONNX GBR + Agentic GenAI + RAG + **Opportunity Engine** + **Bundle AI** |
| Monetization | 5-tier SaaS + transaction commission + promoted listings + wallet + BNPL + flash sales |
| Language | English + Bengali (বাংলা) — GenAI assistant speaks Bangla + **voice commands** |
| Key Integrations | WhatsApp, bKash, Nagad, SSLCommerz, **Bangla QR**, OpenWeatherMap, Facebook, **TikTok Shop**, 3PL partners |
| Architecture | Modular monolith with CQRS + Event Sourcing → microservices-ready, Docker-containerized |
| Trust | PRISM Verified (3-tier) + PRISM Protect (buyer guarantee) + Escrow + Brand Stores |
| Launch Strategy | Dhaka → Chattogram → Sylhet → nationwide within 12 months of launch |

---

## 2. Market Analysis & Opportunity (2026)

### 2.1 Bangladesh E-Commerce Market (2026–2030)

| Metric | Value | Source |
|---|---|---|
| Market Size (2026) | ~US $8.0–9.0 billion | Research & Markets, Trade.gov |
| Projected Size (2030) | ~US $12–18 billion | Multiple analysts |
| CAGR | 12%–18% | Range across analyst estimates |
| Mobile-Driven Volume | 75%+ | GSMA, BTRC |
| bKash Registered Accounts | 70M+ | bKash official |
| Nagad Registered Accounts | 25M+ | Nagad official |
| Internet Users | 135M+ | BTRC |
| Smartphone Penetration | 60%+ (growing) | GSMA |
| Digital Payment Adoption | 60%+ of online purchases | Industry surveys |
| Cash-on-Delivery Preference | ~60-70% of orders (declining) | Industry surveys |
| WhatsApp Users in BD | 48M+ | Meta |
| TikTok Users in BD | 35M+ (rapidly growing) | TikTok |
| Bangla QR Mandate | June 2026 | Bangladesh Bank |

### 2.2 The 2026 Opportunity Gap

```
┌──────────────────────────────────────────────────────────────────────┐
│                THE BANGLADESH E-COMMERCE GAP (2026)                  │
│                                                                      │
│  ┌─── Established Players ──┐   ┌─── The Gap ────────────────────┐   │
│  │ Daraz (Alibaba)          │   │                                │   │
│  │ • Has DarazLive + DEX    │   │  NO PLATFORM IN BANGLADESH     │   │
│  │ • Has DarazMall trust    │   │  COMBINES:                     │   │
│  │ • No AI for vendors      │   │                                │   │
│  │ • High commission 8-15%  │   │  ✗ Agentic AI assistant        │   │
│  │ • English-centric        │   │  ✗ Bangla-first + voice        │   │
│  │                          │   │  ✗ Predictive inventory        │   │
│  │ Shopify                  │   │  ✗ Festival intelligence       │   │
│  │ • Sidekick (English)     │   │  ✗ Escrow + buyer protection   │   │
│  │ • No BD payments         │   │  ✗ Short-form video commerce   │   │
│  │ • $29+/mo (too expensive)│   │  ✗ POS for physical stores     │   │
│  │                          │   │  ✗ Bangla QR compliance        │   │
│  │ sManager                 │   │  ✗ Cross-vendor intelligence   │   │
│  │ • Has POS                │   │  ✗ Affordable SaaS pricing     │   │
│  │ • No AI, no marketplace  │   │                                │   │
│  │                          │   │  PRISM V4 FILLS THIS GAP       │   │
│  └──────────────────────────┘   └────────────────────────────────┘   │
└──────────────────────────────────────────────────────────────────────┘
```

### 2.3 Target Customer Segments

| Segment | Size | Pain Points | PRISM V4 Value Prop |
|---|---|---|---|
| **Facebook Sellers** | 300K+ active | No inventory, no analytics, manual payments | Full platform + AI + Bangla QR + POS |
| **Small Shop Owners** | 3M+ (estimated) | Guesswork on stock, no digital tools | Bangla AI + WhatsApp + POS mode + voice commands |
| **Daraz Sellers** | 100K+ | High commission (8-15%), poor tools | Lower commission (2-5%) + AI + better tools |
| **Shopify Users (BD)** | 5K+ | Expensive, no bKash/Nagad, no Bangla | ৳500/mo with full BD integration + AI |
| **New Entrepreneurs** | Growing rapidly | Don't know where to start | Free tier + PRISM Academy + AI onboarding |
| **TikTok/Social Sellers** | 50K+ (growing) | No proper checkout, no inventory tracking | TikTok Shop sync + short-form video + PRISM checkout |

### 2.4 Competitive Moats (Defensibility) — 7 Moats

1. **Data Network Effect:** More vendors → better cross-vendor intelligence → better forecasts → attracts more vendors
2. **Bangla AI Moat:** First Bangla-native agentic GenAI commerce assistant — extremely hard for foreign platforms to replicate
3. **Festival Intelligence IP:** Proprietary database of Bangladesh festival-demand correlations refined over time
4. **Vendor Lock-in Through Value:** AI gets smarter with vendor's own data — switching costs increase naturally
5. **Local Payment Depth:** bKash + Nagad + SSLCommerz + Bangla QR + Wallet + BNPL — full BD payment stack
6. **Regulatory Compliance Moat (NEW):** Full escrow + Bangla QR + VAT — barriers foreign platforms won't invest in
7. **Content Network Effect (NEW):** Short-form video content + live streams create a discovery engine that grows with each vendor

---

## 3. Competitive Landscape — 12-Dimension Analysis

### 3.1 Head-to-Head Matrix

| Dimension | Daraz | Shopify (2026) | Netstock | sManager | Chaldal | **PRISM V4** |
|---|---|---|---|---|---|---|
| **AI Forecasting** | ❌ None for sellers | ❌ None native | ✅ Pivot Forecasting® | ❌ None | Internal only | ✅ GBR + Opportunity Engine |
| **GenAI Assistant** | ❌ None | ✅ Sidekick (EN, agentic) | ❌ None | ❌ None | ❌ None | ✅ Sahayak (BN+EN, agentic) |
| **Live Commerce** | ✅ DarazLive | ❌ None | N/A | N/A | N/A | ✅ PRISM Live + Short-Form Video |
| **Social Commerce** | Facebook only | ✅ Omnichannel | N/A | N/A | N/A | ✅ FB + WhatsApp + TikTok + YouTube |
| **Logistics** | ✅ DEX (in-house) + DigiBox | ❌ None | N/A | N/A | ✅ Micro-warehouses | ✅ Smart 3PL + COD intelligence |
| **Payments** | Wallet + BNPL | Stripe (no BD) | N/A | Digital payments | ChaldalPay | ✅ Full stack + Bangla QR + Escrow |
| **Trust/Brand** | ✅ DarazMall (3x cashback) | Shop Promise | N/A | N/A | N/A | ✅ Verified + Protect + Brand Stores |
| **Seller Tools** | SellerApp + DMS + University | Full admin + Sidekick | ERP integration | ✅ POS + inventory | N/A | ✅ Dashboard + Academy + POS |
| **Pricing (for BD)** | Free (commission-only) | $29-399/mo | $1000+/mo | Low-cost SaaS | N/A | ✅ ৳0-5,000/mo |
| **Bangla-First** | ❌ English-centric | ❌ No Bangla | ❌ English | ✅ Bangla | ✅ Bangla | ✅ Full Bangla + voice |
| **Agentic Commerce** | ❌ None | ✅ MCP + Storefronts | ❌ None | ❌ None | ❌ None | ✅ Agentic Sahayak + Open API |
| **Regulatory** | ✅ Compliant | ❌ No BD awareness | ❌ N/A | ✅ BD-compliant | ✅ Compliant | ✅ Full compliance |

### 3.2 Daraz Bangladesh (Alibaba Group)

**What they do well:**
- Massive scale (millions of products, hundreds of thousands of sellers)
- DarazLive (live streaming commerce with flash vouchers)
- Own logistics (DEX with IoT DigiBox for automated parcel storage)
- DarazMall (3x cashback guarantee for verified brands, 1,500+ brands)
- "Choice" channel (4,000+ curated products, single-warehouse model, 30% faster delivery)
- Daraz Marketing Solutions (DMS) with AI-driven marketing
- Daraz University for seller training
- Backed by Alibaba Cloud infrastructure

**Where they fail (PRISM's opportunity):**
- ❌ No AI demand forecasting for individual vendors
- ❌ No festival-aware inventory intelligence
- ❌ No weather-aware demand signals
- ❌ High commissions (8–15%) squeeze small vendors
- ❌ English-centric admin interface
- ❌ No cross-vendor collective intelligence
- ❌ No Bangla AI assistant
- ❌ No short-form video commerce (separate from DarazLive)
- ❌ No POS for physical stores

### 3.3 Shopify (2026)

**What they do well:**
- Sidekick (agentic AI — can execute actions, generate tools, "Pulse" insights)
- Shopify Magic (brand voice cloning, AI image editing)
- Hydrogen + Oxygen (headless React framework + hosting)
- Agentic Storefronts (products discoverable in ChatGPT, Copilot, Perplexity)
- Storefront MCP (Model Context Protocol for custom AI agents)
- Checkout Extensibility (Shopify Functions)
- Omnichannel analytics (online + social + POS unified)

**Where they fail for Bangladesh:**
- ❌ Expensive: $29–$399/month (৳3,500–৳47,000/month — unaffordable for BD SMEs)
- ❌ No bKash, Nagad, or Bangla QR
- ❌ No Bangla AI or festival features
- ❌ No understanding of BD market dynamics
- ❌ No WhatsApp Business integration (native)
- ❌ No monsoon/weather-aware forecasting
- ❌ No cross-vendor intelligence (isolated stores)
- ❌ No escrow (not required in their markets)

### 3.4 Netstock

**What they do well:**
- Pivot Forecasting® (AI demand planning with seasonality + trends)
- Opportunity Engine™ (real-time risk/opportunity identification every 90 seconds)
- Automated SKU classification
- Dynamic safety stock adjustment
- Supplier performance analysis
- ERP integration (SAP, NetSuite)
- Scalable subscription bundles (Essential, Advanced, Commercial)

**Where they fail:**
- ❌ No commerce layer (inventory only, no storefront)
- ❌ Enterprise pricing ($1,000+/month)
- ❌ English only
- ❌ No Bangladesh-specific features
- ❌ No mobile-first design for SMEs

### 3.5 Sheba.xyz / sManager

**What they do well:**
- sManager SaaS for SME operations (POS, inventory, accounting, order processing)
- Online store creation within minutes
- Digital payment links
- Loan access for small businesses (financial inclusion)
- Credit/ledger management (*baki* tracking)
- Three-app ecosystem (Sheba.xyz + sManager + sBusiness)
- Bangla-native interface

**Where they fail:**
- ❌ Services-focused (limited product commerce)
- ❌ No AI or predictive intelligence
- ❌ No demand forecasting
- ❌ No live commerce or social commerce
- ❌ No marketplace (single-vendor stores)

### 3.6 Chaldal

**What they do well:**
- AI demand forecasting for grocery
- Micro-warehouse network for 1-hour delivery
- Route optimization; ChaldalPay digital wallet
- Vertical integration (Vegetable Network, BanglaMeds)

**Where they fail:**
- ❌ Grocery-only, no multi-vendor
- ❌ Severe financial struggles (2025 layoffs, liquidity crisis)
- ❌ Too capital-intensive model

**Lesson:** PRISM's 3PL partnership model is leaner and more scalable than Chaldal's owned infrastructure.

---

## 4. Problem Statement — 12 Core Failure Modes

| # | Problem | Real-World Impact | Who Suffers | PRISM V4 Solution |
|---|---|---|---|---|
| **P1** | **Stock Loss** | Overstocking ties up capital. Stockouts during Eid kill revenue. | Vendors | GBR forecasting + smart reorder + **Opportunity Engine** |
| **P2** | **Fragmented Operations** | Orders, inventory, analytics in separate tools (or vendor's head). | Vendors, Admins | Unified platform — one login, everything connected |
| **P3** | **Zero Foresight** | Vendors react *after* problems. No proactive alerts. | Vendors | AI forecast + WhatsApp alerts + What-If planner |
| **P4** | **Language Barrier** | Existing tools are English-only. Excludes 80% of BD vendors. | Vendors, Buyers | Bangla UI + Bangla AI + WhatsApp + **voice commands** |
| **P5** | **Festival Blindness** | No tool accounts for Eid/Puja/Boishakh demand surges. | Vendors | Festival Intelligence Calendar with 14-day alerts |
| **P6** | **Weather Ignorance** | Monsoon shifts demand. No tool factors this. | Vendors | Weather-aware demand signals via OpenWeatherMap |
| **P7** | **Delivery Opacity** | No visibility into where orders are. | Buyers, Vendors | 3PL integration + **intelligent routing** + tracking |
| **P8** | **No Revenue Infrastructure** | SMEs on Facebook have no payment, no invoice, no tax. | Vendors | Wallet + bKash/Nagad + **Bangla QR** + auto-invoices |
| **P9** | **Social Commerce Disconnect** | 80% of BD discovery is on Facebook/TikTok. No bridge. | Vendors, Buyers | FB sync + WhatsApp Catalog + **TikTok Shop** + **reels** |
| **P10** | **No Affordable AI** | AI tools are enterprise-priced (Netstock: $1K+/mo). | Vendors | Free tier AI + ৳500/mo for full AI suite |
| **P11** | **No Buyer Trust (NEW)** | Fake products, no returns, no protection; buyers fear online purchase. | Buyers | **PRISM Verified** + **PRISM Protect** + **Escrow** |
| **P12** | **Regulatory Non-Compliance (NEW)** | Platforms without escrow/Bangla QR face shutdown risk. | Platform, All | **Full compliance**: Escrow, Bangla QR, VAT, Trade License |

---

## 5. Unique Value Proposition — 22 Differentiators

> **Core Thesis:**
> Most commerce platforms tell you **what happened.**
> PRISM tells you **what is about to happen** — and exactly what to do about it.
> Then it **does it for you** via agentic AI — sells it live, chats with buyers, and gets paid instantly — all in Bangla.
>
> Predictive inventory intelligence + agentic AI assistant + live commerce + short-form video + social commerce +
> marketplace trust infrastructure + regulatory compliance,
> unified under a single Bangla-first mobile platform — with weather-awareness, festival intelligence,
> cross-vendor collective learning, and a SaaS model priced for Bangladeshi SMEs.

### Differentiators:

1. **GBR Demand Forecasting per SKU** — ONNX GBR predicts sales for 7, 14, and 30 days with 13 features.
2. **Smart Reorder Point Engine** — Alerts *before* stockout with festival + weather multipliers.
3. **Bangladesh Festival Intelligence Calendar** — Eid, Puja, Boishakh with 14-day pre-surge window.
4. **Bengali (বাংলা) Language Support** — Full UI, WhatsApp, GenAI, **voice commands**.
5. **Cross-Vendor Category Emergence** — Collective intelligence across all vendors.
6. **Agentic GenAI Assistant "PRISM Sahayak V2" (NEW V4)** — Can execute actions: add to cart, apply coupons, complete checkout, set discounts — not just advise.
7. **RAG Semantic Product Search** — pgvector embeddings for natural language Bangla search.
8. **Live Commerce Engine** — WebRTC live streaming with shoppable video.
9. **Short-Form Video Commerce (NEW V4)** — TikTok-style 60-second shoppable reels.
10. **Social Commerce Bridge** — FB Shops + WhatsApp + **TikTok Shop** + **YouTube Shopping**.
11. **PRISM Wallet + BNPL** — Digital wallet, cashback, installments.
12. **3PL Logistics with Intelligent Routing (UPGRADED V4)** — Multi-factor routing + COD fraud scoring.
13. **In-App Buyer-Seller Chat** — Real-time messaging with AI auto-response.
14. **PRISM Verified Program (NEW V4)** — 3-tier vendor verification with badges.
15. **PRISM Protect (NEW V4)** — Buyer protection guarantee + dispute resolution + escrow.
16. **Opportunity Engine (NEW V4)** — Proactive pricing intelligence, 15-minute refresh cycle.
17. **POS Mode (NEW V4)** — Physical store point-of-sale with unified inventory.
18. **PRISM Academy (NEW V4)** — Bangla seller training with certification.
19. **Bangla QR Payments (NEW V4)** — National standardized QR for in-store + online.
20. **Escrow System (NEW V4)** — Payment held until delivery confirmed — regulatory compliant.
21. **Bangla Voice Commands (NEW V4)** — Voice-enabled search and vendor operations.
22. **Bundle Recommendation Engine (NEW V4)** — AI-suggested product bundles from co-purchase patterns.

---

## 6. Business Model & Monetization

### 6.1 Revenue Model — Hybrid SaaS + Commission + Value-Added Services

```
┌──────────────────────────────────────────────────────────────────────┐
│                    PRISM V4 REVENUE STREAMS                          │
│                                                                      │
│  ┌─── Recurring ──────────────┐   ┌─── Transactional ─────────────┐  │
│  │ SaaS Subscriptions         │   │ Commission per sale (2-5%)    │  │
│  │ (৳0 – ৳5,000+/mo)          │   │ Payment processing (1-1.5%)   │  │
│  │ 5 tiers (Free→Enterprise)  │   │ Logistics markup (৳5-20)      │  │
│  └────────────────────────────┘   └───────────────────────────────┘  │
│                                                                      │
│  ┌─── Advertising ────────────┐   ┌─── Financial ──────────────────┐ │
│  │ Promoted listings          │   │ Wallet float income            │ │
│  │ Live commerce slots        │   │ BNPL partner revenue share     │ │
│  │ Homepage featured spots    │   │ Escrow float (short-term)      │ │
│  │ Flash sale slots           │   │                                │ │
│  │ Short-form video boost     │   │                                │ │
│  └────────────────────────────┘   └────────────────────────────────┘ │
│                                                                      │
│  ┌─── Value-Added (NEW V4) ───┐                                      │
│  │ PRISM Academy courses      │                                      │
│  │ Brand Store hosting        │                                      │
│  │ API access (Pro+)          │                                      │
│  │ POS hardware partnership   │                                      │
│  └────────────────────────────┘                                      │
└──────────────────────────────────────────────────────────────────────┘
```

### 6.2 Pricing Tiers (5-Tier Model)

| Tier | Price (৳/mo) | Products | Commission | AI Features | Live Commerce | Trust | Support |
|---|---|---|---|---|---|---|---|
| **Free** | ৳0 | 5 | 5% | Basic forecast only, 3 AI queries/day | No | Basic badge | Community |
| **Starter** | ৳500 (~$4) | 50 | 4% | Full AI (11 modules), POS mode | 2 streams/mo | Verified Basic | Email |
| **Growth** | ৳2,000 (~$17) | 500 | 3% | Full AI + GenAI + What-If + Opportunity Engine | Unlimited | Verified Business | Priority Chat |
| **Pro (NEW)** | ৳5,000 (~$42) | Unlimited | 2.5% | Everything + API access + advanced analytics | Unlimited + priority | Verified Premium + Brand Store | Dedicated CSM |
| **Enterprise** | Custom | Unlimited | 2% | Everything + white-label + custom integrations | Unlimited | Full Brand Store | SLA guarantee |

> **Why this pricing works:** Shopify's cheapest plan is $29/mo (~৳3,500). PRISM Starter at ৳500/mo is **7x cheaper** with BD-specific features Shopify doesn't have. The new Pro tier at ৳5,000/mo captures mid-market vendors Shopify would otherwise attract, while still being cheaper than Shopify Basic.

### 6.3 Revenue Projections (Realistic — Self-Funding Path)

| Metric | Month 3 | Month 6 | Month 12 | Month 18 | Month 24 |
|---|---|---|---|---|---|
| Active Vendors | 50 | 150 | 500 | 1,500 | 4,000 |
| Paid Vendors (15-20%) | 8 | 25 | 75 | 300 | 800 |
| Avg. Subscription/mo | ৳600 | ৳650 | ৳700 | ৳900 | ৳1,100 |
| Subscription Revenue/mo | ৳4,800 | ৳16,250 | ৳52,500 | ৳270,000 | ৳880,000 |
| GMV/mo | ৳500,000 | ৳2,000,000 | ৳8,000,000 | ৳30,000,000 | ৳80,000,000 |
| Commission Revenue/mo (3.5% avg) | ৳17,500 | ৳70,000 | ৳280,000 | ৳1,050,000 | ৳2,800,000 |
| Ads + Other/mo | ৳0 | ৳5,000 | ৳40,000 | ৳150,000 | ৳400,000 |
| **Total Revenue/mo** | **৳22,300** | **৳91,250** | **৳372,500** | **৳1,470,000** | **৳4,080,000** |
| **Total Revenue/mo (USD)** | **~$187** | **~$767** | **~$3,130** | **~$12,350** | **~$34,300** |

### 6.4 Unit Economics (Realistic)

| Metric | Target | Rationale |
|---|---|---|
| Customer Acquisition Cost (CAC) | ৳800–1,500 per vendor | Field sales + digital marketing in BD |
| Lifetime Value (LTV) | ৳15,000–30,000 (18-month avg retention) | Conservative BD SME retention |
| LTV:CAC Ratio (Year 1) | 3:1 – 5:1 | Realistic for BD startup |
| LTV:CAC Ratio (Year 2) | 8:1 – 12:1 | As retention improves |
| Monthly Infrastructure Cost | ৳6,000–18,000 ($50–$150) initial | Docker + VPS + managed DBs |
| Break-Even (Infrastructure) | Month 4–5 | Covering server costs only |
| Break-Even (Full Cost) | Month 14–16 | Including team + marketing |
| Gross Margin | 65–80% (SaaS + commission) | Lower than V3's 70-85% due to escrow costs |

---

## 7. User Architecture — 8 Roles

PRISM V4 has **eight distinct user roles**, each with a tailored experience. V4 adds Content Moderator and Finance Admin for production scale.

| Capability | Super Admin | Vendor | Buyer | Support | Delivery | Affiliate | Finance Admin | Content Mod |
|---|---|---|---|---|---|---|---|---|
| Full platform visibility | ✅ | — | — | — | — | — | — | — |
| Browse & search products | — | — | ✅ | — | — | — | — | — |
| Manage product listings | — | ✅ | — | — | — | — | — | — |
| Handle support tickets | — | — | — | ✅ | — | — | — | — |
| Update delivery status | — | — | — | — | ✅ | — | — | — |
| Track affiliate earnings | — | — | — | — | — | ✅ | — | — |
| Manage finances / escrow | — | — | — | — | — | — | ✅ | — |
| Moderate content / reviews | — | — | — | — | — | — | — | ✅ |
| View GBR demand forecasts | — | ✅ | — | — | — | — | — | — |
| AI Sahayak assistant | — | ✅ | ✅ | — | — | — | — | — |
| Go Live (stream) | — | ✅ | — | — | — | — | — | — |
| Create short-form reels | — | ✅ | — | — | — | — | — | — |
| POS mode (physical sales) | — | ✅ | — | — | — | — | — | — |
| Checkout (bKash/Nagad/QR) | — | — | ✅ | — | — | — | — | — |
| WhatsApp alerts (EN/বাংলা) | — | ✅ | — | — | ✅ | — | — | — |
| Bangla voice commands | — | ✅ | ✅ | — | — | — | — | — |
| PRISM Academy access | — | ✅ | — | — | — | ✅ | — | — |
| Manage PRISM Verified | ✅ | — | — | ✅ | — | — | — | — |
| View PRISM Protect claims | — | — | — | ✅ | — | — | ✅ | — |
| Escrow management | — | — | — | — | — | — | ✅ | — |
| VAT / tax reports | — | — | — | — | — | — | ✅ | — |
| Vendor disbursements | — | — | — | — | — | — | ✅ | — |
| Review moderation | — | — | — | — | — | — | — | ✅ |
| Counterfeit reports | — | — | — | — | — | — | — | ✅ |
| Language toggle (EN/বাংলা) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |

---

## 8. System Architecture — V4

### 8.1 Architecture Overview

PRISM V4 uses a **Modular Monolith with CQRS, Event Sourcing, and Distributed Tracing** — designed for extraction to microservices when scale demands it.

```
┌──────────────────────────────────────────────────────────────────────────────┐
│                      PRISM COMMERCE SYSTEM (V4)                              │
├──────────────────────────────┬───────────────────────────────────────────────┤
│   Next.js 15 Frontend        │        NestJS Backend API                     │
│   (App Router + PPR + PWA)   │   (Modular Monolith + CQRS)                   │
│   shadcn/ui + Tailwind CSS   │                                               │
│   next-intl (EN + BN)        │  ┌────────────────────────────────────────┐   │
│   Recharts + Nivo            │  │  ONNX GBR ML Model                     │   │
│   Zustand (cart + offline)   │  │  (onnxruntime-node v1.17+)             │   │
│   React Native (Phase 2)     │  │  Inference < 80ms per product          │   │
│   Expo (mobile app)          │  │  Weather + Festival + Category inject  │   │
│                              │  └────────────────────────────────────────┘   │
│                              │                                               │
│  ┌─ Video Layer ──────────┐  │  ┌────────────────────────────────────────┐   │
│  │ LiveKit (WebRTC)       │  │  │  GenAI Gateway (Agentic)               │   │
│  │ HLS Recording          │  │  │  Ollama (Llama 3.2) — primary          │   │
│  │ Short-Form Reels       │  │  │  OpenAI GPT-4o — fallback              │   │
│  │ TikTok API sync        │  │  │  Function calling (tool-use)           │   │
│  └────────────────────────┘  │  │  RAG via pgvector + Meilisearch        │   │
│                              │  └────────────────────────────────────────┘   │
│                              │                                               │
│                              │  ┌─────────────────────────────────────────┐  │
│                              │  │  Event Bus & Background Jobs            │  │
│                              │  │  • BullMQ: Task queues (email, SMS)     │  │
│                              │  │  • Event Store: orders, payments, inv   │  │
│                              │  │  • CRON: forecast, velocity, weather    │  │
│                              │  │  • Saga: order fulfillment pipeline     │  │
│                              │  └─────────────────────────────────────────┘  │
│                              │                                               │
│                              │  ┌────────────────────────────────────────┐   │
│                              │  │  Trust & Compliance Engine (NEW V4)    │   │
│                              │  │  • Escrow manager                      │   │
│                              │  │  • PRISM Protect dispute resolver      │   │
│                              │  │  • KYC / verification pipeline         │   │
│                              │  │  • VAT computation + reporting         │   │
│                              │  └────────────────────────────────────────┘   │
└──────────────────────────────┴───────────────────────────────────────────────┘
          │                              │                    │
          │ HTTPS REST                   │ Prisma ORM         │ External APIs
          ▼                              ▼                    ▼
┌──────────────────┐         ┌─────────────────┐    ┌─────────────────────────┐
│  PostgreSQL 16   │         │ Redis 7         │    │  External Services      │
│  + pgvector      │         │ (Cache + Queues)│    │                         │
│  + Read Replica  │         │ Forecasts: 24h  │    │  • WhatsApp Cloud API   │
│  + Partitioned   │         │ Category: 1h    │    │  • bKash PGW            │
│  + Event Store   │         │ Weather: 6h     │    │  • Nagad PGW            │
│  RLS + PgBouncer │         │ Sessions: 15m   │    │  • SSLCommerz           │
│                  │         │ BullMQ queues   │    │  • Bangla QR (Banks)    │
│  Meilisearch     │         │                 │    │  • OpenWeatherMap       │
│  (Full-text +    │         └─────────────────┘    │  • LiveKit Cloud        │
│   Product search)│                                │  • TikTok Shop API      │
└──────────────────┘                                │  • Facebook Shops API   │
                                                    │  • 3PL: Pathao/RedX     │
                          ┌─────────────────┐       │  • Ollama (LLM)         │
                          │ Monitoring      │       └─────────────────────────┘
                          │ Grafana         │
                          │ Prometheus      │       ┌─────────────────────────┐
                          │ Loki (logs)     │       │  Object Storage         │
                          │ Sentry (errors) │       │  S3-compatible          │
                          │ OpenTelemetry   │       │  (Product images,       │
                          └─────────────────┘       │   videos, documents)    │
                                                    └─────────────────────────┘
```

### 8.2 CQRS + Event Sourcing Pattern (NEW V4)

```
┌─── WRITE PATH (Commands) ────────────────────────────────────────────┐
│                                                                      │
│  Client → API Gateway → NestJS Command Handler                       │
│     │                                                                │
│     ├─ PlaceOrderCommand → OrderSaga                                 │
│     │   ├─ Step 1: ReserveInventory → InventoryReserved event        │
│     │   ├─ Step 2: ProcessPayment → PaymentProcessed event           │
│     │   ├─ Step 3: HoldEscrow → EscrowHeld event                     │
│     │   ├─ Step 4: ConfirmOrder → OrderConfirmed event               │
│     │   └─ Step 5: AssignLogistics → LogisticsAssigned event         │
│     │                                                                │
│     ├─ On ANY step failure → Compensating actions:                   │
│     │   PaymentFailed → ReleaseInventory + NotifyBuyer               │
│     │   LogisticsFailed → RefundPayment + ReleaseInventory           │
│     │                                                                │
│     └─ All events → PostgreSQL Event Store (append-only)             │
│                     + Redis publish for real-time subscribers        │
└──────────────────────────────────────────────────────────────────────┘

┌─── READ PATH (Queries) ──────────────────────────────────────────────┐
│                                                                      │
│  Client → API Gateway → NestJS Query Handler                         │
│     │                                                                │
│     ├─ ProductSearch → Meilisearch (denormalized product index)      │
│     ├─ DashboardData → Redis cached materialized views               │
│     ├─ OrderHistory → PostgreSQL read replica                        │
│     └─ AnalyticsQuery → PostgreSQL read replica + materialized views │
│                                                                      │
│  Read models are updated asynchronously by event projectors:         │
│     Event Store → Projector → Denormalized Tables / Meilisearch      │
└──────────────────────────────────────────────────────────────────────┘
```

### 8.3 Data Flow — Key Journeys

#### Journey A: Buyer Places Order (V4 — With Escrow + Saga)

```
Buyer (Browser/PWA/App)
    │  Adds items, applies coupon → Sahayak can auto-apply best coupon
    │  Selects payment: bKash / Nagad / Bangla QR / Card / BNPL / COD
    ▼
NestJS API → PlaceOrderCommand
    │  Step 1: Validate coupon + cart items + inventory availability
    │  Step 2: Reserve inventory (optimistic lock via Prisma)
    │  Step 3: Redirect to payment gateway (or mark COD)
    ▼
Payment Gateway (bKash / Nagad / SSLCommerz / Bangla QR)
    │  Webhook → server-side verification (CRITICAL)
    ▼
NestJS → OrderSaga continues
    │  Step 4: Hold payment in ESCROW (new — regulatory requirement)
    │  Step 5: Create order + decrement inventory (atomic)
    │  Step 6: Assign 3PL via intelligent routing engine
    │  Step 7: Emit events → notification fanout
    ▼
Notification Fanout (parallel via BullMQ)
    ├─ WhatsApp: Vendor receives order alert in preferred locale
    ├─ WhatsApp: Buyer receives confirmation in preferred locale
    ├─ In-App: WebSocket push → buyer sees order status
    ├─ 3PL API: Delivery partner gets assignment
    └─ Event Store: Immutable event logged
    ▼
On Delivery Confirmed (by buyer or auto after 48h)
    │  Escrow releases → vendor disbursement scheduled
    │  VPS score updated with fulfillment data
    └  audit_logs: Full lifecycle recorded
```

#### Journey B: Vendor Uses Agentic Sahayak (NEW V4)

```
Vendor (Dashboard or WhatsApp)
    │  "আমার স্লো-মুভিং প্রোডাক্টগুলোতে ১৫% ডিসকাউন্ট দাও"
    │  ("Give 15% discount on my slow-moving products")
    ▼
PRISM Sahayak V2 (Agentic Mode)
    │  Step 1: Parse intent via LLM (Ollama/GPT-4o)
    │  Step 2: Function call → GET /api/ai/velocity → identify slow products
    │  Step 3: Function call → POST /api/ai/coupon-optimize → calculate discounts
    │  Step 4: Function call → POST /api/coupons/bulk-create → create coupons
    │  Step 5: Respond in Bangla: "৩টি প্রোডাক্টে ১৫% ডিসকাউন্ট কুপন তৈরি হয়েছে"
    ▼
Vendor reviews → confirms or adjusts
    └  All actions logged in audit_logs with agent_action flag
```

### 8.4 Service Communication Map

| From | To | Protocol & Purpose |
|---|---|---|
| Next.js (RSC/Client) | NestJS REST API | HTTPS REST — all feature calls |
| NestJS API | PostgreSQL 16 | Prisma ORM — CQRS write path |
| NestJS API | PostgreSQL Read Replica | Prisma ORM — CQRS read path |
| NestJS API | Redis 7 | ioredis — cache, sessions, BullMQ, pub/sub |
| NestJS API | Meilisearch | REST — product search, RAG-enhanced |
| NestJS API | Ollama | HTTP — LLM inference (local, free) |
| NestJS API | OpenAI | HTTPS — GPT-4o fallback |
| NestJS API | bKash / Nagad / SSLCommerz | HTTPS — payment initiation |
| NestJS API | Bangla QR (Bank APIs) | HTTPS — QR payment verification |
| NestJS API | 3PL APIs (Pathao/RedX/Paperfly) | HTTPS — logistics routing |
| NestJS API | Meta Cloud API | HTTPS — WhatsApp messages (EN/বাংলা) |
| NestJS API | OpenWeatherMap | HTTPS — weather forecast (cached 6h) |
| NestJS API | Facebook Shops API | HTTPS — catalog sync |
| NestJS API | TikTok Shop API | HTTPS — catalog + order sync |
| NestJS API | LiveKit | WebSocket — live video coordination |
| NestJS CRON (hourly) | PostgreSQL + Redis | Category velocity computation |
| NestJS CRON (15min) | PostgreSQL + Redis | Opportunity Engine scan |
| NestJS CRON (daily) | OpenWeatherMap + Redis | Weather forecast refresh |
| NestJS CRON (weekly) | PostgreSQL + ONNX | GBR model evaluation + retrain trigger |
| OpenTelemetry | Grafana Tempo | gRPC — distributed traces |

---

## 9. Core Feature Set

### 9.1 Commerce Layer

| Feature | Detail |
|---|---|
| **Multi-Vendor Product Catalog** | Vendors list products with variants (size, color), pricing, images, and video. Buyers browse with smart filters, AI-ranked results, Bangla search. SEO-friendly slugs. Schema.org JSON-LD structured data for agentic commerce discovery. |
| **Cart, Coupons & Checkout** | Persistent Zustand cart (synced to localStorage + server). AI-optimized coupon suggestions via Sahayak. bKash, Nagad, SSLCommerz, **Bangla QR**, Wallet, BNPL, COD. **Escrow** on all prepaid orders. |
| **Full Order Lifecycle** | State machine: `Pending → Confirmed → Processing → Picked Up → In Transit → Delivered → Completed`. **Saga pattern** ensures consistency. Real-time push via WebSocket. |
| **Reviews & Ratings** | Verified-purchase-only reviews. Photo/video reviews weighted higher. **AI fake review detection.** Vendor response visible publicly. |
| **AI Product Recommendations** | "Trending Now," "You May Like," "Frequently Bought Together" powered by GBR velocity + **bundle engine** + category affinity. |
| **Wishlist & Price Alerts** | Save products. WhatsApp alert when price drops or item goes on sale. |
| **Flash Sales (NEW V4)** | Scheduled flash sales with countdown. Limited stock per slot. Push to wishlisted buyers. Post-sale analytics. |
| **Short-Form Video Commerce (NEW V4)** | TikTok-style 60-second shoppable reels. Vendors record via app. Auto-tag products. Feed algorithm based on buyer interests. |
| **Agentic Shopping (NEW V4)** | Entire purchase journey possible via Sahayak chat. Voice-enabled Bangla checkout. |

### 9.2 Inventory Layer

| Feature | Detail |
|---|---|
| **Real-Time Stock Tracking** | Per-variant inventory with atomic decrement. Full audit log with event sourcing. |
| **Context-Aware Smart Alerts** | GBR ML-triggered (not fixed threshold). ROP considers demand velocity, festivals, weather, category velocity. |
| **WhatsApp Notifications** | Stock below ROP → Bangla/English WhatsApp. Order updates. Festival pre-surge. Weather alerts. |
| **What-If Scenario Planner** | Adjust GBR features interactively. "What if Eid is 5 days away? What if I raise prices 10%?" |
| **Opportunity Engine (NEW V4)** | 15-minute scan: stockout risk → price increase suggestion. Excess → discount/flash sale. Rising demand → stock-up alert. |
| **POS Mode (NEW V4)** | PWA-based Point of Sale. Scan barcode → process sale → update inventory. Unified online + offline inventory. |
| **Sales Analytics Dashboard** | Revenue charts, top products, conversion rates, weather overlay, period comparison. CSV/JSON/PDF exports. |

### 9.3 Trust & Protection Layer (NEW V4)

| Feature | Detail |
|---|---|
| **PRISM Verified** | 3-tier: Basic (NID) → Business (Trade License) → Premium (Brand Authorization). Verified badge on listings. Priority search placement. |
| **PRISM Protect** | 7-day return window. Guaranteed refund if product doesn't match. Prepaid return shipping. Dispute resolution with SLA. Fund from commission pool. |
| **Escrow System** | Buyer payment held until delivery confirmed. Auto-release 48h post-delivery. Dispute → funds held until resolution. Regulatory compliant. |
| **Brand Stores** | Authorized brands get custom storefront. Brand verification. Counterfeit reporting + takedown. |
| **Review Authenticity** | Only verified purchasers. AI sentiment + behavioral analysis for fake detection. |

### 9.4 Admin & Operations Layer

| Feature | Detail |
|---|---|
| **Vendor Approval Workflow** | KYC: NID + Trade License + TIN. Compliance document verification. Store review before listing. |
| **Anomaly Alert Dashboard** | Flagged orders with Z-score + buyer history. One-click Clear/Escalate. |
| **VPS Leaderboard** | Ranked table with Platinum/Gold/Silver/Watch tiers. Low-scoring → suspension risk. Top → homepage promotion. |
| **Platform Analytics** | GMV, order volume, user growth, revenue attribution, category breakdown, delivery metrics. |
| **Finance Admin Dashboard (NEW V4)** | Escrow status monitor. Vendor disbursement queue. VAT reports. Commission reconciliation. |
| **Content Moderation (NEW V4)** | Product listing review. Review/comment moderation. Counterfeit report handling. Video content review. |
| **PRISM Academy (NEW V4)** | Bangla video tutorials. Certification program. Webinars. Resource library. |

### 9.5 Bengali (বাংলা) & Localization Layer

| Component | Implementation |
|---|---|
| **Routing & Detection** | Next.js App Router with next-intl. Routes: `/en/...` and `/bn/...`. Auto-detect browser locale. User preference stored. |
| **UI Translation** | JSON locale files for all UI strings. Bengali numerals (১২৩৪). Currency ৳ formatting. Bengali dates. |
| **WhatsApp Templates** | Meta-approved EN + Bengali templates for all alert types (12 templates). |
| **Bangla Voice Commands (NEW V4)** | Web Speech API + Whisper model. Voice search + vendor operations in Bangla. |
| **GenAI in Bangla** | Sahayak responds in Bangla. RAG search understands Bangla queries. |
| **Onboarding in Bangla** | Full onboarding, product listing, seed data entry in Bangla forms. |

---

## 10. AI Intelligence Layer — 15 Modules

All AI modules are NestJS modules exposing REST endpoints. Redis caches expensive computation. CRON jobs handle retraining, accuracy evaluation, and aggregation.

### Cold-Start Solution (3-Tier Bootstrap)

| Tier | When | What Happens |
|---|---|---|
| **Tier 1** | Onboarding | Vendor enters past 30-day sales per product (Bangla/English). Stored as `synthetic_sales_seed`. |
| **Tier 2** | Week 1+ | Real orders supplement seed data. `data_quality_score` tracks real-to-seed ratio. |
| **Tier 3** | Day 90+ | Seed deprecated. Model retrains fully on real data. `data_quality_score = 1.0`. |

### Module 01 — ONNX Gradient Boosting Regressor (Real ML)

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/forecast/:productId` |
| Model | GradientBoostingRegressor → ONNX (~80–150KB) |
| Runtime | onnxruntime-node v1.17+ — inference **<80ms** |
| Input Features (13) | `quantity_7d`, `quantity_14d`, `quantity_30d`, `rolling_mean_7d`, `rolling_std_7d`, `trend_slope`, `day_of_week`, `is_festival_week`, `days_to_next_festival`, `festival_type` (one-hot), `temperature_avg`, `precipitation_mm`, `category_velocity_score` |
| Output | `{ forecast_7d, forecast_14d, forecast_30d, confidence, feature_importance, model_version, data_quality_score }` |
| Cache | 24h Redis TTL |

### Module 02 — Smart Reorder Point Calculator

**Endpoint:** `GET /api/ai/reorder/:productId`

```
ROP = (Avg Daily Demand × Lead Time) + Safety Stock
Safety Stock = Z(1.65) × StdDev × sqrt(Lead Time)
  × festival_multiplier (if days_to_festival < 14)
  × weather_multiplier (if monsoon + relevant category)

Lead Time: Learned from actual supplier delivery times (not static).
```

### Module 03 — Sales Velocity Momentum Ranker

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/velocity` |
| Algorithm | Exponential smoothing on rolling 7-day sales rate |
| Output | `{ products: [{ id, name, velocity_score, trend: 'accelerating'|'stable'|'decelerating', change_pct }] }` |
| Usage | Accelerating → "Trending" shelf on buyer homepage + vendor receives congratulation alert. Decelerating → vendor WhatsApp warning + coupon suggestion trigger. |
| Cache | 1h Redis TTL |

### Module 04 — Coupon Optimization Advisor

| Property | Value |
|---|---|
| Endpoint | `POST /api/ai/coupon-optimize` |
| Algorithm | `Optimal Discount = (Surplus Ratio - 1) / Price Elasticity` with festival urgency modifier |
| Input | `{ product_id, target_days_to_clear?, max_discount_pct? }` |
| Output | `{ recommended_discount_pct, expected_units_moved, expected_revenue, estimated_days_to_clear, coupon_code_suggestion }` |
| Trigger | Auto-triggers when supply days > 45 (excess inventory). Also callable by Sahayak agentic mode. |

### Module 05 — Order Anomaly Detector

| Property | Value |
|---|---|
| Endpoint | `POST /api/ai/anomaly/check` (async BullMQ job on every order) |
| Signals (6) | `order_frequency_z` (orders per hour from same buyer), `quantity_z` (vs. category avg), `address_mismatch` (billing ≠ shipping), `payment_method_age` (newly added card/MFS), `device_fingerprint_score`, **`cod_history_score` (NEW V4)** |
| Scoring | Each signal → Z-score. Composite > 2.5 → flag as suspicious + soft-pause order + notify admin |
| COD Intelligence | `cod_history_score = successful_cod_deliveries / total_cod_orders`. Score < 0.5 → high risk → require advance payment or reject COD |
| Action | Flagged orders appear on Admin Anomaly Dashboard with one-click Clear/Escalate buttons |

### Module 06 — Vendor Performance Score (VPS)

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/vps/:vendorId` |
| Components | Fulfillment Rate (35%), Avg Rating (25%), Response-to-Ship time (15%), Delivery Accuracy (15%), Dispute Rate (10%) |
| Output | `{ score: 0-100, tier: 'platinum'|'gold'|'silver'|'watch', components: {...}, trend: 'improving'|'stable'|'declining' }` |
| Tiers | **Platinum** (85+): homepage promotion, reduced commission. **Gold** (70-84): standard. **Silver** (50-69): warning notices. **Watch** (<50): at risk of suspension |
| Update Frequency | Recalculated after each order delivery + weekly full refresh |

### Module 07 — WhatsApp Business Engine (EN + বাংলা)

| Property | Value |
|---|---|
| Provider | Meta Cloud API via `@nestjs/bull` queue |
| Templates (12) | `order_placed`, `order_shipped`, `order_delivered`, `low_stock_alert`, `stockout_warning`, `festival_surge_alert`, `weather_demand_alert`, `weekly_forecast_digest`, `payment_received`, `escrow_released`, `vps_tier_change`, `academy_new_module` |
| Languages | Each template in EN + বাংলা (Meta-approved). Locale auto-selected from `user.preferred_locale` |
| Fallback Chain | WhatsApp → Web Push Notification → In-App Notification Center |
| Rate Limit | 5 messages/vendor/hour, 50/day (to avoid spam) |
| Example (বাংলা) | 🚨 *স্টক সতর্কতা:* আপনার "লাল শাড়ি (XL)" মাত্র ৫টি বাকি আছে। আগামী ৭ দিনে ১২টি বিক্রি হবে বলে আমরা অনুমান করছি। 👉 [এখনই অর্ডার করুন] |

### Module 08 — Cross-Vendor Category Emergence

| Property | Value |
|---|---|
| Endpoint | Internal only (no public API — privacy-sensitive) |
| Algorithm | Hourly CRON aggregates `category_velocity_score` from all vendors' `order_items` by category |
| Privacy | **Aggregate only** — never exposes individual vendor data. Minimum 3 vendors per category required |
| Output | `category_velocity` table: `{ category_id, velocity_score, vendor_count, computed_at }` |
| Impact | Injected as feature #13 into GBR model → even new vendors benefit from network intelligence |
| Cache | Redis 1h TTL |

### Module 09 — Closed-Loop GBR Feedback

| Property | Value |
|---|---|
| Trigger | Weekly CRON (every Sunday midnight) |
| Algorithm | Compare `ai_forecasts.forecast_7d` vs. actual sales for each product. Calculate `forecast_error = abs(predicted - actual) / actual` |
| Retrain Trigger | If `rolling_avg_error > 0.25` for a product → flag for retrain. If > 30% of products flagged → trigger full model retrain |
| Output | `forecast_accuracy` table: `{ forecast_id, actual_7d, forecast_error, rolling_avg_error }` |
| Emergence | Per-product memory emerges — model learns seasonal patterns, vendor-specific behaviors, and category trends over time |

### Module 10 — Weather-Aware Demand Signals

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/weather/impact` |
| Source | OpenWeatherMap 5-day forecast API (Free tier: 1000 calls/day) |
| Features Derived | `temperature_avg`, `precipitation_mm`, `is_monsoon` (Jun-Sep flag) |
| Impact Matrix | Monsoon → umbrella/raincoat +80%, outdoor items -40%. Heatwave → drinks +60%, winter clothing -90%. Cold snap → blankets +50% |
| Cache | Redis 6h TTL (weather doesn't change faster than this) |
| CRON | Daily refresh at 6 AM Bangladesh time |

### Module 11 — What-If Scenario Planner

| Property | Value |
|---|---|
| Endpoint | `POST /api/ai/what-if` |
| Input | `{ product_id, modified_features: { is_festival_week?: boolean, days_to_next_festival?: number, temperature_avg?: number, price_change_pct?: number } }` |
| Algorithm | Takes vendor's real current GBR feature vector, applies user modifications, runs live ONNX re-inference |
| Output | `{ original_forecast: {...}, modified_forecast: {...}, delta: { units_7d, units_14d, units_30d, revenue_impact } }` |
| UI | Side-by-side comparison chart. Sliders for each adjustable feature. Real-time update on slider change. |

### Module 12 — Agentic GenAI Sahayak V2 (NEW V4)

| Property | Value |
|---|---|
| Endpoint | `POST /api/ai/sahayak/chat` |
| LLM Primary | Ollama (Llama 3.2-8B) — local, free |
| LLM Fallback | OpenAI GPT-4o (Pro+ tier only) |
| Mode | Agentic — can execute actions via function calling |
| Available Tools | `search_products`, `get_forecast`, `create_coupon`, `add_to_cart`, `apply_coupon`, `get_order_status`, `set_discount`, `get_analytics`, `go_live` |
| Languages | Bangla + English (auto-detect from input) |
| Context | RAG via pgvector: product catalog, order history, vendor's own data |
| Rate Limits | Free: 3/day, Starter: 20/day, Growth+: Unlimited |

### Module 13 — RAG Semantic Search

| Property | Value |
|---|---|
| Endpoint | `GET /api/search/semantic?q=...` |
| Tech | pgvector extension on PostgreSQL 16 |
| Embedding Model | `all-MiniLM-L6-v2` (384-dim, fast, multilingual) via Ollama. Upgrade path: `paraphrase-multilingual-MiniLM-L12-v2` for better Bangla |
| Index | IVFFlat index on `product_embeddings` table |
| Flow | Query → embed → cosine similarity search → filter (price, category, availability) → return ranked results |
| Hybrid | Semantic results merged with Meilisearch full-text results using reciprocal rank fusion (RRF) |
| Update | Product embeddings regenerated on product create/update via BullMQ background job |
| Example | Bangla query: "ঈদের জন্য লাল শাড়ি" → semantic match returns red sarees + related festive clothing + matching accessories |

### Module 14 — Opportunity Engine (NEW V4)

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/opportunities/:vendorId` |
| Refresh Cycle | Every 15 minutes via CRON |
| Alerts | Stockout Risk (red), Excess Inventory (yellow), Rising Demand (green), Price Opportunity (blue) |
| Actions | Suggest price change, flash sale, bundle, restock amount |
| Notification | WhatsApp push for critical (red) alerts |

### Module 15 — Bundle Recommendation Engine (NEW V4)

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/bundles/:vendorId` |
| Algorithm | Co-purchase pattern analysis + category affinity |
| Output | Top 5 bundle suggestions with recommended pricing (5-15% discount) |
| Data Source | `order_items` co-occurrence matrix, computed weekly |

---

## 11. New Strategic Modules (A–L)

### Module A — Live Commerce Engine

| Component | Technology |
|---|---|
| Streaming | LiveKit (WebRTC) — SFU architecture |
| Recording | HLS recording for replays |
| Features | Shoppable overlay, live Q&A, flash sale countdown, viewer count, emoji reactions |
| Access | Starter: 2/mo, Growth+: Unlimited |

### Module B — Short-Form Video Commerce (NEW V4)

| Component | Detail |
|---|---|
| Format | 60-second vertical shoppable reels |
| Recording | In-app camera with filters, text overlay, product tagging |
| Feed | Algorithm: buyer interests + trending + category affinity + recency |
| Discovery | Swipeable feed on buyer homepage + dedicated "Explore" tab |
| Storage | S3-compatible object storage with CDN |

### Module C — Social Commerce Bridge

FB Shops sync + WhatsApp Catalog + **TikTok Shop API** (catalog + order sync) + **YouTube Shopping** (live stream integration). Cross-platform sales attribution tracking.

### Module D — PRISM Wallet & Financial Services

Digital wallet for cashback, refunds. BNPL integration (ShopUp/IDLC Capital/Brac SAAJAN). Wallet balance spendable on platform. Min withdrawal ৳100 via bKash/Nagad.

### Module E — 3PL Logistics Intelligence (UPGRADED V4)

```
Intelligent Routing Engine:
  Input: vendor_location, buyer_location, package_weight, urgency,
         3PL_current_cost, 3PL_current_SLA, 3PL_capacity_status,
         vendor_3PL_preference, buyer_paid_express
  Output: Ranked 3PL options with cost + ETA + reliability score
  Failover: If primary 3PL rejects/delays → auto-assign backup

COD Intelligence (NEW V4):
  • Fraud scoring for COD: high-risk address/phone → require advance payment
  • Buyer COD history score (0-100) — increases with successful COD deliveries
  • COD-to-digital incentive: ৳20 off if buyer pays via bKash instead of COD

Rate Negotiation (NEW V4):
  • Bulk volume = negotiated rates
  • PRISM negotiates on behalf of all vendors (collective bargaining)
  • Transparent rate comparison shown to vendors
```

### Module F — In-App Chat & AI Auto-Response

Real-time buyer-seller messaging via WebSocket. AI auto-response for common queries (hours, shipping, returns). Vendor can set custom auto-responses. Chat history preserved.

### Module G — PRISM Verified Program (NEW V4)

| Level | Requirements | Benefits |
|---|---|---|
| **Basic** | National ID (NID) verification | Verified badge, visible on listings |
| **Business** | Trade License + TIN | Priority search placement, PRISM Protect eligible |
| **Premium** | Brand authorization letter + business bank account | Brand Store, homepage feature, reduced commission |

### Module H — PRISM Protect (NEW V4)

```
Buyer Protection Guarantee:
  1. Product doesn't match description → Full refund
  2. Product not delivered within SLA → Full refund
  3. 7-day return window on eligible products
  4. Prepaid return shipping (cost shared: PRISM 50% + Vendor 50%)
  5. Dispute resolution SLA: Acknowledge < 24h, Resolve < 72h
  6. Fund source: 0.5% of each transaction reserved in protection pool
```

### Module I — Escrow System (NEW V4)

```
Flow: Buyer pays → Payment held in PRISM escrow account
  │  → Vendor fulfills order → Delivery agent marks delivered
  │  → 48-hour cooling period (buyer can raise dispute)
  │  → Auto-release to vendor after 48h OR buyer confirms earlier
  │
  │  If dispute raised:
  │  → Funds frozen → Support investigates → Resolution within 72h
  │  → Refund to buyer OR release to vendor

Accounting: Separate escrow ledger with full audit trail.
Compliance: Bangladesh Digital Commerce Guidelines requirement.
```

### Module J — POS Mode (NEW V4)

PWA-based Point of Sale for vendors with physical shops. Barcode scan → process sale → auto-update inventory. Unified online + offline sales in one dashboard. Bangla QR acceptance for in-store payments. Daily POS sales summary via WhatsApp.

### Module K — PRISM Academy (NEW V4)

| Content Type | Topics |
|---|---|
| Video Tutorials (Bangla) | How to list products, use AI forecasting, go live, create reels, use POS |
| Certification | "PRISM Certified Seller" badge after completing 5 core modules |
| Webinars | Weekly sessions with successful vendors |
| Resource Library | Photography tips, pricing strategies, Eid prep guides, SEO basics |
| Onboarding Wizard | Step-by-step guided setup in Bangla. First product listed in < 5 minutes |

### Module L — Referral & Growth Engine (NEW V4)

| Program | Reward |
|---|---|
| Vendor refers vendor | Both get 1 month free Starter |
| Buyer refers buyer | Both get ৳100 wallet credit |
| Top affiliates | Increased commission rate |
| Monthly top vendor | Social media recognition + homepage feature |

---

## 12. Bangladesh-Native Integrations

### 12.1 Festival Intelligence Calendar

| Festival | Approx. Date | Surge Window | Top Impact Categories |
|---|---|---|---|
| **Eid-ul-Fitr** | Variable (lunar) | 14 days | Clothing +180%, Groceries +60% |
| **Eid-ul-Adha** | Variable (lunar) | 14 days | Livestock, clothing, food +120% |
| **Durga Puja** | Oct (variable) | 10 days | Clothing, sweets, gifts +90% |
| **Pohela Boishakh** | April 14 | 7 days | Clothing, food, crafts +70% |
| **Ramadan Start** | Variable (lunar) | 30-day sustained | Dates, food, prayer items +80% |
| **Victory Day** | December 16 | 5 days | Clothing, accessories +30% |
| **Valentine's Day** | February 14 | 5 days | Gifts, crafts, food +40% |
| **Independence Day** | March 26 | 3 days | Flags, accessories +20% |

GBR features injected: `is_festival_week`, `days_to_next_festival`, `festival_type` (one-hot encoded).

### 12.2 Payment Gateways

| Gateway | Type | Status | Use Case |
|---|---|---|---|
| **bKash PGW** | MFS | Production | Primary MFS — 70M users |
| **Nagad PGW** | MFS | Production | Secondary MFS — 25M users |
| **SSLCommerz** | Aggregator | Production | Cards (Visa/MC), net banking, MFS fallback |
| **Bangla QR (NEW V4)** | National QR | Production | Bank-to-bank contactless, in-store POS |
| **Rocket** | MFS | Production | Dutch-Bangla MFS |
| **PRISM Wallet** | Internal | Production | Cashback, refunds, in-platform spend |
| **BNPL Partners** | Installment | Phase 2 | ShopUp/IDLC — 3/6/12 month EMI |

### 12.3 Logistics Partners (3PL)

| Partner | Coverage | Strength | Integration |
|---|---|---|---|
| **Pathao Courier** | Nationwide | Fast urban delivery, API-ready | REST API |
| **RedX** | Nationwide | COD reconciliation, large seller network | REST API |
| **Paperfly** | Nationwide | Sub-district coverage, reliable tracking | REST API |
| **Steadfast** | Nationwide | Competitive pricing, bulk rates | REST API |
| **eCourier** | Dhaka metro | Same-day Dhaka delivery | REST API |

---

## 13. Technology Stack — V4

| Layer | Technology | Why This Choice |
|---|---|---|
| **Frontend Framework** | Next.js 15 (App Router + PPR) | Partial Pre-Rendering = best SEO + performance for e-commerce |
| **UI Components** | shadcn/ui + Tailwind CSS + Radix | Accessible, customizable, production-grade |
| **State Management** | Zustand (client) + React Query (server) | Lightweight, offline-capable cart |
| **Charts** | Recharts + Nivo | Forecast charts, analytics dashboards |
| **i18n** | next-intl | EN + Bengali routing, number/currency formatting |
| **Mobile App** | React Native (Expo) | Cross-platform, shared business logic with web |
| **Backend Framework** | NestJS 10 (TypeScript) | Modular, CQRS-ready, enterprise patterns |
| **CQRS** | @nestjs/cqrs | Command/query separation, saga orchestration |
| **ORM** | Prisma 5 | Type-safe, migrations, RLS-compatible |
| **Database** | PostgreSQL 16 + pgvector | ACID, RLS, vector search, partitioning |
| **Read Replica** | PostgreSQL 16 replica | Offload analytics/search queries |
| **Connection Pool** | PgBouncer | Handle 10K+ connections efficiently |
| **Cache / Queue** | Redis 7 + BullMQ | Forecast cache, job queue, session store, pub/sub |
| **Search** | Meilisearch | Typo-tolerant, fast, Bangla-compatible |
| **ML Runtime** | onnxruntime-node v1.17+ | GBR inference <80ms, zero Python dependency |
| **LLM Primary** | Ollama (Llama 3.2-8B) | Local, free, function calling for agentic mode |
| **LLM Fallback** | OpenAI GPT-4o | Pro+ tier, complex queries |
| **Embeddings** | all-MiniLM-L6-v2 via Ollama | RAG embeddings for pgvector |
| **Live Video** | LiveKit (WebRTC SFU) | Low-latency live commerce |
| **Video Storage** | S3-compatible (MinIO / Cloudflare R2) | Reels, live replays, product videos |
| **Real-time** | Socket.io + SSE | WebSocket for chat/orders, SSE for notifications |
| **Auth** | Auth.js (NextAuth v5) | Social login, JWT, MFA |
| **Payments** | bKash + Nagad + SSLCommerz + Bangla QR APIs | Full BD payment stack |
| **WhatsApp** | Meta Cloud API | EN + Bengali templates |
| **Weather** | OpenWeatherMap Free API | 5-day forecast, monsoon detection |
| **Voice** | Web Speech API + Whisper (Ollama) | Bangla voice commands |
| **Social APIs** | Facebook Shops + TikTok Shop + YouTube | Catalog sync, order sync |
| **3PL APIs** | Pathao + RedX + Paperfly + Steadfast | Logistics routing |
| **CI/CD** | GitHub Actions | Automated lint, test, build, deploy |
| **Containerization** | Docker + Docker Compose | All services containerized |
| **Orchestration** | Docker Compose (Phase 1) → K8s (Phase 3) | Scale when needed |
| **Monitoring** | Grafana + Prometheus + Loki | Metrics, dashboards, log aggregation |
| **Error Tracking** | Sentry | Frontend + backend error capture |
| **Tracing** | OpenTelemetry + Grafana Tempo | Distributed request tracing |
| **Logging** | Pino (production) + Winston (dev) | Structured JSON logs, 5x faster |
| **Analytics** | PostHog (internal) + Plausible (public) | Product analytics + privacy-friendly web |
| **Hosting** | Hetzner / DigitalOcean VPS | EU/SG regions, cost-effective |
| **CDN** | Cloudflare | Edge caching, DDoS protection, R2 storage |
| **DNS** | Cloudflare | prism.com.bd domain management |

---

## 14. Database Schema

> 50+ tables organized by domain. All tables include `id (uuid PK)`, `created_at`, `updated_at` unless noted.

### Core Commerce Tables

| Table | Key Columns | Notes |
|---|---|---|
| `users` | role, email, phone, whatsapp_number, preferred_locale, avatar_url, is_verified, mfa_enabled | 8 roles via enum |
| `vendors` | user_id FK, shop_name, logo, description, location, subscription_tier, verification_level, is_approved | Tied to subscription |
| `products` | vendor_id FK, name, description, slug, price, compare_at_price, category_id FK, images[], video_url, schema_org_data, is_active | Schema.org JSON-LD |
| `product_variants` | product_id FK, sku, size, color, price_override, inventory_count, barcode | POS barcode support |
| `categories` | parent_id (self-referential), name_en, name_bn, slug, icon | Bilingual |
| `orders` | buyer_id FK, vendor_id FK, status (enum), total, discount, payment_method, payment_status, escrow_status, delivery_partner, tracking_id | Saga-managed states |
| `order_items` | order_id FK, product_id FK, variant_id FK, quantity, unit_price, subtotal | Immutable after creation |
| `coupons` | vendor_id FK, code, discount_type, discount_value, min_order, max_uses, valid_from, valid_to, is_ai_generated | |
| `reviews` | buyer_id FK, product_id FK, order_id FK, rating (1-5), text, photo_urls[], video_url, is_verified_purchase, vendor_response | Photo/video reviews |
| `wishlists` | buyer_id FK, product_id FK | Price alert trigger |

### AI & Intelligence Tables

| Table | Key Columns | Notes |
|---|---|---|
| `ai_forecasts` | product_id FK, forecast_7d, forecast_14d, forecast_30d, confidence, feature_importance (jsonb), model_version, data_quality_score | Cached 24h |
| `forecast_accuracy` | forecast_id FK, actual_7d, forecast_error, rolling_avg_error, computed_at | Feedback loop |
| `festival_calendar` | name_en, name_bn, festival_date, surge_window_days, demand_multiplier (jsonb), is_active | Pre-seeded |
| `category_velocity` | category_id FK, velocity_score, vendor_count, computed_at | Hourly CRON |
| `weather_cache` | location, temperature_avg, precipitation_mm, is_monsoon, forecast_json, cached_at | 6h TTL |
| `synthetic_sales_seed` | product_id FK, units_sold, period_start, period_end, is_deprecated | Cold-start |
| `opportunity_alerts` | vendor_id FK, product_id FK, alert_type (enum), severity, recommendation, is_actioned, created_at | 15-min refresh |
| `bundle_suggestions` | vendor_id FK, product_ids[], suggested_price, discount_pct, confidence, co_purchase_count | Weekly computation |
| `sahayak_conversations` | user_id FK, messages (jsonb[]), tool_calls (jsonb[]), tokens_used, created_at | Agentic audit trail |

### Trust & Compliance Tables (NEW V4)

| Table | Key Columns | Notes |
|---|---|---|
| `escrow_transactions` | order_id FK, buyer_id FK, vendor_id FK, amount, status (held/released/disputed/refunded), held_at, released_at | Regulatory requirement |
| `verification_levels` | vendor_id FK, level (basic/business/premium), documents (jsonb), status, verified_by, verified_at | 3-tier KYC |
| `compliance_documents` | vendor_id FK, type (trade_license/tin/vat_reg/nid), document_url, is_verified, verified_by | KYC attachments |
| `buyer_protection_claims` | order_id FK, buyer_id FK, vendor_id FK, reason, evidence_urls[], status, resolution, amount_refunded | PRISM Protect |
| `brand_authorizations` | vendor_id FK, brand_name, authorization_doc_url, is_verified | Brand Store eligibility |
| `counterfeit_reports` | product_id FK, reporter_id FK, evidence, status, action_taken | Takedown system |
| `bangla_qr_codes` | vendor_id FK, qr_data, payment_reference, amount, status | POS + online |
| `vat_records` | vendor_id FK, month, taxable_amount, vat_amount, report_url | Monthly VAT |

### Financial Tables

| Table | Key Columns | Notes |
|---|---|---|
| `wallets` | user_id FK, balance, currency (BDT), is_active | Buyer + vendor |
| `wallet_transactions` | wallet_id FK, type (credit/debit), amount, source, reference_id | Full ledger |
| `vendor_disbursements` | vendor_id FK, amount, method, status, processed_at | Post-escrow release |
| `subscription_billing` | vendor_id FK, tier, amount, billing_cycle, next_billing_date, payment_method | Recurring billing |
| `commission_records` | order_id FK, vendor_id FK, gmv, commission_rate, commission_amount | Per-transaction |
| `flash_sale_slots` | vendor_id FK, product_id FK, sale_price, stock_limit, start_time, end_time, units_sold | Flash sales |

### Engagement Tables

| Table | Key Columns | Notes |
|---|---|---|
| `live_streams` | vendor_id FK, title, status, viewer_count, duration, replay_url, products_featured[] | LiveKit sessions |
| `short_form_videos` | vendor_id FK, video_url, thumbnail_url, tagged_products[], view_count, like_count, duration | Reels |
| `chat_messages` | sender_id FK, receiver_id FK, order_id FK, content, is_ai_auto_response, read_at | Buyer-seller chat |
| `notifications` | user_id FK, type (enum), channel (whatsapp/in_app/push), content, locale, delivered, read_at | Multi-channel |
| `affiliate_tracking` | affiliate_id FK, product_id FK, click_count, conversion_count, commission_earned | Influencer program |
| `referral_codes` | user_id FK, code, type (vendor/buyer), used_count, reward_given | Growth engine |
| `academy_progress` | vendor_id FK, module_id, status (not_started/in_progress/completed), completed_at | PRISM Academy |
| `pos_transactions` | vendor_id FK, product_id FK, variant_id FK, quantity, amount, payment_method, barcode_scanned | POS sales |

### System Tables

| Table | Key Columns | Notes |
|---|---|---|
| `audit_logs` | actor_id FK, action_type, entity_type, entity_id, payload (jsonb), is_agent_action | Append-only, RLS |
| `event_store` | aggregate_id, aggregate_type, event_type, event_data (jsonb), version, created_at | Event sourcing |
| `api_keys` | vendor_id FK, key_hash, permissions[], rate_limit, last_used_at | Pro+ tier API access |
| `content_moderation_queue` | content_type, content_id, reason, status, moderator_id, resolved_at | Content mod |

---

## 15. Key API Endpoints

> 75+ endpoints organized by domain. Full OpenAPI spec auto-generated at `/api/docs`.

### Auth & Users
| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/auth/register` | Public | Register with role, locale |
| POST | `/api/auth/login` | Public | JWT + refresh token |
| POST | `/api/auth/refresh` | Public | Rotate refresh token |
| GET | `/api/users/me` | Auth | Own profile |
| PATCH | `/api/users/me/locale` | Auth | Update locale preference |

### Products & Catalog
| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/products` | Public | Browse with filters, search, pagination |
| GET | `/api/products/:slug` | Public | Product detail with Schema.org JSON-LD |
| POST | `/api/products` | Vendor | Create product listing |
| GET | `/api/products/search` | Public | Meilisearch + RAG semantic search |

### Orders & Checkout
| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/orders` | Buyer | Place order (triggers Saga) |
| GET | `/api/orders/:id` | Auth | Order detail with tracking |
| PATCH | `/api/orders/:id/status` | Vendor/Delivery | Update order status |
| POST | `/api/payments/webhook` | Internal | Payment gateway callback |
| GET | `/api/escrow/:orderId` | Finance | Escrow status for order |

### AI Modules
| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/ai/forecast/:productId` | Vendor | GBR ONNX forecast |
| GET | `/api/ai/reorder/:productId` | Vendor | Smart reorder point |
| GET | `/api/ai/velocity` | Vendor | Sales velocity ranking |
| POST | `/api/ai/coupon-optimize` | Vendor | Optimal discount recommendation |
| POST | `/api/ai/anomaly/check` | Internal | Async order anomaly check |
| GET | `/api/ai/vps/:vendorId` | Admin | Vendor performance score |
| GET | `/api/ai/opportunities/:vendorId` | Vendor | Opportunity Engine alerts |
| GET | `/api/ai/bundles/:vendorId` | Vendor | Bundle recommendations |
| POST | `/api/ai/sahayak/chat` | Vendor/Buyer | Agentic GenAI assistant |
| POST | `/api/ai/what-if` | Vendor | Scenario planner |
| GET | `/api/ai/weather/impact` | Vendor | Weather demand signals |

### Trust & Compliance
| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/verification/submit` | Vendor | Submit KYC documents |
| GET | `/api/verification/:vendorId` | Admin | Review verification |
| POST | `/api/protect/claim` | Buyer | File buyer protection claim |
| GET | `/api/protect/claims` | Support | All active claims |
| POST | `/api/escrow/release/:orderId` | Finance | Manual escrow release |

### Live & Social Commerce
| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/live/start` | Vendor | Start live stream |
| POST | `/api/videos/upload` | Vendor | Upload short-form reel |
| GET | `/api/videos/feed` | Buyer | Personalized video feed |
| POST | `/api/social/sync/facebook` | Vendor | Sync to FB Shops |
| POST | `/api/social/sync/tiktok` | Vendor | Sync to TikTok Shop |

---

## 16. UI Wireframes & Screens

### Screen 1 — Vendor AI Dashboard (Desktop 1440px)

```
┌───────────────────────────────────────────────────────────────────────────┐
│  PRISM Commerce  [🔍 Search] [🔔 3] [Sahayak 🤖] [EN|বাংলা] [Profile ▼]  │
├─────────┬─────────────────────────────────────────────────────────────────┤
│ Sidebar │  ┌─ Top Stats ───────────────────────────────────────────────┐  │
│ 🏠 Home  │  │ Revenue ৳42.5K  │ Orders 12  │ Low-Stock 3🔴 │ VPS 87⭐ │  │
│ 📦 Prods │  └──────────────────────────────────────────────────────────┘  │
│ 📋 Orders│  ┌─ Opportunity Engine (NEW V4) ────────────────────────────┐  │
│ 📊 AI    │  │ 🔴 Product B: Stockout in 5 days → [Restock Now]         │  │
│ 🎥 Live  │  │ 🟡 Product D: 60-day excess → [Create Flash Sale]        │  │
│ 📹 Reels │  │ 🟢 Product A: Demand ↑23% → [Hold Price]                 │  │
│ 💰 Sales │  └──────────────────────────────────────────────────────────┘  │
│ 🏪 POS   │                                                                │
│ 🎓 Learn │  ┌─ Product List ──────┬─ Forecast Chart ──────────────────┐   │
│ ⚙️ Setup │  │ [Product A] ███ 85% │ Recharts Area Chart:              │   │
│         │  │  Forecast: ↑         │ 30d history + 30d GBR forecast     │   │
│         │  │ [Product B] ██ 15%🚨 │ (dashed + confidence band)         │   │
│         │  │  🗓 Eid in 14 days    │ Festival Markers: 🔴 Eid (x-axis) │   │
│         │  └──────────────────────┴────────────────────────────────────┘   │
│         │  ┌─ Sahayak Chat (Agentic) ────────────────────────────────┐     │
│         │  │ 🤖 "আপনার ৩টি স্লো-মুভিং প্রোডাক্টে ১৫% ডিসকাউন্ট           │     │
│         │  │    তৈরি করেছি। দেখুন... " [View Coupons]                 │     │
│         │  └─────────────────────────────────────────────────────────┘     │
└─────────┴──────────────────────────────────────────────────────────────────┘
```

### Screen 2 — Buyer Homepage (Mobile 375px)

```
┌───────────────────────────────┐
│  PRISM  [🔍] [🔔] [🛒 2]    │
├───────────────────────────────┤
│  🤖 "কি খুঁজছেন?" [🎤 Voice] │ ← Sahayak search bar
├───────────────────────────────┤
│  📹 [Reel 1] [Reel 2] [R3]   │ ← Swipeable reels
│     Trending Reels ▸          │
├───────────────────────────────┤
│  🔴 LIVE  [Vendor A: Sarees]  │ ← Active live stream
│  👤 2.3K watching [Join]      │
├───────────────────────────────┤
│  Flash Sale ⚡ 2h 34m left    │
│  [Product] ৳800 ░░৳500 -37%   │
├───────────────────────────────┤
│  Trending Now 🔥              │
│  [Prod 1] [Prod 2] [Prod 3]   │
├───────────────────────────────┤
│  🏠  🔍  📹  🛒  👤         │ ← Bottom nav
└───────────────────────────────┘
```

---

## 17. Security Architecture

| Layer | Implementation |
|---|---|
| **RBAC** | 8-role system. Every endpoint with `@Roles()` guard. Permission matrix enforced at middleware. |
| **JWT + Refresh + MFA** | Access: 15min. Refresh: rotate on use. Optional TOTP MFA for vendors/admins. |
| **Rate Limiting** | Redis-backed `@nestjs/throttler`. Auth: 10/min. Checkout: 5/min. AI: tier-based. |
| **Input Validation** | `class-validator` DTOs. DOMPurify XSS. Prisma parameterized queries (SQL injection proof). |
| **RLS (Row-Level Security)** | Vendors see only own data. Cross-vendor queries aggregate-only. Category velocity: min 3 vendors. |
| **Escrow Security** | Separate ledger. Dual-approval for manual releases. Full audit trail. |
| **Payment Security** | Server-side webhook verification for all gateways. PCI-DSS compliance via gateway tokenization. |
| **Audit Log** | Append-only `audit_logs`. No UPDATE/DELETE via RLS. Agent actions flagged. |
| **API Versioning** | `/api/v1/...`. Breaking changes require version bump. 6-month deprecation notice. |
| **CORS + HTTPS** | Whitelist frontend origins only. HTTPS enforced. HSTS headers. |
| **WAF** | Cloudflare WAF rules. DDoS protection. Bot detection. |
| **Secrets Management** | Environment variables. Never committed. Rotated quarterly. |
| **Content Security** | Video/image upload scanning. Max file sizes. Content moderation queue. |
| **Data Privacy** | GDPR-inspired data handling. User data export/delete. Privacy policy. |

---

## 18. Performance & Observability

### Performance Targets

| Metric | Target | How |
|---|---|---|
| API Response (p95) | < 200ms | CQRS read path, Redis cache, PgBouncer |
| GBR Inference | < 80ms | onnxruntime-node in-process |
| Product Search | < 50ms | Meilisearch + denormalized index |
| Page Load (LCP) | < 2.5s | Next.js PPR + Cloudflare CDN |
| Concurrent Users | 10,000+ | Docker scaling, read replicas |
| Live Stream Latency | < 500ms | LiveKit SFU |
| Sahayak Response | < 3s | Ollama local, cached RAG |

### Observability Stack

| Tool | Purpose |
|---|---|
| **Grafana** | Dashboards: revenue, orders, API latency, error rates, AI accuracy |
| **Prometheus** | Metrics collection: NestJS, PostgreSQL, Redis, BullMQ |
| **Loki** | Log aggregation: structured JSON logs via Pino |
| **Sentry** | Error tracking: frontend + backend, source maps |
| **OpenTelemetry** | Distributed tracing: trace order saga across modules |
| **Grafana Tempo** | Trace storage and visualization |
| **PostHog** | Product analytics: feature usage, conversion funnels |
| **UptimeRobot** | External uptime monitoring + alerting |

---

## 19. Regulatory & Legal Compliance (NEW V4)

### 19.1 Bangladesh Digital Commerce Guidelines

| Requirement | PRISM V4 Implementation |
|---|---|
| **Escrow System** | Mandatory. All prepaid orders held in escrow until delivery confirmed. |
| **Trade License** | Required for vendor onboarding. Verified during KYC. |
| **Return & Refund Policy** | PRISM Protect: 7-day return window. Policy displayed on all product pages. |
| **Product Description Accuracy** | AI-assisted description review. Counterfeit reporting system. Content moderation. |
| **Consumer Complaint Mechanism** | Dispute resolution center with SLA. Buyer protection claims. |

### 19.2 Bangladesh Bank / Financial Regulations

| Requirement | PRISM V4 Implementation |
|---|---|
| **Bangla QR** | Integrated before June 2026 mandate. All major banks supported. |
| **Payment & Settlement Systems Act 2024** | Compliance with reporting requirements. Transaction monitoring. |
| **MFS Compliance** | bKash + Nagad integrated via official PGW APIs. Server-side verification. |
| **Anti-Money Laundering** | Transaction limits. KYC verification. Suspicious activity flags via anomaly detector. |

### 19.3 Tax & VAT

| Requirement | PRISM V4 Implementation |
|---|---|
| **15% VAT** | Auto-computed on applicable transactions. Monthly VAT reports for vendors. |
| **TIN Verification** | Required for Business-level verification and above. |
| **Invoice Requirements** | Auto-generated invoices with VAT breakdown. Bangla invoice template available. |

### 19.4 Data Protection

| Requirement | PRISM V4 Implementation |
|---|---|
| **User Data Export** | GDPR-inspired: users can request data export in JSON format. |
| **Right to Deletion** | Account deletion with 30-day grace period. Data anonymized, not purged (audit trail preserved). |
| **Privacy Policy** | Comprehensive policy in EN + Bangla. Cookie consent banner. |
| **Cross-Vendor Privacy** | RLS enforcement. Category velocity: aggregate only, min 3 vendors. |

---

## 20. Development Roadmap — 15-Month Plan

### Phase 1: Foundation + Compliance (Months 1–3)

| Month | Key Deliverables |
|---|---|
| **Month 1** | Monorepo (Turborepo + Next.js 15 + NestJS). PostgreSQL 16 + pgvector + Prisma schema (50+ tables). Docker containerization. Auth.js with RBAC (8 roles). Basic CI/CD via GitHub Actions. |
| **Month 2** | Redis 7 + BullMQ event bus. CQRS foundation with @nestjs/cqrs. Escrow system (regulatory). Bangla QR integration (pre-mandate). Meilisearch setup. |
| **Month 3** | Production payments: bKash + Nagad + SSLCommerz + Rocket + Bangla QR. Vendor KYC + compliance document pipeline. API Gateway + rate limiting. OpenTelemetry tracing. next-intl (EN+BN). |

### Phase 2: Revenue + Trust (Months 4–5)

| Month | Key Deliverables |
|---|---|
| **Month 4** | Subscription billing engine. Commission tracking per transaction. PRISM Wallet (cashback, refunds). PRISM Verified Program (3-tier KYC). Vendor onboarding wizard (Bangla). |
| **Month 5** | PRISM Protect (buyer protection + dispute resolution). Vendor disbursement engine (post-escrow). Flash Sale engine. Promoted listings system. Product catalog with Schema.org JSON-LD. |

### Phase 3: AI + GenAI (Months 6–8)

| Month | Key Deliverables |
|---|---|
| **Month 6** | GBR ONNX model training + deployment. Modules 01-03 (Forecast, Reorder, Velocity). Festival Calendar seeded. Weather API integration. Redis caching for AI. Cold-start seed system. |
| **Month 7** | Modules 04-06 (Coupon, Anomaly, VPS). Opportunity Engine (15-min scan). Bundle Recommendation Engine. Cross-vendor category emergence (hourly CRON). ML feedback loop. |
| **Month 8** | Ollama (Llama 3.2) deployment. RAG pipeline with pgvector. Sahayak V1 (advisor mode). Sahayak V2 (agentic mode with function calling). Bangla voice commands (Web Speech API). |

### Phase 4: Communication + Commerce (Months 9–10)

| Month | Key Deliverables |
|---|---|
| **Month 9** | WhatsApp Business API (12 templates, EN+BN). Buyer-seller in-app chat with AI auto-response. Notification center (multi-channel). PRISM Academy MVP (5 video modules, Bangla). Support ticket system. |
| **Month 10** | LiveKit live commerce integration. Shoppable video overlay + live Q&A. Short-form video (reels): recording, tagging, feed algorithm. Facebook Shops sync. TikTok Shop integration. |

### Phase 5: Logistics + Mobile (Months 11–12)

| Month | Key Deliverables |
|---|---|
| **Month 11** | 3PL integration (Pathao, RedX, Paperfly, Steadfast). Intelligent routing engine. COD intelligence (fraud scoring, history score). COD-to-digital incentive system. BNPL partner integration. |
| **Month 12** | POS Mode (PWA-based, barcode scan, Bangla QR). React Native MVP (Expo): browse, buy, chat, track, video feed. Referral/affiliate system. Advanced analytics dashboard. |

### Phase 6: Polish, Launch, Scale (Months 13–15)

| Month | Key Deliverables |
|---|---|
| **Month 13** | Security audit (OWASP ZAP + manual pentest). Load testing (k6: 10K concurrent). WCAG 2.2 AA audit. API versioning + schema governance. Content moderation tools. |
| **Month 14** | Beta launch: 50 vendors in Dhaka. Iterate on feedback. Bug fixes. Performance tuning. Onboarding support. PRISM Academy: remaining modules. |
| **Month 15** | Public launch (Dhaka). Marketing push. Vendor acquisition sprint. Investor preparation (if seeking). Scale to Chattogram + Sylhet. |

---

## 21. Team & Hiring Plan

### Phase 1–5 (Months 1–12): 4–5 People

| Role | Responsibility | Start |
|---|---|---|
| **Full-Stack Lead (Founder)** | Architecture, backend, AI, DevOps, everything | Day 1 |
| **Frontend Developer** | Next.js, React Native, Tailwind, PWA, mobile | Month 1 |
| **Backend Developer** | Payments, logistics, billing, compliance, escrow | Month 3 |
| **UI/UX Designer** | Design system, wireframes, brand identity, Bangla typography | Month 1 (contract/part-time) |
| **Growth / BD (Part-Time)** | Vendor acquisition, BD market outreach, partnerships | Month 4 |

### Phase 6+ (Months 13+): Scale to 7–10

| Role | Start |
|---|---|
| **ML/AI Engineer** | Month 7 |
| **QA Engineer** | Month 10 |
| **Customer Support (Bangla-speaking)** | Month 13 |
| **Marketing Lead** | Month 13 |
| **Finance/Operations** | Month 15 |

---

## 22. Risk Register & Mitigation

| # | Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|---|
| R1 | Vendor acquisition slower than projected | High | High | Field sales in Dhaka markets. Vendor referral bonus. PRISM Academy reduces onboarding friction. Free tier removes financial barrier. |
| R2 | GBR model returns poor predictions with seed data | Medium | High | Pre-train on public BD retail dataset + synthetic. Validate vs. WMA baseline. Fallback to WMA if GBR diverges >50%. |
| R3 | WhatsApp Bengali template approval delayed | Medium | Medium | Submit EN+BN templates in Month 1. Use English fallback + Meta test number for demo. |
| R4 | Bangla QR integration complexity | Medium | High | Start in Month 2 (well before June 2026 mandate). Test with 3+ banks. Fallback: bKash QR as interim. |
| R5 | Escrow system accounting errors | Low | Critical | Separate ledger with double-entry. Automated reconciliation. Daily audit. Legal counsel by Month 3. |
| R6 | 3PL partners API instability | Medium | Medium | Multi-3PL integration. Auto-failover. Manual assignment fallback. |
| R7 | Cash burn exceeds revenue | High | High | Conservative hiring. Revenue from Month 4 (commission on free tier). Keep infra < $150/mo until Month 8. |
| R8 | Daraz launches AI seller tools | Medium | Medium | Speed advantage: ship Sahayak first. Bangla-first moat hard to replicate. |
| R9 | LLM costs at scale | Medium | Medium | Ollama local = free. Cache frequent queries. Rate limit GenAI per tier. OpenAI only for Pro+. |
| R10 | Regulatory changes in BD e-commerce | Low | High | Legal counsel. Stay current with Bangladesh Bank circulars. Build compliance into platform DNA. |
| R11 | COD fraud rate too high | High | Medium | COD intelligence scoring. Gradual COD limit increase. COD-to-digital incentive. Block repeat offenders. |
| R12 | Content moderation at scale | Medium | Medium | AI-assisted screening. Community reporting. Dedicated content moderator from Month 13. |

---

## 23. Novelty & Emergence Argument

### 23.1 What Makes PRISM V4 Novel

PRISM V4 is novel at the **intersection** — no single platform combines all of these:

1. **Agentic AI + Bangla** — An AI assistant that can execute actions (not just advise) in Bangla. Shopify has Sidekick (English-only, no Bangladesh context). Nobody in Bangladesh has this.

2. **Three layers of intelligence:**
   - Layer 1: Per-product GBR forecasting (individual learning)
   - Layer 2: Self-improving feedback loop (per-product memory)
   - Layer 3: Cross-vendor category emergence (network intelligence)

3. **Full Bangladesh compliance** — Escrow + Bangla QR + VAT + Trade License integrated into the platform, not bolted on.

4. **Commerce + Intelligence + Trust** in one platform — No platform in Bangladesh offers AI forecasting + live commerce + short-form video + buyer protection + POS + social commerce simultaneously.

### 23.2 Three Layers of Emergence

```
Layer 1: INDIVIDUAL INTELLIGENCE
  GBR ONNX model → per-product forecast → learns from each product's history

Layer 2: SELF-IMPROVING INTELLIGENCE
  Weekly CRON → forecast vs. actual → error correction → retrain
  Result: forecasts get more accurate without human input

Layer 3: COLLECTIVE INTELLIGENCE (Cross-Vendor)
  All vendors' order_items → hourly category velocity aggregation
  → injected into every vendor's GBR → even new vendors benefit
  Result: genuine network emergence from independent transactions

Layer 4 (NEW V4): AGENTIC INTELLIGENCE
  Sahayak observes vendor patterns → proactively suggests actions
  → executes on approval → learns from vendor acceptance/rejection
  Result: AI assistant evolves per-vendor behavior preferences
```

---

## 24. Testing Strategy

| Type | Tool | Coverage | What |
|---|---|---|---|
| **Unit** | Jest (NestJS) | 80%+ services | GBR inference, order saga, escrow logic, coupon validation, ROP formula, anomaly Z-score, category velocity, Sahayak tool calls |
| **Integration** | Jest + Supertest | All endpoints | Auth flow, order flow, payment webhook, escrow lifecycle, WhatsApp dispatch, Sahayak agentic flow |
| **E2E** | Playwright | 8 critical flows | Buyer: browse → cart → checkout → tracking. Vendor: forecast → reorder alert. Admin: anomaly review. Live: go live → buy during stream. POS: scan → sell |
| **GBR Validation** | Custom Jest | Model quality | Smoke-test GBR vs. WMA. Validate festival feature injection. Validate weather impact on forecast. |
| **Security** | OWASP ZAP + manual | Auth, RLS, escrow | JWT enforcement, RLS isolation, escrow authorization, rate limiter, CORS, payment verification |
| **Load** | k6 | 10K concurrent | API response < 200ms p95, checkout under load, WebSocket stability |
| **Privacy** | Manual + automated | Cross-vendor isolation | Category velocity returns aggregate only. No cross-vendor leakage. Min 3 vendor threshold. |

---

## 25. Accessibility & Inclusivity

| Requirement | Implementation |
|---|---|
| **WCAG 2.1 AA** | All interactive elements meet contrast ratios. Screen reader compatible. Keyboard navigation. |
| **Bengali Font** | Hind Siliguri from Google Fonts. Loaded conditionally when locale=bn. Fallback: system sans-serif. |
| **Bengali Numerals** | `Intl.NumberFormat` with `locale='bn-BD'`. Currency ৳. Bengali date formatting. |
| **Voice Input** | Bangla voice commands for users who prefer speaking to typing. |
| **Mobile-First** | 375px primary breakpoint. Touch-friendly targets (min 44x44px). Bottom navigation. |
| **Offline Access** | PWA service worker caches vendor dashboard. POS mode works offline with sync. |
| **Low Bandwidth** | Lazy loading. Image optimization. Next.js PPR reduces initial payload. |

---

## 26. Financial Projections (Realistic)

### 26.1 Monthly Cost Breakdown (Self-Funding)

| Category | Month 1-3 | Month 4-6 | Month 7-12 | Month 13-15 |
|---|---|---|---|---|
| **Infrastructure** | ৳6,000/mo ($50) | ৳12,000/mo ($100) | ৳18,000/mo ($150) | ৳30,000/mo ($250) |
| **Team (salaries)** | ৳0 (solo) | ৳50,000/mo (2 part-time) | ৳150,000/mo (4 people) | ৳250,000/mo (6 people) |
| **Marketing** | ৳0 | ৳10,000/mo | ৳30,000/mo | ৳50,000/mo |
| **Legal / Compliance** | ৳10,000 (one-time) | ৳5,000/mo | ৳5,000/mo | ৳5,000/mo |
| **Tools / Licenses** | ৳3,000/mo | ৳5,000/mo | ৳8,000/mo | ৳10,000/mo |
| **Total Monthly** | **৳9,000** | **৳82,000** | **৳211,000** | **৳345,000** |
| **Total Monthly (USD)** | **~$75** | **~$690** | **~$1,775** | **~$2,900** |

### 26.2 Cumulative Investment Required

| Period | Cumulative Cost | Cumulative Revenue | Net Position |
|---|---|---|---|
| Month 3 | ৳27,000 | ৳22,300 | -৳4,700 |
| Month 6 | ৳273,000 | ৳113,550 | -৳159,450 |
| Month 12 | ৳1,539,000 | ৳735,000 | -৳804,000 |
| Month 15 | ৳2,574,000 | ৳1,850,000 | -৳724,000 |
| **Month 18** | ৳3,609,000 | ৳4,260,000 | **+৳651,000** ✅ |

> **Self-Funding Verdict:** With ~৳2.6M ($22K) personal investment spread over 15 months, break-even is achievable by Month 16-18. This is realistic for a solo founder with part-time help scaling to a small team.

---

## 27. Investor Pitch Summary (Optional Path)

> This section is here if you decide to seek external funding. Not required for self-funding.

### The Pitch (30-second version)

*"PRISM Commerce is building the Shopify for Bangladesh — but smarter. We're the first Bangla-native AI commerce platform with agentic AI, live commerce, and full regulatory compliance. 8 million SMEs have no digital tools. We're starting with 500 in Dhaka and growing to 10,000 in 24 months."*

### Key Metrics for Investors

| Metric | Value |
|---|---|
| TAM | $8B+ (Bangladesh e-commerce 2026) |
| SAM | $1.2B (SME tools + marketplace commissions) |
| SOM (24 months) | $2M (4,000 vendors, Mixed SaaS + commission) |
| Revenue (M24) | ৳4.08M/mo ($34K/mo) |
| Gross Margin | 65-80% |
| LTV:CAC (Y2) | 8:1 – 12:1 |

### Funding Ask (If Applicable)

| Round | Amount | Use |
|---|---|---|
| **Pre-Seed** | ৳15-25M ($125K-$210K) | 15 months runway: team (3-4 devs), infrastructure, marketing, legal |
| **Seed (Month 18+)** | ৳50-80M ($420K-$670K) | Scale nationwide, expand team to 15, warehouse partnerships, React Native V2 |

---

## 28. Self-Funding Viability Plan

### 28.1 Self-Funding Path (Primary Strategy)

| Phase | Period | Monthly Spend | Funded By |
|---|---|---|---|
| **Solo Build** | Month 1-3 | ৳9,000/mo | Personal savings |
| **First Hire** | Month 4-6 | ৳82,000/mo | Savings + early commission revenue |
| **Small Team** | Month 7-12 | ৳211,000/mo | Savings + growing revenue (reinvested) |
| **Scale Team** | Month 13-15 | ৳345,000/mo | Revenue should cover 80%+ by now |

### 28.2 Revenue Milestones (Self-Funding Gates)

| Gate | Milestone | Decision |
|---|---|---|
| **Gate 1 (Month 4)** | First 20 vendors on platform | Continue? If < 10, pivot strategy |
| **Gate 2 (Month 6)** | First ৳50K revenue month | Hire backend dev + designer |
| **Gate 3 (Month 9)** | First 100 vendors, ৳150K revenue | Validate product-market fit |
| **Gate 4 (Month 12)** | 500 vendors, ৳350K revenue | Decide: self-fund further OR seek external |
| **Gate 5 (Month 15)** | Public launch, ৳500K+ revenue | Profitable unit economics proven |

### 28.3 Cost Reduction Strategies

- **Infrastructure:** Hetzner VPS (€4.5/mo for 2 vCPU) instead of AWS/GCP. Cloudflare free tier for CDN/DNS.
- **AI:** Ollama local LLM = $0. OpenAI only as Pro+ fallback. ONNX GBR = free (in-process).
- **Marketing:** Focus on organic: vendor referrals, PRISM Academy content, social media, WhatsApp word-of-mouth.
- **Team:** Start solo. Hire part-time contractors before full-time. University interns for QA/support.
- **Tools:** Open-source stack throughout. No paid SaaS dependencies.

---

## 29. Growth Playbook

### 29.1 Vendor Acquisition Strategy (First 500)

| Channel | Target | Tactic |
|---|---|---|
| **Field Sales** | Chawkbazar, Mirpur, Uttara markets | Visit shops in person. Demo on tablet. Sign up on the spot. |
| **Facebook Groups** | BD vendor/seller groups (300K+ members) | Educational content → free tool → conversion |
| **WhatsApp Word-of-Mouth** | Vendor networks | Referral bonus: 1 month free Starter |
| **PRISM Academy** | YouTube + Facebook | Bangla tutorial videos → organic SEO → vendor sign-ups |
| **Partnership** | bKash / Nagad | Co-marketing: "Sell smarter with PRISM + bKash" |
| **Daraz Exodus** | Frustrated Daraz sellers | Target via Facebook ads: "Lower commission, smarter tools" |

### 29.2 Buyer Acquisition Strategy

| Channel | Tactic |
|---|---|
| **Content Commerce** | Short-form video reels → viral discovery → purchase |
| **Live Commerce Events** | Weekly PRISM Live: themed shopping events (Eid Fashion, Monsoon Essentials) |
| **Social Sharing** | Share product links + reels to Facebook, TikTok, WhatsApp |
| **Referral** | ৳100 wallet credit for both referrer and referee |
| **Flash Sales** | Weekly flash sales with deep discounts to drive traffic |
| **SEO** | Product pages with Schema.org markup → Google Shopping visibility |

### 29.3 Retention Strategy

| Tactic | Detail |
|---|---|
| **AI Value Loop** | The more data vendors provide, the smarter their forecasts become → natural lock-in |
| **PRISM Academy** | Ongoing education keeps vendors engaged and discovering features |
| **Weekly Reports** | Automated WhatsApp digest with key metrics + actionable insights |
| **Gamification** | Monthly "Top Vendor" awards. Certification badges. Milestone celebrations. |
| **Community** | Vendor forum + success stories → peer learning + belonging |

---

## 30. Glossary

| Term | Definition |
|---|---|
| **GBR** | Gradient Boosting Regressor — a machine learning model that builds many decision trees |
| **ONNX** | Open Neural Network Exchange — a format for ML models that runs on any platform |
| **ROP** | Reorder Point — the inventory level at which a new order should be placed |
| **VPS** | Vendor Performance Score — PRISM's composite trust score for vendors |
| **CQRS** | Command Query Responsibility Segregation — separate read and write data paths |
| **RLS** | Row-Level Security — PostgreSQL feature ensuring vendors can only access own data |
| **3PL** | Third-Party Logistics — external delivery service providers |
| **COD** | Cash On Delivery — buyer pays cash when receiving the product |
| **MFS** | Mobile Financial Services — bKash, Nagad, Rocket |
| **Bangla QR** | Bangladesh national standardized QR payment system |
| **Escrow** | Payment held by a trusted third party until transaction conditions are met |
| **BNPL** | Buy Now, Pay Later — installment payment option |
| **RAG** | Retrieval-Augmented Generation — AI technique combining search with LLM generation |
| **pgvector** | PostgreSQL extension for storing and querying vector embeddings |
| **BullMQ** | Node.js library for managing background job queues with Redis |
| **Saga** | Pattern for managing distributed transactions across multiple services |
| **PPR** | Partial Pre-Rendering — Next.js 15 feature for streaming static + dynamic content |
| **SFU** | Selective Forwarding Unit — architecture for low-latency video streaming |
| **LLM** | Large Language Model — AI model for natural language understanding and generation |
| **MCP** | Model Context Protocol — standard for AI agents to interact with external tools |
| **POS** | Point of Sale — system for processing in-store transactions |
| **KYC** | Know Your Customer — identity verification process for vendors |
| **GMV** | Gross Merchandise Volume — total value of products sold through the platform |
| **CAC** | Customer Acquisition Cost — cost to acquire one new vendor/buyer |
| **LTV** | Lifetime Value — total revenue expected from a customer over their lifetime |
| **PWA** | Progressive Web App — web app installable on mobile with offline capabilities |

---

*PRISM Commerce V4.0 — Production-Grade Startup Edition*  
*Document Version: 4.0.0 | April 2026*  
*Author: Sagar Biswas*  
*"The platform that makes Daraz, Shopify, and Netstock unnecessary for Bangladeshi SMEs."*

---

## 31. Diagram Clarification Spec (Batch A: IDs 1-11)

This section is the normative diagram specification for Mermaid Diagram IDs 1-11. It is added to make every connection, protocol, dependency, and failure path explicit before diagram generation.

### 31.1 Scope and Conventions

- **Scope:** System Architecture and CQRS/Event Sourcing diagram set (IDs 1-11).
- **Authority:** This section extends Sections 8, 13, 14, 15, 17, and 18 for visualization precision.
- **Protocol labels:**
  - `HTTPS REST`: Client and admin API calls.
  - `WSS`: Real-time chat/order push and live interactions.
  - `Redis protocol`: cache and queue transport.
  - `PostgreSQL protocol`: database reads/writes/replication.
  - `Webhook HTTPS`: payment callback integrations.
- **Write path principle:** Commands always append events and commit write model first.
- **Read path principle:** Queries prefer Redis/meilisearch/read replica; no command-side mutations.
- **Failure notation:** Every critical flow must include negative path plus compensating action.

### 31.2 Diagram 1 — PRISM V4 High-Level System Architecture Overview

Required layers and components:

1. **Experience Layer**: Buyer Web (Next.js), Vendor Web (Next.js), Admin Console, React Native Mobile App.
2. **Edge Layer**: Cloudflare CDN/WAF + API Gateway (Nginx/Kong style responsibilities).
3. **Application Layer**: NestJS Modular Monolith (Auth, Product, Order, Payment, Escrow, AI, Notification, Compliance, Analytics).
4. **Data and Search Layer**: PostgreSQL Primary, PostgreSQL Read Replica, Redis, Meilisearch, pgvector extension.
5. **Intelligence Layer**: ONNX Runtime (GBR inference), Sahayak Agentic Runtime (Ollama primary, GPT fallback).
6. **Integration Layer**: Payment gateways, WhatsApp Cloud API, 3PL providers, OpenWeatherMap, LiveKit, social channels.
7. **Observability Layer**: Prometheus, Grafana, Loki, Sentry, OpenTelemetry/Tempo.

Required edges:

- Clients -> Cloudflare (`HTTPS`)
- Cloudflare -> API Gateway (`HTTPS`)
- API Gateway -> NestJS (`HTTPS` internal)
- NestJS -> PostgreSQL Primary (`write`)
- NestJS -> PostgreSQL Replica (`read`)
- NestJS <-> Redis (`cache`, `queue`, `pub/sub`)
- NestJS <-> Meilisearch (`index`, `search`)
- NestJS <-> ONNX Runtime (`in-process inference`)
- NestJS <-> LLM runtime (`tool-calling`, `response generation`)
- NestJS -> External providers (`HTTPS API` / `Webhook callback`)

### 31.3 Diagram 2 — Turborepo Monorepo Workspace Structure

Required monorepo structure (authoritative for diagrams):

```text
PRISM-Commerce/
  apps/
    web/                 # Next.js 15 (buyer/vendor/admin web app)
    api/                 # NestJS modular monolith
  packages/
    ui/                  # shared UI primitives and design tokens
    config/              # shared tsconfig/eslint/prettier/env schema
    types/               # shared DTO and domain types
    sdk/                 # typed API client and helpers
  infra/
    docker/              # compose files and docker assets
    monitoring/          # grafana/prometheus/loki/tempo configs
    scripts/             # deploy, backup, migration scripts
  docs/
    diagrams/            # diagram sources and conventions
```

Required workspace relationships:

- `apps/web` depends on `packages/ui`, `packages/types`, `packages/sdk`, `packages/config`.
- `apps/api` depends on `packages/types`, `packages/config`.
- `packages/sdk` depends on `packages/types`.
- Turborepo cache is shared across `build`, `lint`, `test`, and `typecheck` pipelines.

### 31.4 Diagram 3 — NestJS Modular Monolith Module Dependency Map

Required modules:

- `AuthModule`
- `UserModule`
- `ProductModule`
- `OrderModule`
- `PaymentModule`
- `EscrowModule`
- `LogisticsModule`
- `AIModule`
- `NotificationModule`
- `ComplianceModule`
- `AnalyticsModule`
- `AdminModule`
- `EventStoreModule`

Required dependency rules:

- `OrderModule` depends on `ProductModule`, `PaymentModule`, `EscrowModule`, `LogisticsModule`, `NotificationModule`, `EventStoreModule`.
- `PaymentModule` depends on `ComplianceModule` and `EventStoreModule`.
- `AIModule` reads from `AnalyticsModule` and `EventStoreModule` projections, then emits recommendations via `NotificationModule`.
- `AdminModule` orchestrates cross-module operations but must not bypass `AuthModule` and `ComplianceModule` authorization checks.
- Cyclic dependency is prohibited; cross-cutting interactions happen through commands/events.

### 31.5 Diagram 4 — Docker Compose Service Topology

Required compose services for architecture diagrams:

- `web` (Next.js app)
- `api` (NestJS API)
- `postgres-primary`
- `postgres-replica`
- `redis`
- `meilisearch`
- `ollama`
- `prometheus`
- `grafana`
- `loki`
- `tempo`

Required service dependencies:

- `web` depends on `api`.
- `api` depends on `postgres-primary`, `redis`, `meilisearch`.
- `postgres-replica` replicates from `postgres-primary`.
- `prometheus`, `loki`, and `tempo` scrape/collect from `api`, `web`, and data services.
- `grafana` reads from `prometheus`, `loki`, and `tempo`.

Required resilience labels:

- healthcheck probes on `web`, `api`, `postgres-primary`, `redis`, `meilisearch`.
- restart policy for critical services (`unless-stopped` equivalent behavior).

### 31.6 Diagram 5 — Production Deployment Architecture

Required production topology components:

1. **User traffic edge**: DNS + CDN + WAF at Cloudflare.
2. **Compute**: Hetzner VPS cluster path (initially single VPS in Phase 1/2, scale-ready layout shown).
3. **Runtime containers**: web/api/worker and supporting data/search/monitoring stack.
4. **External managed systems**: payment gateways, WhatsApp, weather provider, live/video/social APIs.
5. **Backup plane**: encrypted backup target for PostgreSQL and event-store retention.

Required network/control paths:

- Public traffic only enters via Cloudflare.
- Direct DB public exposure is disallowed.
- Outbound egress from API to external services is allowlisted.
- Admin access to infrastructure is restricted to secure channels.

### 31.7 Diagram 6 — Service Communication Map (Protocol and Purpose)

The map must include both protocol and business purpose labels on each edge:

- `Client -> API Gateway` (`HTTPS REST`, purpose: user/business operations)
- `API Gateway -> API` (`HTTPS`, purpose: route + auth + throttling)
- `API -> PostgreSQL Primary` (`PostgreSQL`, purpose: command-side writes)
- `API -> PostgreSQL Replica` (`PostgreSQL`, purpose: query-side reads)
- `API <-> Redis` (`Redis protocol`, purpose: cache/session/queue/pubsub)
- `API <-> Meilisearch` (`HTTP`, purpose: lexical search index/query)
- `API <-> ONNX Runtime` (`local runtime`, purpose: forecast inference)
- `API <-> LLM Runtime` (`HTTP`, purpose: tool-calling assistant responses)
- `API -> Payment Gateways` (`HTTPS`, purpose: payment initiate/verify)
- `Payment Gateways -> API` (`Webhook HTTPS`, purpose: payment status callback)
- `API -> WhatsApp` (`HTTPS`, purpose: templated notifications)
- `API -> 3PL` (`HTTPS`, purpose: shipment create/track)

### 31.8 Diagram 7 — CQRS Write Path (Command Handler to Event Store)

Required write-flow sequence:

1. Client submits command (`PlaceOrderCommand`, `ApplyCouponCommand`, etc.).
2. API gateway authenticates and forwards.
3. Command bus dispatches to command handler.
4. Handler validates business rules and authorization.
5. Handler writes transactional changes on primary write model.
6. Handler appends domain event to `event_store` with aggregate/version metadata.
7. Event publish to queue/pubsub for projectors and side effects.
8. Response returns command outcome and correlation ID.

Required failure branches:

- validation failure -> reject command, no write, no event append.
- transaction failure -> rollback, emit technical failure log.
- event append failure after write attempt -> transaction rollback policy applies (write + append atomicity requirement).

### 31.9 Diagram 8 — CQRS Read Path (Query Handler to Materialized Views)

Required read-flow sequence:

1. Client submits query.
2. Query bus dispatches to query handler.
3. Handler checks Redis/materialized cache first.
4. On cache miss, handler reads from read replica and/or meilisearch.
5. Handler assembles DTO response (no write-side mutation).
6. Optional cache refresh with TTL.

Required behavior notes:

- read path must remain side-effect free.
- stale data tolerance is explicit: forecast cache 24h, category velocity 1h, weather 6h, opportunity 15m.

### 31.10 Diagram 9 — Event Store (Aggregate Types and Projection Flow)

Required aggregate types in visualization:

- `OrderAggregate`
- `PaymentAggregate`
- `EscrowAggregate`
- `InventoryAggregate`
- `VendorAggregate`

Required event metadata fields:

- `aggregate_id`
- `aggregate_type`
- `event_type`
- `event_data`
- `version`
- `created_at`

Required projection flow:

1. Event appended to `event_store`.
2. Projector consumes event.
3. Read models/materialized views updated (`orders`, analytics summaries, search documents, notification state).
4. Cache invalidation or refresh is triggered for affected keys.

### 31.11 Diagram 10 — Order Saga (5 Steps + Compensations)

Required distributed transaction steps:

1. Reserve inventory.
2. Process payment.
3. Hold escrow.
4. Confirm order.
5. Assign logistics.

Required compensations:

- If Step 2 fails: release inventory.
- If Step 3 fails: refund payment and release inventory.
- If Step 5 fails: refund payment, release inventory, and mark order failed.

Required messaging outputs:

- buyer/vendor notification on both success and failure.
- finance/admin alert on escrow or payment compensation paths.

### 31.12 Diagram 11 — Saga Failure Recovery Flowchart

Required decision nodes:

1. Inventory reserved?
2. Payment captured?
3. Escrow held?
4. Logistics assigned?
5. Compensation completed?

Required terminal states:

- `OrderConfirmed` (all saga steps passed)
- `OrderFailedCompensated` (rollback completed)
- `OrderFailedManualIntervention` (compensation did not fully complete)

Required manual intervention branch:

- If any compensation fails, create incident, freeze related financial records, and escalate to support/finance for controlled reconciliation.

### 31.13 Diagram Generation Compliance Checklist (for IDs 1-11)

- Include actors, systems, and stores explicitly.
- Label every connection with protocol and purpose.
- Include at least one failure branch in each process-heavy diagram.
- Keep command and query paths separate where CQRS applies.
- Preserve module boundaries and avoid implying cyclic dependencies.

---

## 32. Diagram Clarification Spec (Batch B: IDs 12-22)

This section is the normative diagram specification for Mermaid Diagram IDs 12-22. It extends Sections 10, 11, 12, 14, 15, 17, and 20 with explicit ERD relationships and payment/escrow execution paths.

### 32.1 Scope and Conventions

- **Scope:** Database schema ERDs (12-18) and payment/escrow flows (19-22).
- **Authority:** This section is authoritative for visualization details in Batch B.
- **ERD notation:**
  - `PK` and `FK` fields are mandatory in ERD table definitions.
  - Cardinality must be explicit on all relationship edges.
  - Array/json references (for example `product_ids[]`) are modeled as reference lists, not strict FK constraints.
- **Flow notation:**
  - All payment flows include success path, gateway/webhook verification, and failure path.
  - Escrow/disbursement flows include financial controls, audit logs, and retry/escalation behavior.

### 32.2 Diagram 12 - Core Commerce ERD

Required entities:

- `users`
- `vendors`
- `products`
- `product_variants`
- `categories`
- `orders`
- `order_items`
- `coupons`
- `reviews`
- `wishlists`

Required relationships:

- `users (1) -> (0..1) vendors` via `vendors.user_id`
- `users (1) -> (0..N) orders` via `orders.buyer_id`
- `vendors (1) -> (0..N) products` via `products.vendor_id`
- `categories (1) -> (0..N) products` via `products.category_id`
- `categories (1) -> (0..N) categories` via `categories.parent_id`
- `products (1) -> (0..N) product_variants` via `product_variants.product_id`
- `orders (1) -> (1..N) order_items` via `order_items.order_id`
- `products (1) -> (0..N) order_items` via `order_items.product_id`
- `product_variants (1) -> (0..N) order_items` via `order_items.variant_id`
- `vendors (1) -> (0..N) coupons` via `coupons.vendor_id`
- `users (1) -> (0..N) reviews` via `reviews.buyer_id`
- `products (1) -> (0..N) reviews` via `reviews.product_id`
- `orders (1) -> (0..N) reviews` via `reviews.order_id`
- `users (1) -> (0..N) wishlists` via `wishlists.buyer_id`
- `products (1) -> (0..N) wishlists` via `wishlists.product_id`

### 32.3 Diagram 13 - AI and Intelligence ERD

Required entities:

- `ai_forecasts`
- `forecast_accuracy`
- `festival_calendar`
- `category_velocity`
- `weather_cache`
- `synthetic_sales_seed`
- `opportunity_alerts`
- `bundle_suggestions`
- `sahayak_conversations`

Required relationships:

- `products (1) -> (0..N) ai_forecasts` via `ai_forecasts.product_id`
- `ai_forecasts (1) -> (0..N) forecast_accuracy` via `forecast_accuracy.forecast_id`
- `categories (1) -> (0..N) category_velocity` via `category_velocity.category_id`
- `products (1) -> (0..N) synthetic_sales_seed` via `synthetic_sales_seed.product_id`
- `vendors (1) -> (0..N) opportunity_alerts` via `opportunity_alerts.vendor_id`
- `products (1) -> (0..N) opportunity_alerts` via `opportunity_alerts.product_id`
- `vendors (1) -> (0..N) bundle_suggestions` via `bundle_suggestions.vendor_id`
- `users (1) -> (0..N) sahayak_conversations` via `sahayak_conversations.user_id`

Reference-list note:

- `bundle_suggestions.product_ids[]` is modeled as a product reference list for recommendation groups.

### 32.4 Diagram 14 - Trust and Compliance ERD

Required entities:

- `escrow_transactions`
- `verification_levels`
- `compliance_documents`
- `buyer_protection_claims`
- `brand_authorizations`
- `counterfeit_reports`
- `bangla_qr_codes`
- `vat_records`

Required relationships:

- `orders (1) -> (0..N) escrow_transactions` via `escrow_transactions.order_id`
- `users (1) -> (0..N) escrow_transactions` via `escrow_transactions.buyer_id`
- `vendors (1) -> (0..N) escrow_transactions` via `escrow_transactions.vendor_id`
- `vendors (1) -> (0..N) verification_levels` via `verification_levels.vendor_id`
- `vendors (1) -> (0..N) compliance_documents` via `compliance_documents.vendor_id`
- `orders (1) -> (0..N) buyer_protection_claims` via `buyer_protection_claims.order_id`
- `users (1) -> (0..N) buyer_protection_claims` via `buyer_protection_claims.buyer_id`
- `vendors (1) -> (0..N) buyer_protection_claims` via `buyer_protection_claims.vendor_id`
- `vendors (1) -> (0..N) brand_authorizations` via `brand_authorizations.vendor_id`
- `products (1) -> (0..N) counterfeit_reports` via `counterfeit_reports.product_id`
- `users (1) -> (0..N) counterfeit_reports` via `counterfeit_reports.reporter_id`
- `vendors (1) -> (0..N) bangla_qr_codes` via `bangla_qr_codes.vendor_id`
- `vendors (1) -> (0..N) vat_records` via `vat_records.vendor_id`

### 32.5 Diagram 15 - Financial ERD

Required entities:

- `wallets`
- `wallet_transactions`
- `vendor_disbursements`
- `subscription_billing`
- `commission_records`
- `flash_sale_slots`

Required relationships:

- `users (1) -> (0..N) wallets` via `wallets.user_id`
- `wallets (1) -> (0..N) wallet_transactions` via `wallet_transactions.wallet_id`
- `vendors (1) -> (0..N) vendor_disbursements` via `vendor_disbursements.vendor_id`
- `vendors (1) -> (0..N) subscription_billing` via `subscription_billing.vendor_id`
- `orders (1) -> (0..N) commission_records` via `commission_records.order_id`
- `vendors (1) -> (0..N) commission_records` via `commission_records.vendor_id`
- `vendors (1) -> (0..N) flash_sale_slots` via `flash_sale_slots.vendor_id`
- `products (1) -> (0..N) flash_sale_slots` via `flash_sale_slots.product_id`

### 32.6 Diagram 16 - Engagement ERD

Required entities:

- `live_streams`
- `short_form_videos`
- `chat_messages`
- `notifications`
- `affiliate_tracking`
- `referral_codes`
- `academy_progress`
- `pos_transactions`

Required relationships:

- `vendors (1) -> (0..N) live_streams` via `live_streams.vendor_id`
- `vendors (1) -> (0..N) short_form_videos` via `short_form_videos.vendor_id`
- `users (1) -> (0..N) chat_messages` via `chat_messages.sender_id`
- `users (1) -> (0..N) chat_messages` via `chat_messages.receiver_id`
- `orders (1) -> (0..N) chat_messages` via `chat_messages.order_id`
- `users (1) -> (0..N) notifications` via `notifications.user_id`
- `users (1) -> (0..N) affiliate_tracking` via `affiliate_tracking.affiliate_id`
- `products (1) -> (0..N) affiliate_tracking` via `affiliate_tracking.product_id`
- `users (1) -> (0..N) referral_codes` via `referral_codes.user_id`
- `vendors (1) -> (0..N) academy_progress` via `academy_progress.vendor_id`
- `vendors (1) -> (0..N) pos_transactions` via `pos_transactions.vendor_id`
- `products (1) -> (0..N) pos_transactions` via `pos_transactions.product_id`
- `product_variants (1) -> (0..N) pos_transactions` via `pos_transactions.variant_id`

Reference-list note:

- `short_form_videos.tagged_products[]` and `live_streams.products_featured[]` are modeled as product reference lists.

### 32.7 Diagram 17 - System ERD

Required entities:

- `audit_logs`
- `event_store`
- `api_keys`
- `content_moderation_queue`

Required relationships:

- `users (1) -> (0..N) audit_logs` via `audit_logs.actor_id`
- `vendors (1) -> (0..N) api_keys` via `api_keys.vendor_id`
- `users (1) -> (0..N) content_moderation_queue` via `content_moderation_queue.moderator_id`

System behavior notes for diagram labeling:

- `event_store` is append-only and stores aggregate/event version history for CQRS.
- `audit_logs` is append-only with agent action flagging.
- `content_moderation_queue` tracks lifecycle `queued -> under_review -> resolved`.

### 32.8 Diagram 18 - Full Cross-Domain Relationship Map

Diagram 18 must include all domain tables explicitly documented in Section 14 and show cross-domain links.

Required domain groups:

- Core Commerce
- AI and Intelligence
- Trust and Compliance
- Financial
- Engagement
- System

Required cross-domain relationship spine:

- Commerce transactions (`orders`, `order_items`) drive AI, financial, and trust records.
- Trust records (`escrow_transactions`, `buyer_protection_claims`) bind to order/vendor/buyer entities.
- Financial records (`commission_records`, `vendor_disbursements`, `wallet_transactions`) derive from completed commerce and escrow outcomes.
- Engagement records link to users/vendors/products and feed analytics/AI context.
- System records (`event_store`, `audit_logs`) capture immutable operational history across domains.

### 32.9 Diagram 19 - Payment Gateway Integration Flow

Required channels in one diagram:

- `bKash`
- `Nagad`
- `SSLCommerz`
- `Bangla QR`
- `Rocket`

Required flow steps:

1. Buyer initiates checkout and selects payment method.
2. Platform creates payment intent and redirects or displays payment payload.
3. Buyer authorizes payment through provider.
4. Provider returns callback/webhook.
5. Platform performs server-side signature and transaction verification.
6. On success: emit payment-confirmed event and continue saga.
7. On failure: emit payment-failed event and return recovery options.

Required failure branches:

- webhook signature mismatch -> reject callback and log security event.
- provider timeout/decline -> mark payment failed and keep order unconfirmed.

### 32.10 Diagram 20 - Escrow System (Double-Entry Ledger and Lifecycle)

Required lifecycle states:

- `Held`
- `Released`
- `Disputed`
- `Refunded`

Required lifecycle transitions:

- `Held -> Released` (buyer confirms or 48h auto-release post-delivery)
- `Held -> Disputed` (buyer files claim)
- `Disputed -> Refunded` (claim accepted)
- `Disputed -> Released` (claim rejected)

Required accounting controls:

- escrow ledger entry on hold, release, dispute freeze, refund.
- mirrored wallet/disbursement entries for net settlement.
- daily reconciliation check between escrow releases and payout credits.

### 32.11 Diagram 21 - Vendor Disbursement Pipeline

Required pipeline sequence:

1. Escrow release event received.
2. Compute deductions: commission and applicable fees.
3. Create disbursement record (`pending`).
4. Queue payout job by selected method (`bKash`/`Nagad`).
5. Execute provider payout API.
6. Update disbursement status (`processed`/`failed`).
7. Notify vendor and append audit log.

Required failure handling:

- payout failure -> retry with backoff and maintain immutable attempt history.
- repeated failure threshold -> move to manual finance review queue.

### 32.12 Diagram 22 - Bangla QR Payment Flow (POS and Online)

Required dual entry paths in one diagram:

- **In-store POS path**
  - POS generates Bangla QR payload.
  - Buyer scans via banking/MFS app.
  - Bank confirms payment.
  - POS marks transaction paid and updates inventory.
- **Online checkout path**
  - Checkout renders Bangla QR intent.
  - Buyer scans and pays.
  - Callback/webhook verified server-side.
  - Order payment status confirmed and escrow hold applied for prepaid order.

Required controls:

- unique payment reference correlation between QR intent and settlement callback.
- duplicate callback/idempotency protection.

### 32.13 Diagram Generation Compliance Checklist (for IDs 12-22)

- Use ERD diagrams for IDs 12-17 and include explicit PK/FK markers.
- Include required cardinalities for all listed relationships.
- Ensure Diagram 18 includes all Section 14 domain tables and cross-domain links.
- Include success and failure branches for payment/escrow/disbursement flows (19-22).
- Label financial control points (verification, reconciliation, idempotency, audit).

---

## 33. Diagram Clarification Spec (Batch C: IDs 23-34)

This section is the normative diagram specification for Mermaid Diagram IDs 23-34. It extends Sections 8.4, 9.2, 10, 12.1, 13, 14, 15, 17, and 20 to make AI/ML and agentic workflow behavior explicit before diagram generation.

### 33.1 Scope and Conventions

- **Scope:** AI/ML inference, feedback, aggregation, optimization, and agentic orchestration diagrams (23-34).
- **Authority:** This section is authoritative for Batch C visualization details.
- **Flow labeling requirements:**
  - Include endpoint labels for API interactions (for example, `GET /api/ai/forecast/:productId`).
  - Include cadence labels for scheduled jobs (`hourly`, `15min`, `daily 6 AM`, `weekly Sunday midnight`).
  - Include cache TTL labels (`24h`, `6h`, `1h`, `15m`) where applicable.
- **Control requirements:**
  - Include at least one failure/degradation path for each process-heavy diagram.
  - Show state persistence targets explicitly (`ai_forecasts`, `forecast_accuracy`, `category_velocity`, `weather_cache`, `opportunity_alerts`, `bundle_suggestions`, `sahayak_conversations`, `audit_logs`).

### 33.2 Diagram 23 - GBR ONNX Forecast Inference Dataflow

Required components:

- Vendor Dashboard or API consumer
- Forecast endpoint (`GET /api/ai/forecast/:productId`)
- Feature assembly stage with all 13 features
- ONNX runtime inference (`onnxruntime-node`)
- `ai_forecasts` persistence
- Redis forecast cache (24h TTL)

Required flows:

1. Request arrives for product forecast.
2. Cache lookup performed.
3. On miss, feature vector is assembled from sales history + festival + weather + category velocity.
4. ONNX inference executes and returns `{ forecast_7d, forecast_14d, forecast_30d, confidence, feature_importance, model_version, data_quality_score }`.
5. Result persisted to `ai_forecasts` and cached.

Required failure/degradation branches:

- If model runtime fails, return controlled failure and log to observability.
- If upstream context is partially unavailable, continue with last valid cached context where policy allows and mark degraded confidence.

### 33.3 Diagram 24 - Cold-Start Bootstrap and Data Quality Lifecycle

Required lifecycle stages:

- Tier 1: onboarding seed (`synthetic_sales_seed`)
- Tier 2: mixed real + seed data
- Tier 3: fully real data (seed deprecated at day 90+)

Required transitions:

- Onboarding -> first real orders
- Week 1+ blending period with rising `data_quality_score`
- Day 90+ transition to `data_quality_score = 1.0`

Required decision/fallback branches:

- If vendor does not submit seed, system must show low-confidence baseline behavior path.
- If real order volume remains sparse, continue mixed-mode forecasting with explicit confidence constraints.

### 33.4 Diagram 25 - Smart Reorder Point (ROP) and Alert Routing

Required formula blocks:

- `ROP = (Avg Daily Demand x Lead Time) + Safety Stock`
- `Safety Stock = Z(1.65) x StdDev x sqrt(Lead Time)`
- Festival and weather multipliers explicitly shown

Required inputs:

- Forecast demand from Module 01
- Learned lead time
- Festival proximity (`days_to_festival < 14`)
- Weather regime impact

Required outputs/decisions:

- `reorder_point`, `reorder_quantity`, `urgency_flag`
- Decision branch for `stock_on_hand <= ROP`
- Alert fanout path to WhatsApp / in-app notifications

Required fallback branch:

- If lead-time learning data is missing, use default lead-time policy and mark output as lower-confidence.

### 33.5 Diagram 26 - Sales Velocity Ranking and Trend Classification

Required flow elements:

- `GET /api/ai/velocity` request path
- Exponential smoothing over rolling 7-day sales rate
- Trend classification (`accelerating`, `stable`, `decelerating`)
- Ranked output for dashboard consumption

Required action branches:

- Accelerating -> buyer-side trending shelf + positive vendor signal
- Decelerating -> warning + coupon optimization trigger path

Required cache annotation:

- Redis 1h TTL for velocity response.

### 33.6 Diagram 27 - Coupon Optimization Advisor Decision Flow

Required entry points:

- Direct API call (`POST /api/ai/coupon-optimize`)
- Auto-trigger when supply days > 45
- Sahayak-initiated call path

Required logic blocks:

- `Optimal Discount = (Surplus Ratio - 1) / Price Elasticity`
- Festival urgency modifier
- Max discount guardrail

Required outputs:

- `recommended_discount_pct`
- `expected_units_moved`
- `expected_revenue`
- `estimated_days_to_clear`
- `coupon_code_suggestion`

Required failure/guard branch:

- If suggested discount violates policy bounds, return constrained recommendation and rationale.

### 33.7 Diagram 28 - Order Anomaly Detection and Admin Triage

Required asynchronous pipeline:

- Order event -> BullMQ anomaly job -> signal extraction -> composite scoring -> admin action

Required signal set (all six shown):

- `order_frequency_z`
- `quantity_z`
- `address_mismatch`
- `payment_method_age`
- `device_fingerprint_score`
- `cod_history_score`

Required decision nodes:

- Composite score > 2.5 -> suspicious, soft-pause order
- Composite score <= 2.5 -> proceed

Required triage actions:

- Admin dashboard `Clear` / `Escalate`
- Auditability of triage decision

Required failure branch:

- If one signal source is unavailable, use partial scoring with explicit degraded-risk marker.

### 33.8 Diagram 29 - Vendor Performance Score (VPS) Computation and Tiering

Required inputs and weights:

- Fulfillment Rate (35%)
- Avg Rating (25%)
- Response-to-Ship Time (15%)
- Delivery Accuracy (15%)
- Dispute Rate (10%)

Required schedule paths:

- Recalculate on each delivery event
- Weekly full refresh

Required tier decisions:

- Platinum (85+)
- Gold (70-84)
- Silver (50-69)
- Watch (<50)

Required action branches:

- Platinum incentives path
- Watch warning/suspension-risk path

### 33.9 Diagram 30 - Cross-Vendor Category Emergence (Hourly Aggregation)

Required pipeline:

1. Hourly CRON reads `order_items` aggregates by category.
2. Computes `category_velocity_score`.
3. Enforces privacy threshold (`vendor_count >= 3`).
4. Writes `category_velocity` table + Redis cache (1h TTL).
5. Publishes feature for GBR injection.

Required privacy branch:

- Categories below threshold must be excluded from published aggregate output.

### 33.10 Diagram 31 - Closed-Loop Forecast Feedback and Retraining Trigger

Required cadence and computations:

- Weekly CRON (Sunday midnight)
- Compare predicted vs actual
- `forecast_error = abs(predicted - actual) / actual`
- Update `forecast_accuracy`

Required trigger logic:

- Product-level flag if `rolling_avg_error > 0.25`
- Full retrain trigger if >30% products flagged

Required failure branch:

- Retrain failure path must keep prior model version active and record incident for follow-up.

### 33.11 Diagram 32 - Weather-Aware Demand Signal Pipeline

Required flow:

1. Daily CRON fetch from OpenWeatherMap at 6 AM Bangladesh time.
2. Derive `temperature_avg`, `precipitation_mm`, `is_monsoon`.
3. Persist/update `weather_cache` and Redis (6h TTL).
4. Inject weather-derived signals into demand and ROP calculations.

Required mapping annotation:

- Include impact-matrix examples (for example monsoon boosts rain gear, suppresses outdoor categories).

Required degradation branch:

- If provider call fails, serve last valid cached weather and flag stale-data condition.

### 33.12 Diagram 33 - Agentic Sahayak V2 Tool-Calling Orchestration

Required sequence participants:

- Vendor (dashboard or chat channel)
- Sahayak endpoint (`POST /api/ai/sahayak/chat`)
- LLM runtime (Ollama primary, GPT fallback)
- RAG retrieval context
- Tool APIs (`get_velocity`, `coupon_optimize`, coupon creation path)
- Persistence (`sahayak_conversations`, `audit_logs`)

Required execution sequence:

1. Intent parse in Bangla/English.
2. RAG/context retrieval for vendor-specific grounding.
3. Ordered tool calls to compute and stage actions.
4. Human confirmation step before irreversible mutations.
5. Final response with action summary.

Required fallback and safety branches:

- LLM fallback policy path (tier-aware GPT fallback).
- Tool-call failure path that returns partial advisory response without silent mutation.

### 33.13 Diagram 34 - RAG Search + Opportunity + Bundle Intelligence Flow

Required combined pipelines:

- **RAG semantic search path:** embed query -> pgvector similarity -> Meilisearch merge (RRF) -> ranked result set.
- **Opportunity path:** 15-minute scan -> alert classification (red/yellow/green/blue) -> action suggestions.
- **Bundle path:** weekly co-purchase computation -> top 5 bundle suggestions.

Required convergence points:

- Vendor dashboard consumption
- Sahayak context/tool usage
- Persistence to `opportunity_alerts` and `bundle_suggestions`

Required failure branches:

- Embedding/index lag -> queued regeneration path
- Opportunity scan miss -> stale alert flag and retry scheduling
- Bundle computation miss -> retain last successful bundle snapshot with timestamp

### 33.14 Diagram Generation Compliance Checklist (for IDs 23-34)

- Label all endpoints and background cadences explicitly.
- Include cache TTL annotations where applicable.
- Include explicit decision nodes for thresholds (`2.5`, `0.25`, `30%`, privacy floor `3 vendors`).
- Include at least one failure/degradation path per diagram.
- Preserve agentic safety: no implicit mutation without a visible confirmation/control path.

---

## 34. Diagram Clarification Spec (Batch D: IDs 35-45)

This section is the normative diagram specification for Mermaid Diagram IDs 35-45. It extends Sections 7, 8.2, 8.3, 9.1, 9.3, 9.4, 15, 17, and 19 for security and order-lifecycle visualization precision.

### 34.1 Scope and Conventions

- **Scope:** Authentication/security diagrams (35-40) and order lifecycle diagrams (41-45).
- **Authority:** This section is authoritative for Batch D visualization details.
- **Security notation requirements:**
  - Include verification and authorization gates explicitly.
  - Include idempotency and audit steps on payment and escrow-sensitive paths.
- **Lifecycle notation requirements:**
  - Include the canonical state sequence: `Pending -> Confirmed -> Processing -> Picked Up -> In Transit -> Delivered -> Completed`.
  - Include failure/dispute branches where applicable.

### 34.2 Diagram 35 - RBAC Authorization Matrix and Access Control Flow

Required role set:

- `Super Admin`
- `Vendor`
- `Buyer`
- `Support`
- `Delivery`
- `Affiliate`
- `Finance Admin`
- `Content Mod`

Required flow:

1. User authenticates and receives role-bearing token context.
2. Endpoint request enters guard pipeline.
3. `@Roles()` check evaluates required permission set.
4. Allowed requests proceed to handler, denied requests return authorization failure.

Required examples in diagram:

- Vendor product management allowed.
- Finance admin escrow/disbursement actions allowed.
- Content moderation actions restricted to content moderator/super admin paths.

### 34.3 Diagram 36 - JWT, Refresh Token, and MFA Lifecycle

Required token lifecycle:

- Access token lifetime: 15 minutes.
- Refresh token rotation on refresh flow.
- Optional TOTP MFA for vendor/admin-sensitive sessions.

Required sequence:

1. Login request -> credential verification.
2. Optional MFA challenge branch.
3. Access + refresh issuance.
4. Access expiry branch -> refresh endpoint call.
5. Refresh success -> rotated token pair.

Required failure branches:

- Invalid/expired refresh token -> re-authentication required.
- MFA verification failure -> deny session establishment.

### 34.4 Diagram 37 - Request Security Pipeline (Defense in Depth)

Required ordered gates:

1. HTTPS + edge WAF/bot protections.
2. CORS origin checks.
3. Rate limiting (`auth`, `checkout`, `AI tier-based`).
4. DTO input validation and sanitization.
5. Parameterized DB access path.
6. RBAC guard and domain authorization checks.

Required outputs:

- Pass path to handler execution.
- Reject paths with explicit response classes (`401`, `403`, `429`, `400`).

### 34.5 Diagram 38 - PostgreSQL RLS Isolation and Cross-Vendor Privacy

Required policy behavior:

- Vendors see only own rows for vendor-bound entities.
- Buyer order visibility limited to own orders.
- Cross-vendor analytics exposure remains aggregate-only.
- Category velocity privacy floor enforces minimum 3-vendor threshold.

Required sequence:

1. Auth context attached to DB session.
2. RLS policy evaluation for each query.
3. Filtered result set returned or denied.

Required branch:

- Attempted cross-tenant data access -> blocked result path.

### 34.6 Diagram 39 - Payment Webhook Verification and Idempotent Processing

Required verification chain:

1. Receive webhook payload.
2. Verify signature/HMAC.
3. Verify transaction status server-side with provider.
4. Apply idempotency check against payment reference.
5. Commit payment state transition and emit event.

Required failure branches:

- Signature mismatch -> reject + security log.
- Provider verification failure -> no payment confirmation.
- Duplicate callback -> idempotent no-op success response.

### 34.7 Diagram 40 - Escrow Authorization and Release Controls

Required release paths:

- Auto-release path: delivery confirmed + 48h cooling elapsed.
- Manual release path: finance admin authorized action.

Required controls:

- Dual-approval gate for sensitive manual release scenarios.
- Immutable audit log for each release decision.
- Dispute freeze path preventing release until resolution.

Required failure/escalation branch:

- Authorization failure or policy breach -> release blocked and escalated.

### 34.8 Diagram 41 - Order Lifecycle State Machine

Required canonical states:

- `Pending`
- `Confirmed`
- `Processing`
- `Picked Up`
- `In Transit`
- `Delivered`
- `Completed`

Required alternative branches:

- Dispute branch from post-delivery/protection scenarios.
- Cancellation/failure branch where saga compensation applies.

### 34.9 Diagram 42 - Order Creation to Confirmation Sequence

Required participants:

- Buyer client
- API/order command handler
- inventory reserve path
- payment gateway
- escrow hold path
- event/notification fanout

Required steps:

1. Place order command received.
2. Inventory validation and reservation.
3. Payment initiation and callback verification.
4. Escrow hold for prepaid path.
5. Order creation and event emission.
6. Buyer/vendor notification fanout.

Required failure branches:

- Inventory failure -> reject command.
- Payment verification failure -> compensation/rollback path.

### 34.10 Diagram 43 - Delivery and COD Intelligence Decision Flow

Required decision elements:

- COD vs prepaid split.
- COD risk evaluation using anomaly/COD history signals.
- Delivery acceptance vs dispute handling.

Required outputs:

- Delivery success -> progress to delivered state and escrow timing path.
- High COD risk -> restricted/advance-payment-required path.
- Dispute -> escrow freeze and support investigation path.

### 34.11 Diagram 44 - Vendor Fulfillment Workflow and Operational Updates

Required steps:

1. Vendor receives order alert.
2. Accept/reject decision.
3. Pick-pack-process stage.
4. 3PL assignment and pickup.
5. Real-time status updates and inventory mutation.

Required integrations:

- WebSocket/in-app status update path.
- AI signal update hooks (velocity/ROP/opportunity).

### 34.12 Diagram 45 - Order History and Analytics Query Flow

Required query paths:

- Buyer order history retrieval.
- Vendor sales analytics retrieval.
- Admin platform analytics retrieval.

Required CQRS read behavior:

- Queries served from read-optimized stores/caches.
- No write-side mutations in history/analytics flow.

Required failure/degradation branch:

- Cache/read-source miss -> fallback to replica/read model with traceable latency path.

### 34.13 Diagram Generation Compliance Checklist (for IDs 35-45)

- Include explicit authz/authn gates on security diagrams.
- Include explicit status transitions for order lifecycle diagrams.
- Include webhook verification + idempotency branches where payments are involved.
- Include audit/logging branches on security-sensitive actions.
- Include at least one rejection/failure branch per process diagram.

---

## 35. Diagram Clarification Spec (Batch E: IDs 46-56)

This section is the normative diagram specification for Mermaid Diagram IDs 46-56. It extends Sections 8.1, 8.4, 9.1, 9.2, 9.5, 11, 13, 15, and 16 for frontend and real-time/messaging visualization precision.

### 35.1 Scope and Conventions

- **Scope:** Frontend architecture diagrams (46-51) and real-time/messaging diagrams (52-56).
- **Authority:** This section is authoritative for Batch E visualization details.
- **Frontend notation requirements:**
  - Show boundaries for buyer, vendor, and admin experiences.
  - Show locale and routing behavior for EN/BN explicitly.
- **Realtime notation requirements:**
  - Show event transport (`WebSocket`, queue-driven messaging, provider APIs).
  - Include fallback/degradation branches for delivery failure or transient outages.

### 35.2 Diagram 46 - Next.js Routing and Localization Architecture

Required components:

- Next.js App Router
- Locale route groups (`/en/...`, `/bn/...`)
- next-intl locale detection and preference persistence
- Role-scoped route segments (buyer/vendor/admin experiences)

Required flow:

1. Request enters route resolution.
2. Locale detection and user preference merge.
3. Route dispatch to localized page tree.

Required fallback branch:

- Unsupported/missing locale -> default locale route with redirect.

### 35.3 Diagram 47 - Buyer Frontend Experience Composition

Required surfaces:

- Search and discovery
- Reel/live discovery cards
- product detail/cart/checkout path
- order tracking and chat entry points

Required data interactions:

- REST query/data fetch path.
- Real-time status update subscription path.

Required failure branch:

- API fetch failure path with recoverable UI state.

### 35.4 Diagram 48 - Vendor Dashboard Frontend Architecture

Required surfaces:

- KPI/forecast widgets
- Opportunity panel
- Product/stock management panels
- Sahayak interaction panel
- Live/reels/POS entry points

Required interactions:

- Forecast/opportunity query endpoints.
- Action endpoints for coupons/pricing/inventory operations.

Required safety branch:

- Action confirmation path before state-changing operations.

### 35.5 Diagram 49 - Admin Console Frontend Architecture

Required surfaces:

- Compliance and KYC review
- Anomaly triage dashboard
- Escrow/finance operations view
- Content moderation queue
- Platform analytics view

Required guardrails:

- Role-restricted action controls for finance/compliance actions.

Required failure branch:

- Unauthorized action attempt path and UI denial state.

### 35.6 Diagram 50 - Client State and Data Sync Architecture

Required state layers:

- Local client state (cart/session/UI state)
- Server state cache/query layer
- Real-time event updates merged into view state

Required flows:

1. Initial data fetch and cache hydration.
2. Client mutation request path.
3. Revalidation/invalidation flow.
4. Realtime event reconciliation with cached state.

Required degradation branch:

- Offline/transient network mode with queued or deferred sync for supported flows.

### 35.7 Diagram 51 - PWA, Mobile, and POS Experience Topology

Required channels:

- Web PWA experience
- Mobile app experience
- POS mode flow (barcode/QR-assisted sales updates)

Required consistency paths:

- Shared backend APIs across channels.
- Inventory/order state synchronization across online and POS events.

Required failure branch:

- Connectivity interruption path with subsequent resync/reconciliation behavior.

### 35.8 Diagram 52 - WebSocket Event Architecture

Required event domains:

- Order status events
- Chat messages
- Alert/notification push events
- Live viewer/event updates

Required flow:

1. Socket authentication and room assignment.
2. Event publish/subscribe routing by role/context.
3. Client acknowledgment/update cycle.

Required failure branch:

- Reconnect/backoff path and missed-event recovery behavior.

### 35.9 Diagram 53 - WhatsApp Dispatch Pipeline (EN/BN Templates)

Required pipeline:

1. Domain event triggers notification intent.
2. Template selection by locale preference.
3. Queue dispatch worker sends provider request.
4. Delivery status callback updates notification state.

Required fallback chain:

- WhatsApp failure -> web push/in-app fallback path.

Required controls:

- Rate-limit and anti-spam policy branch.

### 35.10 Diagram 54 - Live Commerce Real-Time Interaction Flow

Required sequence:

1. Vendor starts live session.
2. Buyer joins stream.
3. Real-time chat/reactions/overlay commerce interactions.
4. Shoppable actions route into cart/order pathways.

Required components:

- Live streaming coordination layer.
- Session metadata and viewer count updates.

Required failure branch:

- Stream disruption/reconnect path with session continuity handling.

### 35.11 Diagram 55 - Short-Form Video Feed Ranking and Commerce Actions

Required ranking factors (explicitly labeled):

- Buyer interest signals
- Trend/engagement signals
- Category affinity
- Recency

Required actions:

- Feed impression/view update path
- Product tag click-to-cart path
- Vendor/profile navigation path

Required degradation branch:

- Ranking-source fallback for sparse-user history scenarios.

### 35.12 Diagram 56 - Unified Notification Center Orchestration

Required channels:

- In-app notifications
- WhatsApp notifications
- Push/web notifications

Required flow:

1. Event classification by type/severity.
2. Channel preference evaluation.
3. Channel fanout and delivery tracking.
4. Notification center state update (`delivered`, `read`).

Required failure branch:

- Primary channel failure reroutes to allowed fallback channels.

### 35.13 Diagram Generation Compliance Checklist (for IDs 46-56)

- Show role/experience boundaries clearly for buyer/vendor/admin.
- Show locale routing behavior for EN/BN where frontend navigation is involved.
- Show event transport and fallback paths for real-time/messaging diagrams.
- Include at least one failure/degradation branch per process-heavy diagram.
- Keep all endpoint/feature names aligned to V4 section terminology.

---

## 36. Diagram Clarification Spec (Batch F: IDs 57-67)

This section is the normative diagram specification for Mermaid Diagram IDs 57-67. It extends Sections 9, 10, 11, 12, 14, 15, 16, 17, 20, and 29 for vendor operations and social/live commerce visualization precision.

### 36.1 Scope and Conventions

- **Scope:** Vendor flow diagrams (57-63) and social/live commerce bridge diagrams (64-67).
- **Authority:** This section is authoritative for Batch F visualization details.
- **Flow requirements:**
  - Include role gates (`Vendor`, `Admin`, `Finance`, `Support`) where actions change compliance or money state.
  - Include async paths where queues/webhooks/background jobs are required.
  - Include at least one failure branch per process-heavy diagram.

### 36.2 Diagram 57 - Vendor Onboarding and KYC Verification Workflow

Required steps:

1. Vendor registration (`/api/auth/register`) with locale and role.
2. KYC submission (`/api/verification/submit`) with NID/trade license/TIN artifacts.
3. Compliance review queue evaluation.
4. Approval/rejection decision and reason capture.
5. Vendor activation and dashboard access on approval.

Required branches:

- Missing/invalid documents -> revision request path.
- Rejected vendor -> appeal/resubmission path.

### 36.3 Diagram 58 - Subscription Billing and Tier Change Flow

Required tiers:

- Free, Starter, Growth, Pro, Enterprise.

Required flow:

1. Vendor selects tier or upgrade/downgrade action.
2. Billing engine computes cycle amount and proration policy.
3. Payment attempt through configured payment rails.
4. `subscription_billing` update and entitlement update.

Required branches:

- Payment failure -> grace period + retry + downgrade guard path.
- Feature entitlement mismatch -> reconciliation path.

### 36.4 Diagram 59 - Vendor Catalog Publish and Moderation Pipeline

Required flow:

1. Vendor submits product listing (text/images/video/brand claims).
2. Validation and policy scan (content, counterfeit risk, required fields).
3. Moderation queue assignment for flagged items.
4. Approve -> publish to catalog and search index.

Required branches:

- Rejected listing -> vendor correction loop.
- Escalated counterfeit suspicion -> compliance takedown path.

### 36.5 Diagram 60 - Vendor Campaign Orchestration (Coupon + Flash Sale)

Required components:

- Coupon Optimization Advisor (`/api/ai/coupon-optimize`).
- Flash sale slot and stock cap controls.

Required flow:

1. Vendor selects campaign objective (clear stock, boost conversion, festival push).
2. AI recommendation generated for discount and expected movement.
3. Vendor confirms campaign and publish window.
4. Campaign goes live with inventory guardrails.

Required branches:

- Policy-violating discount -> clamp/reject path.
- Insufficient stock for flash slot -> auto-adjust/reject path.

### 36.6 Diagram 61 - Vendor Inventory Replenishment and Supplier Lead-Time Learning

Required logic:

- Smart reorder point from Module 02.
- Supplier lead-time learning from actual deliveries.

Required flow:

1. Stock and forecast context evaluated.
2. ROP breach triggers reorder recommendation.
3. Vendor places supplier order.
4. Actual receipt date captured to refine lead-time model.

Required branches:

- Missing supplier history -> default lead-time path.
- Delayed supplier delivery -> urgency escalation path.

### 36.7 Diagram 62 - Vendor Finance Reconciliation and Disbursement Control Flow

Required components:

- `commission_records`, `escrow_transactions`, `vendor_disbursements`, `wallet_transactions`.

Required flow:

1. Escrow release events aggregated for vendor period.
2. Fees/commission/net payable computed.
3. Disbursement execution status checked.
4. Reconciliation dashboard status updated.

Required branches:

- Mismatch between ledger and payout -> finance hold/escalation path.
- Failed payout -> retry/manual review path.

### 36.8 Diagram 63 - PRISM Academy Learning and Certification Progress Flow

Required flow:

1. Vendor enrolls in module.
2. Progress events update `academy_progress`.
3. Completion checks and certification decision.
4. Benefits unlocked (badge/feature prompt/education milestones).

Required branches:

- Incomplete prerequisites -> blocked certification path.
- Abandoned progress -> reminder and re-engagement path.

### 36.9 Diagram 64 - Facebook Shops Sync and Attribution Flow

Required flow:

1. Vendor initiates `POST /api/social/sync/facebook`.
2. Catalog mapping and sync job execution.
3. Status callbacks and mapping persistence.
4. Attribution signal to PRISM analytics.

Required branches:

- API auth/token failure -> reconnect flow.
- Partial sync failure -> delta retry flow.

### 36.10 Diagram 65 - TikTok Shop Sync and Order Reconciliation Flow

Required flow:

1. Vendor links TikTok integration.
2. Catalog push and product mapping.
3. External order ingress and PRISM order reconciliation.
4. Inventory and payout attribution updates.

Required branches:

- Duplicate external order -> idempotent handling path.
- Mapping conflict -> manual review queue.

### 36.11 Diagram 66 - YouTube Shopping and Live Product Overlay Integration Flow

Required flow:

1. Live or video inventory mapped to product IDs.
2. Product overlays published to stream/video context.
3. Viewer click-through routed to PRISM product/cart.
4. Attribution recorded for source channel.

Required branches:

- Missing product mapping -> overlay suppression path.
- Link integrity failure -> fallback destination path.

### 36.12 Diagram 67 - Influencer Affiliate and Referral Attribution Lifecycle

Required entities and outputs:

- `affiliate_tracking`, `referral_codes`, commission payout signals.

Required flow:

1. Affiliate/referral link issuance.
2. Click and conversion tracking.
3. Attribution validation window.
4. Reward/commission posting and reporting.

Required branches:

- Invalid or expired code -> no-attribution path.
- Fraud-like attribution anomaly -> hold and review path.

### 36.13 Diagram Generation Compliance Checklist (for IDs 57-67)

- Include role gates for KYC, moderation, and finance-sensitive actions.
- Include queue/background processing for sync and moderation workflows.
- Include explicit attribution persistence paths for social/affiliate flows.
- Include at least one rejection/failure branch for each process-heavy diagram.

---

## 37. Diagram Clarification Spec (Batch G: IDs 68-75)

This section is the normative diagram specification for Mermaid Diagram IDs 68-75. It extends Sections 8.4, 13, 15, 17, 18, 20, 22, and 24 for DevOps/observability and API design visualization precision.

### 37.1 Scope and Conventions

- **Scope:** DevOps/observability diagrams (68-71) and API design/governance diagrams (72-75).
- **Authority:** This section is authoritative for Batch G visualization details.
- **Notation requirements:**
  - Show control-plane tools and runtime-plane services distinctly.
  - Include reliability controls (retry, alerting, rollback, idempotency) where relevant.

### 37.2 Diagram 68 - CI/CD Build-Test-Deploy Pipeline

Required stages:

1. Source change trigger (push/PR).
2. Lint, typecheck, unit/integration tests.
3. Build artifacts and container images.
4. Deploy to target environment.
5. Post-deploy smoke/health checks.

Required branches:

- Failed quality gate -> block deployment.
- Failed post-deploy check -> rollback path.

### 37.3 Diagram 69 - Observability Signal Topology (Metrics, Logs, Traces, Errors)

Required components:

- Prometheus, Grafana, Loki, Tempo/OpenTelemetry, Sentry.

Required flow:

1. Services emit metrics/logs/traces/errors.
2. Signals aggregated and routed to observability stack.
3. Dashboards and alert rules consume signal streams.

Required branches:

- Telemetry sink outage -> buffered/degraded observability path.

### 37.4 Diagram 70 - Incident Detection, Alerting, and On-Call Response Workflow

Required flow:

1. Alert threshold breach from SLO/SLA or error spike.
2. Notification to on-call path.
3. Triage and incident severity classification.
4. Mitigation and recovery steps.
5. Post-incident review and action items.

Required branches:

- False positive alert -> close with rule tuning.
- Unresolved in time window -> escalation path.

### 37.5 Diagram 71 - Backup, Restore, and Disaster Recovery Flow

Required coverage:

- PostgreSQL backups, event store retention, recovery validation.

Required flow:

1. Scheduled encrypted backup creation.
2. Integrity verification.
3. Restore rehearsal in isolated environment.
4. RTO/RPO validation.

Required branches:

- Backup corruption -> backup-chain fallback.
- Restore failure -> incident escalation.

### 37.6 Diagram 72 - API Gateway Request Lifecycle and Version Governance

Required controls:

- Versioned routes (`/api/v1/...`), auth guard, throttling, validation.

Required flow:

1. Incoming request to gateway.
2. Route/version resolution.
3. Security and validation middleware.
4. Domain handler execution and response shaping.

Required branches:

- Unsupported version -> deprecation/error path.
- Rate limit or auth failure -> controlled reject path.

### 37.7 Diagram 73 - Vendor Write API Contract (Idempotency + Consistency)

Required endpoints context:

- Vendor product/order/campaign mutation paths.

Required flow:

1. Authenticated vendor write request accepted.
2. Idempotency key checked.
3. Command and persistence execution.
4. Event/audit append and response.

Required branches:

- Duplicate idempotency key -> replay-safe return.
- Domain validation failure -> no mutation path.

### 37.8 Diagram 74 - Webhook Ingestion Reliability Pattern

Required sources:

- Payment gateways and partner callbacks.

Required flow:

1. Webhook receive.
2. Signature verification + source validation.
3. Idempotency check.
4. Process + event emit.
5. Retry/dead-letter handling on transient failure.

Required branches:

- Invalid signature -> security reject path.
- Permanent processing error -> manual intervention queue.

### 37.9 Diagram 75 - API Key Lifecycle and Partner Access Control Flow

Required entities:

- `api_keys`, permissions set, rate-limit policy.

Required flow:

1. Vendor/admin requests key issuance.
2. Permission-scoped key generated and hashed.
3. Runtime authorization with key policy checks.
4. Rotation/revocation lifecycle.

Required branches:

- Scope mismatch -> deny request.
- Compromised key signal -> emergency revoke path.

### 37.10 Diagram Generation Compliance Checklist (for IDs 68-75)

- Distinguish CI/CD control-plane from runtime data-plane in diagrams.
- Include reliability controls: rollback, retry, dead-letter, escalation.
- Include explicit versioning/governance paths for API design diagrams.
- Include at least one failure branch for each process-heavy diagram.

---

## 38. Diagram Clarification Spec (Batch H: IDs 76-84)

This section is the normative diagram specification for Mermaid Diagram IDs 76-84. It extends Sections 6, 20, 22, 26, 27, 28, and 29 for business model, growth, and execution-governance visualization precision.

### 38.1 Scope and Conventions

- **Scope:** Business and growth diagrams (76-84).
- **Authority:** This section is authoritative for Batch H visualization details.
- **Modeling requirements:**
  - Show decision gates and measurable thresholds where roadmap/finance decisions are made.
  - Keep flows anchored to documented milestones and gates (Month 4, 6, 9, 12, 15, 18).

### 38.2 Diagram 76 - Five-Tier Subscription Packaging and Entitlement Flow

Required tiers and controls:

- Free, Starter, Growth, Pro, Enterprise with entitlement boundaries.

Required flow:

1. Vendor selects/changes tier.
2. Entitlement profile loaded.
3. Feature access checks executed at runtime.

Required branches:

- Requested feature outside tier -> upgrade prompt path.

### 38.3 Diagram 77 - Revenue Waterfall and Reserve Allocation Flow

Required order of allocation:

1. Gross platform inflows.
2. Operating cost coverage.
3. Reserve allocation (20% as documented).
4. Remaining distributable pool.

Required branches:

- Revenue shortfall against operating costs -> austerity/escalation path.

### 38.4 Diagram 78 - Unit Economics and Break-Even Trajectory Model

Required metrics:

- CAC, LTV, gross margin band, monthly burn, monthly revenue.

Required flow:

1. Monthly cohort/revenue/cost inputs.
2. Net position computation.
3. Break-even detection around Month 16-18 trajectory.

Required branches:

- If break-even trend drifts materially, trigger mitigation strategy.

### 38.5 Diagram 79 - Vendor Acquisition Funnel and Conversion Flywheel

Required stages:

- Awareness -> Lead -> Demo -> Onboarded -> Active vendor -> Referral.

Required channels:

- Field sales, Facebook groups, referrals, academy content.

Required branches:

- Funnel drop-off at any stage -> targeted intervention loop.

### 38.6 Diagram 80 - Buyer Acquisition and Retention Loop

Required loop components:

- Reels/live discovery, flash sales, referrals, repeat purchase, loyalty effects.

Required flow:

1. Discovery and first purchase.
2. Post-purchase engagement and notification loops.
3. Repeat behavior and referral activation.

Required branches:

- Churn-risk signals -> win-back campaign path.

### 38.7 Diagram 81 - Geographic Expansion Rollout Strategy

Required sequence:

- Dhaka -> Chattogram -> Sylhet -> broader nationwide rollout.

Required gates:

- Capacity, logistics readiness, support readiness, vendor density thresholds.

Required branches:

- Gate not met -> hold and remediation path.

### 38.8 Diagram 82 - Self-Funding Gates and External Funding Decision Tree

Required decision gates:

- Gate 1 (Month 4), Gate 2 (Month 6), Gate 3 (Month 9), Gate 4 (Month 12), Gate 5 (Month 15).

Required flow:

1. Evaluate revenue and traction at each gate.
2. Continue self-funding vs seek external path decision.
3. Resource allocation implications.

Required branches:

- Underperforming gate -> pivot/cost-control path.

### 38.9 Diagram 83 - Risk Register Monitoring and Mitigation Escalation Workflow

Required structure:

- Risk intake, likelihood/impact scoring, owner assignment, mitigation execution, residual risk review.

Required branches:

- High-impact unresolved risk -> executive escalation path.
- Closed risk -> archive/knowledge capture path.

### 38.10 Diagram 84 - 15-Month Roadmap Dependency and Milestone Timeline

Required phases:

- Foundation/Compliance, Revenue/Trust, AI/GenAI, Communication/Commerce, Logistics/Mobile, Polish/Launch/Scale.

Required flow:

1. Phase dependencies mapped.
2. Milestone readiness checks.
3. Launch readiness gate at Month 15.

Required branches:

- Dependency slip -> re-plan and scope adjustment path.

### 38.11 Diagram Generation Compliance Checklist (for IDs 76-84)

- Include numerical gates/thresholds where documented.
- Include explicit decision points for funding and expansion.
- Keep business diagrams tied to V4 roadmap and projection terminology.
- Include at least one risk/deviation branch for each process-heavy diagram.
