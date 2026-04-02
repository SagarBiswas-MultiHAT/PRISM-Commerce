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
┌─────────────────────────────────────────────────────────────────────┐
│                THE BANGLADESH E-COMMERCE GAP (2026)                  │
│                                                                      │
│  ┌─── Established Players ──┐   ┌─── The Gap ──────────────────┐   │
│  │ Daraz (Alibaba)          │   │                               │   │
│  │ • Has DarazLive + DEX    │   │  NO PLATFORM IN BANGLADESH    │   │
│  │ • Has DarazMall trust    │   │  COMBINES:                    │   │
│  │ • No AI for vendors      │   │                               │   │
│  │ • High commission 8-15%  │   │  ✗ Agentic AI assistant       │   │
│  │ • English-centric        │   │  ✗ Bangla-first + voice       │   │
│  │                          │   │  ✗ Predictive inventory       │   │
│  │ Shopify                  │   │  ✗ Festival intelligence      │   │
│  │ • Sidekick (English)     │   │  ✗ Escrow + buyer protection  │   │
│  │ • No BD payments         │   │  ✗ Short-form video commerce  │   │
│  │ • $29+/mo (too expensive)│   │  ✗ POS for physical stores    │   │
│  │                          │   │  ✗ Bangla QR compliance       │   │
│  │ sManager                 │   │  ✗ Cross-vendor intelligence  │   │
│  │ • Has POS                │   │  ✗ Affordable SaaS pricing    │   │
│  │ • No AI, no marketplace  │   │                               │   │
│  │                          │   │  PRISM V4 FILLS THIS GAP      │   │
│  └──────────────────────────┘   └───────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────┘
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
│                    PRISM V4 REVENUE STREAMS                           │
│                                                                       │
│  ┌─── Recurring ──────────────┐   ┌─── Transactional ─────────────┐  │
│  │ SaaS Subscriptions         │   │ Commission per sale (2-5%)    │  │
│  │ (৳0 – ৳5,000+/mo)         │   │ Payment processing (1-1.5%)  │  │
│  │ 5 tiers (Free→Enterprise) │   │ Logistics markup (৳5-20)     │  │
│  └────────────────────────────┘   └────────────────────────────────┘  │
│                                                                       │
│  ┌─── Advertising ────────────┐   ┌─── Financial ──────────────────┐ │
│  │ Promoted listings          │   │ Wallet float income            │ │
│  │ Live commerce slots        │   │ BNPL partner revenue share     │ │
│  │ Homepage featured spots    │   │ Escrow float (short-term)      │ │
│  │ Flash sale slots           │   │                                │ │
│  │ Short-form video boost     │   │                                │ │
│  └────────────────────────────┘   └────────────────────────────────┘ │
│                                                                       │
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
│                      PRISM COMMERCE SYSTEM (V4)                               │
├──────────────────────────────┬───────────────────────────────────────────────┤
│   Next.js 15 Frontend        │        NestJS Backend API                     │
│   (App Router + PPR + PWA)   │   (Modular Monolith + CQRS)                  │
│   shadcn/ui + Tailwind CSS   │                                               │
│   next-intl (EN + BN)        │  ┌────────────────────────────────────────┐   │
│   Recharts + Nivo            │  │  ONNX GBR ML Model                     │   │
│   Zustand (cart + offline)   │  │  (onnxruntime-node v1.17+)             │   │
│   React Native (Phase 2)     │  │  Inference < 80ms per product          │   │
│   Expo (mobile app)          │  │  Weather + Festival + Category inject   │   │
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
│                              │  ┌────────────────────────────────────────┐   │
│                              │  │  Event Bus & Background Jobs            │   │
│                              │  │  • BullMQ: Task queues (email, SMS)     │   │
│                              │  │  • Event Store: orders, payments, inv   │   │
│                              │  │  • CRON: forecast, velocity, weather    │   │
│                              │  │  • Saga: order fulfillment pipeline     │   │
│                              │  └────────────────────────────────────────┘   │
│                              │                                               │
│                              │  ┌────────────────────────────────────────┐   │
│                              │  │  Trust & Compliance Engine (NEW V4)     │   │
│                              │  │  • Escrow manager                       │   │
│                              │  │  • PRISM Protect dispute resolver       │   │
│                              │  │  • KYC / verification pipeline          │   │
│                              │  │  • VAT computation + reporting          │   │
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
│                                                                       │
│  Client → API Gateway → NestJS Command Handler                       │
│     │                                                                 │
│     ├─ PlaceOrderCommand → OrderSaga                                 │
│     │   ├─ Step 1: ReserveInventory → InventoryReserved event        │
│     │   ├─ Step 2: ProcessPayment → PaymentProcessed event           │
│     │   ├─ Step 3: HoldEscrow → EscrowHeld event                    │
│     │   ├─ Step 4: ConfirmOrder → OrderConfirmed event               │
│     │   └─ Step 5: AssignLogistics → LogisticsAssigned event         │
│     │                                                                 │
│     ├─ On ANY step failure → Compensating actions:                   │
│     │   PaymentFailed → ReleaseInventory + NotifyBuyer               │
│     │   LogisticsFailed → RefundPayment + ReleaseInventory           │
│     │                                                                 │
│     └─ All events → PostgreSQL Event Store (append-only)             │
│                     + Redis publish for real-time subscribers         │
└───────────────────────────────────────────────────────────────────────┘

┌─── READ PATH (Queries) ──────────────────────────────────────────────┐
│                                                                       │
│  Client → API Gateway → NestJS Query Handler                         │
│     │                                                                 │
│     ├─ ProductSearch → Meilisearch (denormalized product index)      │
│     ├─ DashboardData → Redis cached materialized views               │
│     ├─ OrderHistory → PostgreSQL read replica                        │
│     └─ AnalyticsQuery → PostgreSQL read replica + materialized views │
│                                                                       │
│  Read models are updated asynchronously by event projectors:         │
│     Event Store → Projector → Denormalized Tables / Meilisearch      │
└───────────────────────────────────────────────────────────────────────┘
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
┌──────────────────────────────────────────────────────────────────────────┐
│  PRISM Commerce  [🔍 Search] [🔔 3] [Sahayak 🤖] [EN|বাংলা] [Profile ▼]│
├─────────┬────────────────────────────────────────────────────────────────┤
│ Sidebar │  ┌─ Top Stats ──────────────────────────────────────────────┐  │
│ 🏠 Home  │  │ Revenue ৳42.5K  │ Orders 12  │ Low-Stock 3🔴 │ VPS 87⭐ │  │
│ 📦 Prods │  └──────────────────────────────────────────────────────────┘  │
│ 📋 Orders│  ┌─ Opportunity Engine (NEW V4) ─────────────────────────────┐ │
│ 📊 AI    │  │ 🔴 Product B: Stockout in 5 days → [Restock Now]          │ │
│ 🎥 Live  │  │ 🟡 Product D: 60-day excess → [Create Flash Sale]        │ │
│ 📹 Reels │  │ 🟢 Product A: Demand ↑23% → [Hold Price]                 │ │
│ 💰 Sales │  └───────────────────────────────────────────────────────────┘ │
│ 🏪 POS   │                                                               │
│ 🎓 Learn │  ┌─ Product List ──────┬─ Forecast Chart ─────────────────┐  │
│ ⚙️ Setup │  │ [Product A] ███ 85% │ Recharts Area Chart:             │  │
│         │  │  Forecast: ↑         │ 30d history + 30d GBR forecast   │  │
│         │  │ [Product B] ██ 15%🚨 │ (dashed + confidence band)       │  │
│         │  │  🗓 Eid in 14 days    │ Festival Markers: 🔴 Eid (x-axis)│  │
│         │  └──────────────────────┴──────────────────────────────────┘  │
│         │  ┌─ Sahayak Chat (Agentic) ────────────────────────────────┐  │
│         │  │ 🤖 "আপনার ৩টি স্লো-মুভিং প্রোডাক্টে ১৫% ডিসকাউন্ট         │  │
│         │  │    তৈরি করেছি। দেখুন... " [View Coupons]                 │  │
│         │  └──────────────────────────────────────────────────────────┘  │
└─────────┴────────────────────────────────────────────────────────────────┘
```

### Screen 2 — Buyer Homepage (Mobile 375px)

```
┌──────────────────────────────┐
│  PRISM  [🔍] [🔔] [🛒 2]     │
├──────────────────────────────┤
│  🤖 "কি খুঁজছেন?" [🎤 Voice] │ ← Sahayak search bar
├──────────────────────────────┤
│  📹 [Reel 1] [Reel 2] [R3]  │ ← Swipeable reels
│     Trending Reels ▸         │
├──────────────────────────────┤
│  🔴 LIVE  [Vendor A: Sarees] │ ← Active live stream
│  👤 2.3K watching [Join]     │
├──────────────────────────────┤
│  Flash Sale ⚡ 2h 34m left   │
│  [Product] ৳800 ░░৳500 -37% │
├──────────────────────────────┤
│  Trending Now 🔥              │
│  [Prod 1] [Prod 2] [Prod 3] │
├──────────────────────────────┤
│  🏠  🔍  📹  🛒  👤         │ ← Bottom nav
└──────────────────────────────┘
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
