# 🚀 PRISM Commerce — V3.0 (Startup Edition)
## Predictive Retail Intelligence & Stock Management

> **Type:** Startup Business Plan & Technical Architecture  
> **Version:** 3.0 (Startup Transformation — Production-Grade, Revenue-Ready, AI-Native)  
> **Date:** April 2026  
> **Mission:** Build Bangladesh's first Bangla-native, AI-powered, live commerce-enabled multi-vendor marketplace

---

```
Stack:    Next.js 15 · NestJS · PostgreSQL 16 · Redis 7 · ONNX GBR · Docker
AI:       11 REST Engines + 1 ONNX GBR Model + GenAI Assistant (LLM) + RAG Search
New V3:   Live Commerce · Social Commerce · GenAI Sahayak · PRISM Wallet · BNPL
          3PL Logistics · Multi-Tenant SaaS · In-App Chat · Influencer System
          Hybrid Monetization (SaaS + Commission + Ads) · React Native App
Local:    Bengali (বাংলা) · Festival Intelligence · Weather-Aware · bKash/Nagad/SSLCommerz
```

---

## 📋 Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Market Analysis & Opportunity](#2-market-analysis--opportunity)
3. [Competitive Landscape — Deep Analysis](#3-competitive-landscape--deep-analysis)
4. [Problem Statement (Expanded)](#4-problem-statement-expanded)
5. [Unique Value Proposition](#5-unique-value-proposition)
6. [Business Model & Monetization](#6-business-model--monetization)
7. [User Architecture — 7 Roles](#7-user-architecture--7-roles)
8. [System Architecture — V3](#8-system-architecture--v3)
9. [Core Feature Set](#9-core-feature-set)
10. [AI Intelligence Layer — 11 Modules + GenAI](#10-ai-intelligence-layer)
11. [New Strategic Modules (A–H)](#11-new-strategic-modules-a-h)
12. [Bangladesh-Native Integrations](#12-bangladesh-native-integrations)
13. [Technology Stack — V3](#13-technology-stack--v3)
14. [Database Schema](#14-database-schema)
15. [Key API Endpoints](#15-key-api-endpoints)
16. [UI Wireframes & Screens](#16-ui-wireframes--screens)
17. [Security Architecture](#17-security-architecture)
18. [Performance & Observability](#18-performance--observability)
19. [Development Roadmap — 12-Month Startup Plan](#19-development-roadmap--12-month-startup-plan)
20. [Team & Hiring Plan](#20-team--hiring-plan)
21. [Risk Register & Mitigation](#21-risk-register--mitigation)
22. [Novelty & Emergence Argument](#22-novelty--emergence-argument)
23. [Testing Strategy](#23-testing-strategy)
24. [Accessibility & Inclusivity](#24-accessibility--inclusivity)
25. [Financial Projections](#25-financial-projections)
26. [Investor Pitch Summary](#26-investor-pitch-summary)
27. [Glossary](#27-glossary)

---

## 1. Executive Summary

PRISM Commerce is a **Predictive Retail Intelligence and Stock Management** platform that unifies e-commerce operations with an AI-driven inventory intelligence layer, a generative AI shopping assistant, live commerce capabilities, and social commerce integration — purpose-built for the Bangladeshi market as a competitive startup platform.

### The Vision

> Build the platform that makes Daraz, Shopify, and Netstock unnecessary for Bangladeshi SMEs — by combining the marketplace reach of Daraz, the SaaS power of Shopify, the forecasting intelligence of Netstock, and the local relevance that none of them have.

### Who is it for?

**Primary:** Small-to-mid-scale businesses (SMEs) in Bangladesh — the 8 million+ micro-merchants who currently rely on intuition, spreadsheets, Facebook pages, or nothing at all to manage their inventory and sales.

**Secondary:** Buyers across Bangladesh who want a trusted, Bangla-first shopping experience with AI-powered discovery, live commerce, and modern payment options.

> **Real-world analogy:** Imagine a shop owner in Chawkbazar who sells fabric. Every year before Eid, she guesses how much to buy. With PRISM, she gets a WhatsApp alert in Bangla saying "আপু, আগামী ১৪ দিনে তোমার লাল শাড়ি ৫০ পিস শেষ হবে, এখনই অর্ডার দাও!" — powered by AI that learns from her sales, the entire fabric market on PRISM, the weather forecast, and the festival calendar. She can also go LIVE on the platform to showcase her new collection, chat with buyers directly, and get paid instantly via bKash.

### What makes this a startup, not a project?

| Dimension | V2 (Course Project) | V3 (Startup) |
|---|---|---|
| Revenue Model | None (BDT 0/month) | Hybrid SaaS + Commission + Ads + Wallet |
| Scale Target | Demo (~100 products) | 10K+ vendors, 100K+ products, 1M+ users |
| AI Depth | GBR forecasting (11 modules) | GBR + GenAI Assistant + RAG Search + LLM |
| Commerce | Static product pages | Live Commerce + Social Commerce + Video Shopping |
| Communication | WhatsApp only (one-way) | In-app Chat + WhatsApp + Email + SMS + Chatbot |
| Delivery | Basic partner role | 3PL integration (Pathao, Paperfly, RedX, Steadfast) |
| Payments | Sandbox APIs | Production bKash + Nagad + SSLCommerz + Wallet + BNPL |
| Infrastructure | Free-tier services | Docker + VPS + Managed databases |
| Mobile | PWA only | PWA + React Native app |
| Timeline | 6 weeks | 12-month phased launch |

### At a Glance

| Dimension | Detail |
|---|---|
| Category | AI-Powered Multi-Vendor E-Commerce Marketplace + SaaS |
| Stack | Next.js 15, NestJS, PostgreSQL 16, Redis 7, ONNX, Docker |
| Target Market | Bangladesh (~$7.5B e-commerce market, 80% mobile-first) |
| User Roles | 7: Super Admin, Vendor, Buyer, Support, Delivery, Affiliate, Finance Admin |
| AI Modules | 11 REST engines + 1 ONNX GBR ML + GenAI Assistant (LLM) + RAG Search |
| Monetization | SaaS tiers + transaction commission + promoted listings + wallet + BNPL |
| Language | English + Bengali (বাংলা) — GenAI assistant speaks Bangla |
| Key Integrations | WhatsApp, bKash, Nagad, SSLCommerz, OpenWeatherMap, Facebook Shops, 3PL partners |
| Architecture | Modular monolith → microservices-ready, Docker-containerized |
| Launch Strategy | Dhaka-first → nationwide within 6 months of launch |

---

## 2. Market Analysis & Opportunity

### 2.1 Bangladesh E-Commerce Market (2025–2030)

| Metric | Value | Source |
|---|---|---|
| Market Size (2025) | ~US $7.4–7.5 billion | Research & Markets, Trade.gov |
| Projected Size (2029) | ~US $9.6–15 billion | Multiple analysts |
| CAGR | 6.7%–17.7% | Range across analyst estimates |
| Mobile-Driven Volume | 80%+ | PaymentsCMI |
| bKash Registered Accounts | 67M+ | bKash official |
| Nagad Registered Accounts | 20M+ | Nagad official |
| Internet Users | 130M+ | BTRC |
| Smartphone Penetration | 55%+ (growing) | GSMA |
| Cash-on-Delivery Preference | ~70-90% of orders | Industry surveys |
| WhatsApp Users in BD | 45M+ | Meta |

### 2.2 The Opportunity Gap

```
┌─────────────────────────────────────────────────────────────────┐
│                    THE BANGLADESH E-COMMERCE GAP                │
│                                                                 │
│  ┌─── Big Players ────┐   ┌─── The Gap ──────────────────┐     │
│  │ Daraz (Alibaba)    │   │                               │     │
│  │ • English-centric  │   │  NO PLATFORM IN BANGLADESH    │     │
│  │ • No AI for SMEs   │   │  COMBINES:                    │     │
│  │ • High commission  │   │                               │     │
│  │ • Generic tools    │   │  ✗ Bangla-first AI assistant  │     │
│  │                    │   │  ✗ Live commerce for SMEs     │     │
│  │ Chaldal            │   │  ✗ Predictive inventory       │     │
│  │ • Grocery only     │   │  ✗ Festival intelligence      │     │
│  │ • No multi-vendor  │   │  ✗ Social commerce bridge     │     │
│  │ • Struggling 2025  │   │  ✗ Affordable SaaS pricing    │     │
│  │                    │   │  ✗ Cross-vendor intelligence   │     │
│  │ Shopify            │   │                               │     │
│  │ • Expensive ($$$)  │   │  PRISM V3 FILLS THIS GAP      │     │
│  │ • No BD features   │   │                               │     │
│  │ • No Bangla AI     │   │                               │     │
│  └────────────────────┘   └───────────────────────────────┘     │
└─────────────────────────────────────────────────────────────────┘
```

### 2.3 Target Customer Segments

| Segment | Size | Pain Points | PRISM Value Prop |
|---|---|---|---|
| **Facebook Sellers** | 300K+ active | No inventory management, no analytics, manual everything | Full platform migration with AI, payments, delivery |
| **Small Shop Owners** | 3M+ (estimated) | Guesswork on stock, no digital tools, Bangla-only | Bangla AI assistant + WhatsApp alerts + mobile-first |
| **Daraz Sellers (frustrated)** | 100K+ | High commission (8-15%), poor analytics, no demand prediction | Lower commission (2-5%) + AI forecasting + better tools |
| **Shopify Users (BD)** | 5K+ (estimated) | Expensive ($29+/mo), no bKash/Nagad, no Bangla, no BD features | ৳500/mo with full BD integration + AI |
| **New Entrepreneurs** | Growing rapidly | Don't know where to start | Free tier + guided onboarding + AI assistant in Bangla |

### 2.4 Competitive Moats (Defensibility)

1. **Data Network Effect:** More vendors → better cross-vendor intelligence → better forecasts → attracts more vendors
2. **Bangla AI Moat:** First Bangla-native GenAI commerce assistant — extremely hard for foreign platforms to replicate
3. **Festival Intelligence IP:** Proprietary database of Bangladesh festival-demand correlations refined over time
4. **Vendor Lock-in Through Value:** AI gets smarter with vendor's own data over time — switching costs increase naturally
5. **Local Payment Integration Depth:** bKash + Nagad + SSLCommerz + Wallet + BNPL — full BD payment stack

---

## 3. Competitive Landscape — Deep Analysis

### 3.1 Daraz Bangladesh (Alibaba Group)

**What they do well:**
- Massive scale (millions of products, hundreds of thousands of sellers)
- DarazLive (live streaming commerce)
- Own logistics network (DEX with IoT DigiBox)
- Daraz Wallet + Buy-Now-Pay-Later
- Daraz University (seller training)
- Backed by Alibaba Cloud infrastructure (React, React Native, Java, Python, Tengine)

**Where they fail (PRISM's opportunity):**
- ❌ No AI demand forecasting for individual vendors
- ❌ No festival-aware inventory intelligence
- ❌ No weather-aware demand signals
- ❌ High commissions (8–15%) squeeze small vendors
- ❌ English-centric admin interface
- ❌ Generic seller tools — no predictive analytics
- ❌ No cross-vendor collective intelligence
- ❌ Vendor support is impersonal and slow

**PRISM V3 vs. Daraz:**

| Dimension | Daraz | PRISM V3 |
|---|---|---|
| AI for Vendors | None | GBR forecasting + GenAI assistant + What-If planner |
| Commission | 8–15% | 2–5% (tiered) |
| Language | English-centric | Bangla-first (AI speaks Bangla) |
| Festival Intel | Flash sales only | Predictive calendar with 14-day pre-surge alerts |
| Live Commerce | DarazLive | PRISM Live (+ Bangla AI recommendations during stream) |
| Vendor Analytics | Basic dashboard | Profit reporting, CLV, RFM, AI insights |

### 3.2 Shopify

**What they do well:**
- World-class SaaS platform (multi-tenant, headless commerce)
- Shopify Magic (AI content generation)
- Sidekick (LLM-powered agentic AI assistant)
- Shopify Flow (workflow automation)
- Omnichannel analytics (online + social + POS unified)
- App ecosystem with thousands of extensions
- Profit-centric reporting

**Where they fail for Bangladesh:**
- ❌ Expensive: $29–$399/month (unaffordable for BD SMEs at ৳3,500–৳47,000/month)
- ❌ No bKash or Nagad integration
- ❌ No Bangla AI or festival features
- ❌ No understanding of BD market dynamics
- ❌ No WhatsApp Business integration (native)
- ❌ No monsoon/weather-aware forecasting
- ❌ No cross-vendor intelligence (isolated stores)

**PRISM V3 vs. Shopify:**

| Dimension | Shopify | PRISM V3 |
|---|---|---|
| Pricing | $29–$399/mo | ৳0–৳5,000/mo (~$0–$42) |
| AI Assistant | Sidekick (English) | PRISM Sahayak (Bangla + English) |
| Payments | Stripe (no BD) | bKash + Nagad + SSLCommerz native |
| Festival Intel | None | Built-in Bangladesh calendar |
| Weather | None | OpenWeatherMap demand signals |
| Marketplace | No (single-store SaaS) | Yes (multi-vendor marketplace + SaaS hybrid) |

### 3.3 Netstock

**What they do well:**
- AI-powered demand forecasting (Pivot Forecasting®)
- Opportunity Engine™ (real-time risk/opportunity identification)
- Automated model selection per SKU
- Scenario planning for best/worst cases
- ERP integration (SAP, NetSuite, etc.)

**Where they fail:**
- ❌ No commerce layer (inventory only, no storefront)
- ❌ Enterprise pricing ($1,000+/month)
- ❌ English only
- ❌ No Bangladesh-specific features
- ❌ No mobile-first design for SMEs

**PRISM V3 vs. Netstock:**

| Dimension | Netstock | PRISM V3 |
|---|---|---|
| Demand Forecasting | Pivot Forecasting® (proprietary) | GBR ONNX (13 features) + feedback loop |
| Commerce | ❌ None | Full multi-vendor marketplace |
| Pricing | $1,000+/mo | ৳500–৳5,000/mo |
| Language | English | Bangla + English |
| Local Features | None | Festival + Weather + bKash/Nagad |

### 3.4 Sheba.xyz

**What they do well:**
- Service marketplace (150+ categories)
- Three-app ecosystem (Sheba.xyz + sManager + sBusiness)
- sManager SaaS for SME operations
- Financial inclusion for micro-entrepreneurs
- AWS infrastructure

**Where they fail:**
- ❌ Service-only (no product commerce)
- ❌ No AI or predictive intelligence
- ❌ No inventory management
- ❌ No demand forecasting

**PRISM V3 vs. Sheba.xyz:** Different vertical entirely, but PRISM adopts Sheba's strength of building an SME SaaS ecosystem alongside the marketplace.

### 3.5 Chaldal

**What they do well:**
- AI demand forecasting for grocery
- Micro-warehouse network for 1-hour delivery
- Route optimization
- ChaldalPay digital wallet
- Vertical integration (Vegetable Network, BanglaMeds)

**Where they fail:**
- ❌ Grocery-only, no multi-vendor
- ❌ No vendor-facing AI tools
- ❌ Severe financial struggles (2025 layoffs, liquidity crisis)
- ❌ No SaaS offering for other merchants

**Lesson from Chaldal:** Their operational model (micro-warehouses, vertical integration) is too capital-intensive for a startup. PRISM's 3PL integration model (Pathao, Paperfly, RedX) is leaner and more scalable.

---

## 4. Problem Statement (Expanded)

### The 10 Core Failure Modes for Bangladeshi SME Commerce

| # | Problem | Real-World Impact | Who Suffers | PRISM V3 Solution |
|---|---|---|---|---|
| **P1** | **Stock Loss** | Overstocking ties up capital. Stockouts during Eid kill revenue. | Vendors | GBR demand forecasting + smart reorder alerts |
| **P2** | **Fragmented Operations** | Orders, inventory, analytics in separate tools (or vendor's head). | Vendors, Admins | Unified platform — one login, everything connected |
| **P3** | **Zero Foresight** | Vendors react *after* problems. No proactive "you will run out in 9 days." | Vendors | AI forecast + WhatsApp alerts + What-If planner |
| **P4** | **Language Barrier** | Existing tools are English-only. Excludes 80% of BD vendors. | Vendors, Buyers | Bangla UI + Bangla AI assistant + Bangla WhatsApp |
| **P5** | **Festival Blindness** | No tool accounts for Eid/Puja/Boishakh demand surges. | Vendors | Festival Intelligence Calendar with 14-day alerts |
| **P6** | **Weather Ignorance** | Monsoon shifts demand. No tool factors this. | Vendors | Weather-aware demand signals via OpenWeatherMap |
| **P7** | **Delivery Opacity** | No visibility into where orders are. Vendor can't track delivery performance. | Buyers, Vendors | 3PL integration + unified tracking + performance metrics |
| **P8** | **No Revenue Infrastructure** | SMEs selling on Facebook have no payment, no invoice, no tax compliance. | Vendors | PRISM Wallet + bKash/Nagad + auto-invoices + VAT reports |
| **P9** | **Social Commerce Disconnect** | 80% of BD e-commerce discovery is on Facebook. No bridge to proper platform. | Vendors, Buyers | Facebook Shops sync + WhatsApp Catalog + social sharing |
| **P10** | **No Affordable AI** | AI/ML tools are enterprise-priced (Netstock: $1K+/mo). SMEs are excluded. | Vendors | Free tier AI forecasting + ৳500/mo for full AI suite |

### 4.1 User Validation Research

> **Method:** 5 informal interviews with small vendors in Dhaka (Chawkbazar, Mirpur, Uttara) and via Facebook vendor groups.

| Vendor | Business Type | Key Pain Point | Current Tool |
|---|---|---|---|
| V1 (Chawkbazar) | Fabric & garments | Always over-buys before Eid, left with dead stock | Excel / notebook |
| V2 (Mirpur) | Electronics accessories | No alert when stock goes low — finds out at checkout | None |
| V3 (Facebook group) | Handmade crafts | No idea which products to restock after a sales spike | Daraz seller panel only |
| V4 (Uttara) | Grocery & FMCG | Manually checks 200+ SKUs weekly — takes 3 hrs/week | WhatsApp groups |
| V5 (Facebook group) | Clothing vendor | Wishes platform could tell her what to order before running out | Shopify + gut feel |

### Key Validation Findings

- ✅ **4 of 5** vendors expressed strong interest in automated reorder alerts
- ✅ **All 5** vendors use WhatsApp daily for supplier communication
- ✅ **3 of 5** experienced a stockout during a festival in the past year
- ✅ **0 of 5** use any AI or predictive tool
- ✅ **4 of 5** communicate primarily in Bangla
- ✅ **3 of 5** sell on Facebook alongside (or instead of) a formal platform
- ✅ **All 5** said they would pay ৳500/month for a tool that predicts demand accurately

---

## 5. Unique Value Proposition

> **Core Thesis:**
> Most commerce platforms tell you **what happened.**
> PRISM tells you **what is about to happen** — and exactly what to do about it.
> Then it helps you **sell it live**, **chat with buyers**, and **get paid instantly** — all in Bangla.
>
> Predictive inventory intelligence + live commerce + GenAI shopping assistant + social commerce bridge,
> unified under a single Bangla-first mobile platform — with weather-awareness, festival intelligence,
> cross-vendor collective learning, and a SaaS model priced for Bangladeshi SMEs.

### Key Differentiators (18 — V3 Expansion):

1. **GBR Demand Forecasting per SKU** — Gradient Boosting Regressor serialized to ONNX predicts sales for 7, 14, and 30 days, with non-linear festival-peak modeling.

2. **Smart Reorder Point Engine** — fires alerts *before* stockout using EOQ model with AI-adjusted safety stock, factoring in festival proximity, weather conditions, and learned lead times.

3. **Bangladesh Festival Intelligence Calendar** — built-in table of Eid, Durga Puja, Pohela Boishakh, and national holidays auto-populates ML features with a 14-day pre-surge window.

4. **Bengali (বাংলা) Language Support** — full UI translation, WhatsApp alerts in Bangla, GenAI assistant speaks Bangla.

5. **Cross-Vendor Category Emergence** — category-level demand signals aggregated anonymously across all vendors.

6. **GenAI Commerce Assistant (PRISM Sahayak)** — (NEW V3) LLM-powered AI assistant in Bangla and English. Vendors ask "কোন পণ্যে ডিসকাউন্ট দেব?" and get AI-powered answers. Buyers search conversationally.

7. **RAG Semantic Product Search** — (NEW V3) Products indexed as vector embeddings in pgvector. Buyers type natural language queries ("ঈদের জন্য লাল শাড়ি, বাজেট ২০০০") and get semantically relevant results.

8. **Live Commerce Engine** — (NEW V3) Vendors go live, pin products, buyers shop during the stream. Real-time chat + reactions + AI product recommendations during stream.

9. **Social Commerce Bridge** — (NEW V3) Sync product catalog to Facebook Shops, WhatsApp Catalog. Influencer/affiliate tracking. Social sharing rewards.

10. **PRISM Wallet + BNPL** — (NEW V3) Digital wallet for instant refunds, loyalty rewards. Buy-Now-Pay-Later via local partners for installment purchases.

11. **3PL Logistics Integration** — (NEW V3) Connect to Pathao, Paperfly, RedX, Steadfast. Auto-routing, zone-based pricing, unified tracking, COD reconciliation.

12. **In-App Buyer-Seller Chat** — (NEW V3) Real-time messaging with product cards, image sharing, AI-suggested responses.

13. **Coupon Optimization** — recommends the minimum discount to clear surplus stock based on price elasticity.

14. **Anomaly Detection** — flags suspicious order patterns for fraud review using Z-score on behavioral signals.

15. **Vendor Performance Scoring** — composite trust tier fed by fulfillment, ratings, speed, and delivery performance.

16. **Weather-Aware Demand Signals** — OpenWeatherMap integration captures monsoon-driven demand shifts.

17. **What-If Scenario Planner** — vendors simulate forecast changes by adjusting input parameters.

18. **Closed-Loop ML Feedback** — GBR model retrains automatically when forecast error exceeds threshold.

---

## 6. Business Model & Monetization

### 6.1 Revenue Model — Hybrid SaaS + Commission

> PRISM combines recurring SaaS subscription revenue with per-transaction commissions and value-added services. This hybrid model maximizes revenue while keeping the entry barrier low for SMEs.

```
┌─────────────────────────────────────────────────────────────────┐
│                    PRISM V3 REVENUE STREAMS                     │
│                                                                 │
│  ┌─── Recurring ──────────┐   ┌─── Transactional ───────────┐  │
│  │ SaaS Subscriptions     │   │ Commission per sale (2-5%)  │  │
│  │ (৳0 – ৳5,000+/mo)     │   │ Payment processing (1-1.5%)│  │
│  └────────────────────────┘   │ Logistics markup (৳5-20)    │  │
│                                └─────────────────────────────┘  │
│  ┌─── Advertising ────────┐   ┌─── Financial ───────────────┐  │
│  │ Promoted listings       │   │ Wallet float income         │  │
│  │ Live commerce slots     │   │ BNPL partner revenue share  │  │
│  │ Homepage featured spots │   │                             │  │
│  └────────────────────────┘   └─────────────────────────────┘  │
└─────────────────────────────────────────────────────────────────┘
```

### 6.2 Pricing Tiers

| Tier | Price (৳/mo) | Products | Commission | AI Features | Live Commerce | Support |
|---|---|---|---|---|---|---|
| **Free** | ৳0 | 5 | 5% | Basic forecast only | No | Community |
| **Starter** | ৳500 (~$4.20) | 50 | 4% | Full AI (11 modules) | 2 streams/mo | Email |
| **Growth** | ৳2,000 (~$16.80) | Unlimited | 3% | Full AI + GenAI + What-If | Unlimited | Priority Chat |
| **Enterprise** | Custom | Unlimited | 2% | Everything + API + white-label | Unlimited + priority slots | Dedicated Manager |

> **Why this pricing works:** Shopify's cheapest plan is $29/mo (~৳3,500). PRISM's Starter at ৳500/mo is **7x cheaper** while offering BD-specific features Shopify doesn't have. Even the Growth tier at ৳2,000/mo is cheaper than Shopify Basic and includes AI forecasting that Shopify doesn't offer at any tier.

### 6.3 Revenue Projections (Conservative)

| Metric | Month 6 | Month 12 | Month 24 |
|---|---|---|---|
| Active Vendors | 200 | 1,000 | 5,000 |
| Paid Vendors (est. 30%) | 60 | 300 | 1,500 |
| Avg. Subscription/mo | ৳800 | ৳1,000 | ৳1,200 |
| Subscription Revenue/mo | ৳48,000 | ৳300,000 | ৳1,800,000 |
| GMV/mo | ৳2,000,000 | ৳20,000,000 | ৳150,000,000 |
| Commission Revenue/mo (3.5% avg) | ৳70,000 | ৳700,000 | ৳5,250,000 |
| Ads + Other/mo | ৳10,000 | ৳100,000 | ৳500,000 |
| **Total Revenue/mo** | **৳128,000** | **৳1,100,000** | **৳7,550,000** |
| **Total Revenue/mo (USD)** | **~$1,075** | **~$9,240** | **~$63,450** |

### 6.4 Unit Economics

| Metric | Target |
|---|---|
| Customer Acquisition Cost (CAC) | ৳500–1,000 per vendor |
| Lifetime Value (LTV) | ৳30,000–60,000 (avg. 24-month retention) |
| LTV:CAC Ratio | 30:1 – 60:1 (excellent) |
| Monthly Infrastructure Cost | ৳6,000–18,000 ($50–$150) initial |
| Break-Even | Month 8–10 (covering infrastructure + marginal costs) |
| Gross Margin | 70–85% (SaaS + commission) |

---

## 7. User Architecture — 7 Roles, One Ecosystem

PRISM V3 has **seven distinct user roles**, each with a tailored experience. V3 adds two new roles: Affiliate/Influencer and Finance Admin.

| Capability | Super Admin | Vendor | Buyer | Support & Billing | Delivery Partner | Affiliate | Finance Admin |
|---|---|---|---|---|---|---|---|
| Full platform visibility | ✅ | — | — | — | — | — | — |
| Browse & search products | — | — | ✅ | — | — | — | — |
| Manage product listings | — | ✅ | — | — | — | — | — |
| Handle support tickets | — | — | — | ✅ | — | — | — |
| Update delivery status | — | — | — | — | ✅ | — | — |
| Manage referral campaigns | — | — | — | — | — | ✅ | — |
| Manage platform finances | — | — | — | — | — | — | ✅ |
| View GBR demand forecasts | — | ✅ | — | — | — | — | — |
| Use GenAI Assistant (Sahayak) | — | ✅ | ✅ | — | — | — | — |
| Go LIVE (stream + sell) | — | ✅ | — | — | — | — | — |
| Watch live streams + buy | — | — | ✅ | — | — | — | — |
| Chat with vendors/buyers | — | ✅ | ✅ | ✅ | — | — | — |
| PRISM Wallet | — | — | ✅ | — | — | — | ✅ |
| BNPL checkout | — | — | ✅ | — | — | — | — |
| Sync to Facebook Shops | — | ✅ | — | — | — | — | — |
| Track affiliate commissions | — | — | — | — | — | ✅ | — |
| Revenue & payout dashboard | — | — | — | — | — | — | ✅ |
| Vendor subscription billing | — | — | — | — | — | — | ✅ |
| Checkout (bKash/Nagad/Card/Wallet) | — | — | ✅ | — | — | — | — |
| Receive WhatsApp alerts (EN/বাংলা) | — | ✅ | — | — | ✅ | — | — |
| Language toggle (EN/বাংলা) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Festival demand calendar | — | ✅ | — | — | — | — | — |
| What-If Scenario Planner | — | ✅ | — | — | — | — | — |
| AI model health checks | ✅ | — | — | — | — | — | — |
| Cross-vendor emergence panel | ✅ | — | — | — | — | — | — |
| View assigned deliveries | — | — | — | — | ✅ | — | — |
| Platform-wide analytics | ✅ | — | — | — | — | — | ✅ |

---

## 8. System Architecture — V3

### 8.1 Architecture Overview

PRISM V3 uses a **modular monolith** architecture designed for future microservices extraction. All services are Docker-containerized from Day 1.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    PRISM COMMERCE V3.0 — STARTUP ARCHITECTURE              │
├───────────────────────────────────────────────────────────────────────────── │
│                                                                             │
│  CLIENTS                                                                    │
│  ┌─────────────┐  ┌────────────┐  ┌────────────────┐  ┌────────────────┐  │
│  │ Next.js 15  │  │ React      │  │ Facebook Shops │  │ WhatsApp       │  │
│  │ Web + PWA   │  │ Native App │  │ (Sync SDK)     │  │ Business API   │  │
│  └──────┬──────┘  └─────┬──────┘  └───────┬────────┘  └───────┬────────┘  │
│         └──────────────┬─┘                 │                   │            │
│                        ▼                   ▼                   ▼            │
│  ┌─────────────────────────────────────────────────────────────────────┐    │
│  │              API GATEWAY (Kong / Nginx)                             │    │
│  │         Rate Limiting · Auth · Routing · CORS · CDN                │    │
│  └──────────────────────────────┬──────────────────────────────────────┘    │
│                                 ▼                                           │
│  CORE SERVICES (NestJS Modular Monolith — Docker Container)                │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐        │
│  │Commerce  │ │Inventory │ │Orders    │ │Auth &    │ │Payment   │        │
│  │Module    │ │Module    │ │Module    │ │RBAC      │ │Engine    │        │
│  └──────────┘ └──────────┘ └──────────┘ └──────────┘ └──────────┘        │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐        │
│  │AI/ML     │ │Chat &    │ │Logistics │ │Live      │ │Social    │        │
│  │Engine    │ │Messaging │ │Engine    │ │Commerce  │ │Commerce  │        │
│  └──────────┘ └──────────┘ └──────────┘ └──────────┘ └──────────┘        │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐                     │
│  │Billing & │ │Notif &   │ │Analytics │ │GenAI     │                     │
│  │Subscript.│ │Comms     │ │Engine    │ │Gateway   │                     │
│  └──────────┘ └──────────┘ └──────────┘ └──────────┘                     │
│                                 │                                           │
│  ┌──────────────────────────────┴──────────────────────────────────────┐    │
│  │              EVENT BUS (BullMQ — Redis Streams)                     │    │
│  │   Async: notifications, analytics, ML retraining, email, SMS       │    │
│  └────────────────────────────────────────────────────────────────────┘    │
│                                 │                                           │
│  DATA LAYER                     │                                           │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐        │
│  │PostgreSQL│ │Redis 7   │ │S3/MinIO  │ │Meili-    │ │Ollama    │        │
│  │16 +      │ │Cache +   │ │Files &   │ │search    │ │(LLM)     │        │
│  │pgvector  │ │Queue +   │ │Images &  │ │Full-text │ │Llama 3.2 │        │
│  │(Primary) │ │Sessions  │ │Videos    │ │Search    │ │/ Mistral │        │
│  └──────────┘ └──────────┘ └──────────┘ └──────────┘ └──────────┘        │
│                                                                             │
│  INFRASTRUCTURE                                                             │
│  ┌─────────────────────────────────────────────────────────────────────┐    │
│  │  Docker Compose (dev) → Docker Swarm / K8s (prod)                  │    │
│  │  CI/CD: GitHub Actions → ArgoCD                                    │    │
│  │  Monitoring: Grafana + Prometheus + Loki                           │    │
│  │  Error Tracking: Sentry                                            │    │
│  │  CDN: Cloudflare                                                   │    │
│  │  Hosting: VPS (Hetzner/DigitalOcean) or AWS                        │    │
│  └─────────────────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 8.2 Key Architecture Principles

1. **Modular Monolith** — All business logic in one NestJS application organized as independent modules. Each module has its own controllers, services, and Prisma models. Modules communicate via internal events (BullMQ) not direct imports — making future microservices extraction straightforward.

2. **Event-Driven Processing** — Non-critical paths (notifications, analytics, ML retraining, email, SMS) are processed asynchronously via BullMQ queues backed by Redis Streams. This keeps API responses fast and the system resilient.

3. **LLM Gateway Pattern** — A unified abstraction layer (`GenAiGatewayService`) that routes LLM requests to Ollama (local, free) with automatic fallback to OpenAI/Gemini API. Future-proofs against model changes.

4. **RAG Pipeline** — Products → text chunks → vector embeddings (pgvector) → similarity search → context injection → LLM response. Enables both semantic product search and the GenAI assistant.

5. **Docker-First** — Every service (NestJS, PostgreSQL, Redis, Meilisearch, Ollama, MinIO) runs in Docker. `docker-compose up` starts the entire stack locally. Production uses the same images.

6. **Privacy by Design** — PostgreSQL RLS enforces vendor data isolation. Cross-vendor signals are computed server-side as aggregates only. Minimum 3 vendor threshold for category velocity.

### 8.3 Data Flow — Five Core Journeys

#### Journey A: Vendor Views GBR Forecast (Same as V2, Enhanced)

```
Vendor → Next.js → NestJS AI Module → Redis cache check
    [miss] → Historical data + Festival + Weather + Category velocity
    → ONNX GBR inference (<80ms) → Cache in Redis (24h) → Return
```

#### Journey B: Buyer Shops via GenAI Assistant (NEW V3)

```
Buyer types: "ঈদের জন্য লাল শাড়ি, বাজেট ২০০০ টাকা"
    → NestJS GenAI Gateway
    → Step 1: Embed query via sentence-transformer
    → Step 2: pgvector similarity search → top 10 products
    → Step 3: Filter by price (≤৳2000), availability
    → Step 4: LLM generates personalized response with product cards
    → Return: Bangla response + clickable product carousel
```

#### Journey C: Buyer Places Order (Enhanced with Wallet + 3PL)

```
Buyer → Cart → Checkout → Select payment (bKash/Nagad/Card/Wallet/BNPL)
    → NestJS Payment Engine → Gateway redirect/Wallet deduct
    → Webhook verification → Order created (atomic)
    → BullMQ: Assign 3PL (Pathao/Paperfly) based on zone
    → BullMQ: Send WhatsApp notification to vendor
    → BullMQ: Update inventory + check reorder point
    → Supabase Realtime: Push status to buyer
```

#### Journey D: Vendor Goes LIVE (NEW V3)

```
Vendor taps "Go Live" → LiveKit WebRTC room created
    → Viewers join → see stream + pinned product cards
    → Viewer taps product → adds to cart (in-stream)
    → Real-time: viewer count, reactions, sales counter
    → AI: trending product suggestions during stream
    → Stream ends → summary: views, sales, revenue
```

#### Journey E: Social Commerce (NEW V3)

```
Vendor enables Facebook Shops sync
    → NestJS Social Module → Facebook Commerce API
    → Product catalog synchronized nightly
    → Buyer discovers on Facebook → redirected to PRISM checkout
    → Affiliate link tracked → commission credited
```

### 8.4 Service Communication Map

| From | To | Protocol & Purpose |
|---|---|---|
| Next.js / React Native | API Gateway | HTTPS REST — all feature calls |
| API Gateway | NestJS Modules | Internal routing — auth, rate limiting pre-applied |
| NestJS API | PostgreSQL 16 | Prisma ORM — queries and mutations |
| NestJS API | Redis 7 | ioredis — cache, sessions, BullMQ queues |
| NestJS API | Meilisearch | REST — full-text product search |
| NestJS GenAI | Ollama (local) | HTTP — LLM inference (Llama 3.2 / Mistral) |
| NestJS GenAI | pgvector | SQL — vector similarity search for RAG |
| NestJS GenAI | OpenAI API (fallback) | HTTPS REST — GPT-4 / GPT-4o when Ollama unavailable |
| NestJS GBR Module | ONNX Runtime (in-process) | Node.js — demand forecast inference <80ms |
| NestJS Live Commerce | LiveKit Server | WebRTC — live video streaming |
| NestJS Chat | Socket.io Gateway | WebSocket — real-time buyer-seller messaging |
| NestJS Notifications | Meta WhatsApp Cloud API | HTTPS POST — EN/বাংলা alerts |
| NestJS Notifications | Resend / AWS SES | HTTPS — transactional emails |
| NestJS Notifications | Twilio / BD SMS | HTTPS — SMS OTP and order updates |
| NestJS Logistics | Pathao / Paperfly / RedX API | HTTPS REST — order assignment, tracking |
| NestJS Payments | bKash / Nagad / SSLCommerz | HTTPS REST — payment initiation + webhook |
| NestJS Social | Facebook Commerce API | HTTPS — catalog sync, order import |
| BullMQ Workers | All async operations | Redis Streams — notifications, analytics, ML retraining |
| NestJS CRON (hourly) | PostgreSQL + Redis | Category velocity aggregation |
| NestJS CRON (daily) | OpenWeatherMap + Redis | Weather forecast refresh |
| NestJS CRON (weekly) | ONNX + PostgreSQL | GBR model accuracy evaluation + retraining |
| Grafana + Prometheus | NestJS /metrics | HTTP scrape — observability |

---

## 9. Core Feature Set

### 9.1 Commerce Layer

| Feature | Detail |
|---|---|
| **Multi-Vendor Product Catalog** | Vendors list products with variants (size, color), pricing, images, and videos. Buyers browse with smart filters by category, price, rating, and location. SEO-friendly slugs. Bilingual product names and descriptions. |
| **Semantic AI Search (NEW V3)** | RAG-powered search via pgvector. Buyers type natural language in Bangla or English. Meilisearch handles typo-tolerant full-text search as the fast path; pgvector handles semantic queries. |
| **Cart, Coupons & Checkout** | Persistent Zustand cart (synced to localStorage + PostgreSQL for cross-device). AI-optimized coupon suggestions. bKash, Nagad, SSLCommerz, PRISM Wallet, and BNPL payment options. |
| **Full Order Lifecycle** | State machine: `Pending → Confirmed → Processing → Picked Up → In Transit → Delivered → Completed`. Real-time push via Socket.io. 3PL-integrated tracking. |
| **Reviews & Vendor Ratings** | Post-delivery review with 1–5 star rating + text + image upload. Verified purchase badge. Feeds into Vendor Performance Score. |
| **AI Product Recommendations** | "Trending Now" and "You May Like" shelves powered by GBR velocity + GenAI collaborative filtering. |
| **Wishlist & Price Alerts** | Buyers save products. WhatsApp/push alert when item goes on sale or drops in price. |
| **Live Commerce (NEW V3)** | Vendors go live via WebRTC (LiveKit). Pin products during stream. Buyers buy in-stream without leaving. Chat + reactions + AI suggestions. |

### 9.2 Inventory Layer

| Feature | Detail |
|---|---|
| **Real-Time Stock Tracking** | Per-product, per-variant inventory auto-decrements on purchase via atomic Prisma transaction. Full audit log. |
| **Context-Aware Low-Stock Alerts** | GBR ML-triggered (not fixed threshold). Considers demand velocity, festivals, weather, and learned lead times. |
| **WhatsApp Low-Stock Notifications** | When stock ≤ ROP, vendor receives WhatsApp in preferred locale. Fallback: Push → In-app. |
| **What-If Scenario Planner** | Adjust GBR input features interactively. See instant re-forecast. |
| **Sales Analytics Dashboard** | Revenue charts, top products, conversion rates, weather impact overlay, period-over-period. |
| **Exportable Reports** | CSV, JSON, PDF, Excel exports. Scheduled weekly email digest. |
| **Bulk Import/Export (NEW V3)** | CSV/Excel upload for product catalog and inventory. Speeds up onboarding for vendors with 100+ SKUs. |

### 9.3 Admin & Operations Layer

| Feature | Detail |
|---|---|
| **Vendor Approval & KYC (NEW V3)** | Document verification (NID, trade license) during onboarding. Admin approval before listings go live. |
| **Anomaly Alert Dashboard** | Flagged orders with Z-score detail, buyer history, one-click Clear/Escalate. |
| **Vendor Performance Leaderboard** | VPS scores with trust tier badges. Low-scoring vendors flagged. Top vendors get featured placement. |
| **Platform-Wide Analytics** | Total GMV, order volume, user growth, revenue by vendor, category breakdown, delivery metrics, financial reports. |
| **Invoice Generation** | Auto-generated PDF invoices in EN + বাংলা using @react-pdf/renderer. Stored in S3/MinIO. |
| **Cross-Vendor Emergence Panel** | Category velocity trends and per-vendor forecast error charts. |
| **Delivery Partner Management** | Assign partners, track times, view 3PL performance. Partners update via mobile PWA. |
| **Subscription Management (NEW V3)** | View/manage vendor subscriptions, plan changes, billing history, failed payments. |

### 9.4 Bengali (বাংলা) Language & Localization Layer

| Component | Implementation Detail |
|---|---|
| **Routing & Locale Detection** | Next.js App Router with next-intl middleware. Routes: `/en/...` and `/bn/...`. Auto-detects browser locale. |
| **UI Translation Files** | JSON files at `/messages/en.json` and `/messages/bn.json`. Covers all UI strings including AI explanations. |
| **WhatsApp Bangla Templates** | Meta-approved templates for all notification types in both EN and বাংলা. |
| **Number & Currency Formatting** | Bengali numerals (১২৩৪) via `Intl.NumberFormat` with `locale='bn-BD'`. Currency as ৳. |
| **GenAI in Bangla (NEW V3)** | PRISM Sahayak responds in Bangla. Product descriptions can be generated in Bangla via LLM. |
| **Onboarding in Bangla** | Full vendor onboarding wizard in Bangla with progress bar and tooltips. |

### 9.5 Bangladesh Festival Intelligence Calendar

| Festival | Approx. Date | Surge Window | Demand Impact |
|---|---|---|---|
| **Eid-ul-Fitr (ঈদুল ফিত্র)** | Variable (lunar) | 14 days pre-Eid | Clothing: +180%, Groceries: +60% |
| **Eid-ul-Adha (ঈদুল আযহা)** | Variable (lunar) | 14 days pre-Eid | Livestock, clothing, food: +120% |
| **Durga Puja (দুর্গাপূজা)** | Oct (variable) | 10 days pre-Puja | Clothing, sweets, gifts: +90% |
| **Pohela Boishakh (পহেলা বৈশাখ)** | April 14 | 7 days pre-event | Clothing, food, crafts: +70% |
| **Victory Day (বিজয় দিবস)** | December 16 | 5 days pre-event | Clothing, accessories: +30% |
| **Valentine's Day** | February 14 | 5 days pre-event | Gifts, crafts, food: +40% |
| **Independence Day (স্বাধীনতা দিবস)** | March 26 | 3 days pre-event | Flags, accessories: +20% |
| **Ramadan Start (রমজান)** | Variable (lunar) | 30-day sustained | Dates, food, prayer items: +80% |

Three GBR features injected at every inference: `is_festival_week`, `days_to_next_festival`, `festival_type` (one-hot encoded).

---

## 10. AI Intelligence Layer — 11 Modules + GenAI

All original V2 AI modules are retained and enhanced. V3 adds the GenAI layer (Module 12) and RAG Search (Module 13).

### Cold-Start Solution (Three-Tier Bootstrap)

| Tier | When | What Happens |
|---|---|---|
| **Tier 1 (Day 0)** | Onboarding | Vendor enters past 30-day sales per product. Stored as `synthetic_sales_seed`. |
| **Tier 2 (Week 1+)** | Early use | Real orders supplement seed data. `data_quality_score` tracks ratio. |
| **Tier 3 (Day 90+)** | Full maturity | Seed deprecated. Model retrains fully on real data. |

### Module 01 — ONNX Gradient Boosting Regressor

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/forecast/:productId` |
| Model | GradientBoostingRegressor → ONNX (~80–150KB) |
| Runtime | onnxruntime-node v1.17+ — inference **<80ms** |
| Input Features (13) | `quantity_7d`, `quantity_14d`, `quantity_30d`, `rolling_mean_7d`, `rolling_std_7d`, `trend_slope`, `day_of_week`, `is_festival_week`, `days_to_next_festival`, `festival_type`, `temperature_avg`, `precipitation_mm`, `category_velocity_score` |
| Output | `{ forecast_7d, forecast_14d, forecast_30d, confidence, feature_importance, model_version, data_quality_score }` |
| Cache | Redis 24h TTL |

### Module 02 — Smart Reorder Point Calculator

`ROP = (Avg Daily Demand × Lead Time) + Safety Stock` with festival and weather multipliers. Lead time auto-learned from supplier history.

### Module 03 — Sales Velocity Momentum Ranker

Exponential smoothing on 7-day rolling sales. Accelerating → "Trending" shelf. Decelerating → vendor WhatsApp alert.

### Module 04 — Coupon Optimization Advisor

`Optimal Discount = (Surplus Ratio - 1) / Price Elasticity`. Triggers when supply days > 45.

### Module 05 — Order Anomaly Detector

Z-Score on 5 signals: order frequency, quantity vs. average, address mismatch, payment method age, device fingerprint. Composite > 2.5 → flag + soft-pause.

### Module 06 — Vendor Performance Score (VPS)

0–100 score from: Fulfillment Rate (35%), Avg Rating (25%), Response-to-Ship (15%), Delivery Time (15%), Dispute Rate (10%). Trust tiers: Platinum (85+), Gold (70-84), Silver (50-69), Watch (<50).

### Module 07 — WhatsApp Business Notification Engine

Meta Cloud API. EN + বাংলা templates. Trigger events: low stock, order status, delivery, anomaly, weekly forecast, festival reminder, weather alert. Fallback: WhatsApp → Push → In-app.

### Module 08 — Cross-Vendor Category Emergence

Hourly CRON aggregates sales velocity by category across ALL vendors. `category_velocity_score` cached in Redis (1h TTL). Injected as GBR feature. Min 3 vendors per category for privacy.

### Module 09 — Closed-Loop GBR Feedback

Weekly CRON compares predicted vs. actual. If rolling error > 25% → triggers retraining. System improves silently over time.

### Module 10 — What-If Scenario Planner

`POST /api/ai/scenario` — vendor adjusts feature sliders → instant ONNX re-inference with modified feature vector. Side-by-side comparison.

### Module 11 — Weather-Aware Demand Engine

Daily CRON fetches OpenWeatherMap 5-day forecast. Derives `temperature_avg`, `precipitation_mm`, `is_monsoon`. Injected into GBR. Category-weather correlation matrix drives demand adjustments.

### Module 12 — GenAI Commerce Assistant "PRISM Sahayak" (NEW V3)

| Property | Value |
|---|---|
| Endpoint | `POST /api/ai/assistant` |
| LLM | Ollama (Llama 3.2 / Mistral 7B) local; OpenAI GPT-4o fallback |
| Languages | Bangla + English (auto-detects from input) |
| **For Vendors** | "কোন পণ্যে ডিসকাউন্ট দেব?" → AI analyzes stock levels, forecasts, margins, and surplus ratio. Responds with specific product recommendations and optimal discount percentages. |
| **For Buyers** | "ঈদের জন্য ৳2000 বাজেটে শাড়ি চাই" → RAG retrieves matching products from pgvector, LLM generates conversational response with product cards. |
| **Content Generation** | Vendors paste basic product info in Bangla → AI generates SEO-optimized bi-lingual descriptions, bullet points, and meta tags. |
| RAG Pipeline | Products → chunk → embedding (sentence-transformers) → pgvector → similarity search → LLM context injection → response |
| Safety | Content filtering, hallucination guard (only recommend products that exist in DB), no financial advice |
| Rate Limit | 20 queries/vendor/hour (Free: 5/day) |

### Module 13 — RAG Semantic Product Search (NEW V3)

| Property | Value |
|---|---|
| Endpoint | `GET /api/search/semantic?q=...` |
| Tech | pgvector extension on PostgreSQL 16 |
| Embedding Model | `all-MiniLM-L6-v2` (384-dim, fast, multilingual) or `paraphrase-multilingual-MiniLM-L12-v2` for better Bangla |
| Index | IVFFlat index on `product_embeddings` table |
| Flow | Query → embed → cosine similarity search → filter (price, category, availability) → return ranked results |
| Hybrid | Semantic results merged with Meilisearch full-text results using reciprocal rank fusion |
| Update | Product embeddings regenerated on product create/update via BullMQ background job |

---

## 11. New Strategic Modules (A–H)

### Module A — Live Commerce Engine

> Vendors go LIVE from their dashboard — stream video, pin products, viewers buy in real-time.

| Property | Detail |
|---|---|
| **Tech** | LiveKit (open-source WebRTC SFU) for media server. Socket.io for chat/reactions overlay. |
| **Vendor Experience** | One-tap "Go Live" from dashboard. Pin up to 5 products. See viewer count + real-time sales counter. Schedule streams in advance. |
| **Buyer Experience** | Browse "PRISM Live" section on homepage. Watch streams. Tap product overlay → add to cart → checkout without leaving stream. Live chat with emoji reactions. |
| **AI Integration** | During stream, GenAI suggests trending products to vendor ("পণ্য X এখন ট্রেন্ডিং, পিন করুন!"). Post-stream analytics with AI insights. |
| **Monetization** | Free tier: no live. Starter: 2 streams/mo. Growth+: unlimited. Premium homepage carousel slots: ৳500-2000/slot. |
| **Recording** | Streams auto-recorded and available as shoppable video replays. |
| **Scale** | LiveKit handles 1000+ concurrent viewers per room. Horizontal scaling via multiple SFU instances. |

### Module B — Social Commerce Bridge

| Property | Detail |
|---|---|
| **Facebook Shops Sync** | Vendors connect their Facebook Page. PRISM syncs product catalog via Facebook Commerce API (nightly batch). Orders from Facebook redirected to PRISM checkout. |
| **WhatsApp Catalog** | Product catalog viewable in WhatsApp Business profile. "Buy on PRISM" links in catalog items. |
| **Social Sharing** | Every product page has optimized Open Graph meta tags. Share buttons for Facebook, WhatsApp, Instagram. Short links with tracking. |
| **Referral System** | Buyers earn ৳50 PRISM Wallet credit for each successful referral purchase. |
| **Influencer/Affiliate Dashboard** | Unique referral codes per affiliate. Track clicks, conversions, commission. Auto-payout to bKash/Wallet. |

### Module C — PRISM Wallet & Financial Services

| Property | Detail |
|---|---|
| **PRISM Wallet** | Digital wallet for buyers. Load via bKash/Nagad/bank. Spend on PRISM purchases. Instant refunds to wallet (no 3-5 day wait). |
| **Wallet Benefits** | 2% cashback on wallet payments (capped at ৳100/order). Incentivizes wallet adoption over COD. |
| **BNPL Integration** | Partner with ShopUp Pay, iPay, or similar BD BNPL provider. 3-month installment option for orders > ৳2,000. |
| **Vendor Disbursement** | Weekly automated payouts to vendor bKash/bank account. Commission auto-deducted. Payout reports with invoice. |
| **Transaction Ledger** | Double-entry bookkeeping for all platform transactions. Audit-ready. |
| **Tax Compliance** | Auto-generate monthly VAT summary reports for vendors. |

### Module D — Logistics & Fulfillment Engine

| Property | Detail |
|---|---|
| **3PL Partners** | Integrate with Pathao Parcel, Paperfly, RedX, Steadfast, eCourier via their APIs. |
| **Auto-Routing** | When order confirmed → system selects optimal 3PL based on: delivery zone, package weight, vendor preference, cost, SLA. |
| **Zone-Based Pricing** | Dhaka Metro (৳60–80), Dhaka Suburban (৳80–120), Divisional HQ (৳100–150), Rural (৳120–200). Rates configurable per 3PL. |
| **Unified Tracking** | Single tracking page for buyers regardless of which 3PL handles delivery. Status: Picked Up → In Transit → Out for Delivery → Delivered. |
| **COD Reconciliation** | For cash-on-delivery orders: track COD amount collected by delivery partner → reconcile with vendor payout. |
| **Delivery SLA** | Track delivery-time SLA per 3PL. Auto-flag delayed orders. Vendor dashboard shows delivery performance metrics. |
| **Rate Calculator at Checkout** | Buyer sees estimated delivery cost + estimated delivery date before placing order. |

### Module E — In-App Communication Hub

| Property | Detail |
|---|---|
| **Buyer-Seller Chat** | Real-time messaging via Socket.io. Image/file sharing. Product card embedding (buyer can share product link in chat). |
| **AI Auto-Response** | GenAI drafts suggested responses for vendors. Common queries (return policy, shipping time) auto-answered by AI chatbot. |
| **Support Tickets** | Structured ticket system with priority levels, SLA tracking (24h response for Starter, 4h for Growth). Escalation to Super Admin. |
| **Notification Center** | Unified inbox: orders, stock alerts, messages, promotions, system updates — all in one searchable timeline. |
| **Chatbot for Buyers** | FAQ bot handles: order tracking, return/refund status, payment issues. Escalates to human support when needed. |

### Module F — Advanced Analytics & BI

| Feature | Detail |
|---|---|
| **Vendor Profit Dashboard** | True profit: Revenue − COGS − Shipping − Commission − Returns − Coupons. Not just top-line revenue. |
| **Customer Analytics** | RFM segmentation (Recency, Frequency, Monetary). Customer Lifetime Value (CLV). Cohort analysis. |
| **Product Analytics** | ABC classification (A=top 20% by revenue, B=next 30%, C=bottom 50%). Slow-mover alerts. Dead stock identification. |
| **Market Intelligence** | Category trends platform-wide. Demand heatmaps by region (when multi-city). Pricing position vs. category average. |
| **AI Weekly Digest** | Auto-generated email/WhatsApp: "This week: Revenue ↑12%, Product X grew 23%, consider restocking Product Y." |
| **Custom Reports** | Pre-built report templates + simple query builder for custom date ranges and filters. |
| **Export** | PDF, CSV, Excel. Google Sheets sync (Growth+ tier). |

### Module G — Multi-Tenant SaaS Infrastructure

| Property | Detail |
|---|---|
| **Tenant Isolation** | PostgreSQL Row-Level Security (RLS) isolates vendor data at DB layer. Each vendor is a tenant. |
| **Subscription Billing** | Stripe-like billing engine: plan selection → bKash/card charge → auto-renewal → dunning (failed payment retries). |
| **Plan Enforcement** | Product limits, API rate limits, feature gates enforced by NestJS guards based on active subscription plan. |
| **White-Label (Enterprise)** | Custom subdomain, logo, and color scheme. `vendorname.prism.com.bd`. Own branding on buyer-facing pages. |
| **Usage Metering** | Track API calls, storage used, streams, GenAI queries per vendor. Overage alerts and auto-upgrade suggestions. |

### Module H — Affiliate & Influencer Platform

| Property | Detail |
|---|---|
| **Affiliate Registration** | Anyone can apply to become a PRISM affiliate. Approval by admin. Get unique referral code + tracking link. |
| **Commission Structure** | Category-based commission: 5-15% of sale value for affiliate referrals. Configurable per vendor or platform-wide. |
| **Tracking** | UTM-based link tracking. 30-day cookie window. Attribution: last-click model. |
| **Dashboard** | Affiliate sees: clicks, conversions, pending/paid commissions, top-performing products. |
| **Payout** | Monthly auto-payout to bKash/Wallet when balance > ৳500. |
| **Social Integration** | One-click share to Facebook, WhatsApp, Instagram with pre-generated captions and product images. |

---

## 12. Bangladesh-Native Integrations

### 12.1 WhatsApp Business Cloud API

| Property | Detail |
|---|---|
| **Why?** | 45M+ WhatsApp users in BD. Higher open rates than email. |
| API | Meta WhatsApp Business Cloud API |
| Languages | English + Bengali templates |
| Message Types | Low-stock, order updates, delivery, anomaly, forecast digest, festival reminder, weather alert, promotional |
| Fallback | WhatsApp → Web Push → In-app → SMS |

### 12.2 bKash Payment Integration (PRODUCTION)

| Property | Detail |
|---|---|
| **Why?** | 67M registered accounts. Dominant MFS in Bangladesh. |
| Mode | Production PGW (live transactions) |
| Flow | Buyer → bKash checkout → callback → server-side verify → order create |

### 12.3 Nagad Payment Integration (PRODUCTION)

| Property | Detail |
|---|---|
| **Why?** | 20M+ accounts. Fastest-growing MFS. |
| Mode | Production PGW |

### 12.4 SSLCommerz (PRODUCTION)

| Property | Detail |
|---|---|
| **Why?** | Aggregates all BD payment methods: cards (Visa/MC/Amex), bKash, Nagad, Rocket, mobile banking. |
| Mode | Production gateway |

### 12.5 3PL Logistics Partners (NEW V3)

| Partner | Coverage | API | COD Support |
|---|---|---|---|
| Pathao Parcel | Dhaka + major cities | REST API | Yes |
| Paperfly | Nationwide (64 districts) | REST API | Yes |
| RedX | Nationwide | REST API | Yes |
| Steadfast | Nationwide | REST API | Yes |
| eCourier | Nationwide | REST API | Yes |

### 12.6 Facebook Commerce API (NEW V3)

Product catalog sync to Facebook Shops + Instagram Shopping. Order import from Facebook.

### 12.7 OpenWeatherMap API

5-day forecast for demand signals. Daily CRON refresh. Cached in Redis (6h TTL).

---

## 13. Technology Stack — V3

### 13.1 Core Services

| Layer | Technology | Why | Cost |
|---|---|---|---|
| **Frontend** | Next.js 15 (App Router) | SSR, RSC, Turbopack, PWA-ready | Vercel Pro or self-host |
| **Mobile** | React Native (Phase 3) | Cross-platform native app | Free / OSS |
| **PWA** | next-pwa | Offline, installable | Free / OSS |
| **Styling** | Tailwind CSS + shadcn/ui + Radix | Rapid, accessible design system | Free / OSS |
| **i18n** | next-intl | Locale routing, EN + Bangla | Free / OSS |
| **Backend** | NestJS + TypeScript | Modular, scalable, Swagger, CRON | Free / OSS |
| **ML Engine** | onnxruntime-node | In-process GBR inference <80ms | Free / OSS |
| **LLM** | Ollama (Llama 3.2 / Mistral) | Local LLM, free, Bangla support | Free / OSS |
| **LLM Fallback** | OpenAI API (GPT-4o) | High-quality fallback | ~$10-50/mo |
| **Database** | PostgreSQL 16 + pgvector | Primary DB + vector search for RAG | $5-20/mo (Neon/managed) |
| **Auth** | Auth.js (NextAuth) + JWT | Social login, multi-tenant, flexible | Free / OSS |
| **Cache + Queue** | Redis 7 + BullMQ | Cache, sessions, async event bus | $5-10/mo (managed) |
| **Search** | Meilisearch | Full-text, typo-tolerant, fast | Free / OSS |
| **Storage** | S3-compatible (MinIO or AWS S3) | Product images, videos, invoices | $5-20/mo |
| **Real-time** | Socket.io (NestJS gateway) | Chat, live commerce, notifications | Free / OSS |
| **Live Video** | LiveKit (self-hosted) | WebRTC SFU for live commerce | Free / OSS |
| **Payments** | bKash + Nagad + SSLCommerz (LIVE) | Production payment processing | Transaction fees only |
| **Email** | Resend or AWS SES | Transactional emails | Free tier / $5/mo |
| **SMS** | Twilio or BD local gateway | OTP, order updates | ~$10/mo |
| **Weather** | OpenWeatherMap | Demand feature signals | Free tier |

### 13.2 Infrastructure & DevOps

| Layer | Technology | Purpose | Cost |
|---|---|---|---|
| **Containerization** | Docker + Docker Compose | Consistent deployments | Free / OSS |
| **Orchestration** | Docker Swarm → K8s (scale) | Production scaling | Free / OSS |
| **Monorepo** | Turborepo | Shared types, unified builds | Free / OSS |
| **ORM** | Prisma | Type-safe DB queries | Free / OSS |
| **CI/CD** | GitHub Actions + ArgoCD | Automated test + deploy | Free tier + OSS |
| **Monitoring** | Grafana + Prometheus | Metrics, dashboards | Free / OSS |
| **Logging** | Loki + Winston | Structured logs, aggregation | Free / OSS |
| **Error Tracking** | Sentry | Error monitoring | Free tier |
| **Analytics** | PostHog (self-hosted) | Product analytics, funnels | Free / OSS |
| **CDN** | Cloudflare | Edge caching, DDoS protection | Free tier → Pro |
| **Hosting** | VPS (Hetzner / DigitalOcean) | All services containerized | $20-80/mo |
| **API Gateway** | Kong or Nginx | Routing, rate limiting, auth | Free / OSS |
| **Testing** | Jest + Playwright + k6 | Unit, E2E, load testing | Free / OSS |
| **API Docs** | Swagger (NestJS built-in) | Auto-generated OpenAPI | Free / OSS |

**Estimated Monthly Infrastructure Cost: $50–$150 initially, $200–$500 at scale**

---

## 14. Database Schema

### 14.1 Core Tables (Retained from V2, Enhanced)

- `users` — + `subscription_tier`, `wallet_id`, `kyc_status`, `kyc_documents`
- `products` — + `video_url`, `embedding_vector` (via `product_embeddings`)
- `product_variants` — unchanged
- `inventory` — + `learned_lead_time_days` auto-updated from delivery history
- `orders` — + `logistics_partner`, `tracking_id`, `delivery_zone`, `wallet_amount_used`, `bnpl_id`
- `order_items` — unchanged
- `categories` — unchanged
- `reviews` — + `image_urls` (array)

### 14.2 AI Tables (Retained, Enhanced)

- `ai_forecasts` — unchanged
- `forecast_accuracy` — unchanged
- `festival_calendar` — unchanged
- `category_velocity` — unchanged
- `weather_cache` — unchanged
- `synthetic_sales_seed` — unchanged
- `audit_logs` — unchanged
- `notifications` — + `sms` channel

### 14.3 New V3 Tables

#### Monetization

| Table | Key Columns |
|---|---|
| `subscription_plans` | id, name, price_bdt, product_limit, commission_pct, features (jsonb), is_active |
| `vendor_subscriptions` | id, vendor_id, plan_id, status (active/cancelled/past_due), current_period_start, current_period_end, payment_method |
| `platform_commissions` | id, order_id, vendor_id, commission_amount, commission_pct, status (pending/paid), payout_id |
| `vendor_payouts` | id, vendor_id, amount, payout_method (bkash/bank), reference, status, paid_at |
| `promoted_listings` | id, product_id, vendor_id, placement (search/homepage/category), budget_bdt, spent_bdt, start_date, end_date, impressions, clicks |

#### PRISM Wallet

| Table | Key Columns |
|---|---|
| `wallets` | id, user_id, balance, currency (BDT), is_active |
| `wallet_transactions` | id, wallet_id, type (credit/debit), amount, source (bkash_load/refund/cashback/purchase), reference_id, created_at |

#### Chat & Communication

| Table | Key Columns |
|---|---|
| `conversations` | id, buyer_id, vendor_id, last_message_at, unread_count_buyer, unread_count_vendor |
| `messages` | id, conversation_id, sender_id, content, type (text/image/product_card), read_at, created_at |
| `support_tickets` | id, user_id, subject, status (open/in_progress/resolved/closed), priority, assigned_to, sla_deadline, created_at |

#### Live Commerce

| Table | Key Columns |
|---|---|
| `live_streams` | id, vendor_id, title, status (scheduled/live/ended), started_at, ended_at, viewer_count_peak, total_sales_amount, recording_url |
| `stream_products` | id, stream_id, product_id, pinned_at, unpinned_at, units_sold_during |
| `stream_reactions` | id, stream_id, user_id, type (like/heart/fire), created_at |

#### Logistics

| Table | Key Columns |
|---|---|
| `logistics_partners` | id, name, api_endpoint, api_key_encrypted, supported_zones, cod_support, is_active |
| `shipping_zones` | id, name (dhaka_metro/suburban/divisional/rural), partner_id, base_rate, per_kg_rate |
| `shipments` | id, order_id, partner_id, tracking_id, status, picked_up_at, delivered_at, cod_amount, cod_collected |

#### Social Commerce & Affiliates

| Table | Key Columns |
|---|---|
| `social_connections` | id, vendor_id, platform (facebook/instagram), external_id, access_token_encrypted, last_synced_at |
| `referral_codes` | id, user_id (affiliate), code, total_clicks, total_conversions, total_commission |
| `referral_conversions` | id, referral_code_id, order_id, commission_amount, status (pending/paid) |

#### GenAI

| Table | Key Columns |
|---|---|
| `ai_conversations` | id, user_id, role (vendor/buyer), messages (jsonb array), model_used, tokens_used, created_at |
| `product_embeddings` | id, product_id, embedding (vector(384)), model_version, updated_at |

---

## 15. Key API Endpoints

> Full Swagger docs at `/api/docs`. Below is the expanded V3 API surface.

### Auth & Users

| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/auth/register` | Public | Register with role, locale, KYC docs (vendor) |
| POST | `/api/auth/login` | Public | Returns access + refresh tokens |
| POST | `/api/auth/social/:provider` | Public | Social login (Google, Facebook) |
| GET | `/api/users/me` | Auth | Profile with subscription, wallet balance |

### Products & Search

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/products` | Public | Browse with filters |
| POST | `/api/products` | Vendor | Create product (pending approval) |
| POST | `/api/products/bulk-import` | Vendor | CSV/Excel bulk import |
| GET | `/api/search?q=...` | Public | Full-text search (Meilisearch) |
| GET | `/api/search/semantic?q=...` | Public | RAG semantic search (pgvector) |

### Orders, Payments & Delivery

| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/orders` | Buyer | Create order from cart |
| POST | `/api/payment/initiate` | Buyer | Initiate bKash/Nagad/Card/Wallet/BNPL |
| POST | `/api/payment/webhook/:provider` | Webhook | Payment callback + verify |
| GET | `/api/shipments/:orderId/track` | Buyer | Unified 3PL tracking |
| POST | `/api/logistics/assign` | Internal | Auto-assign 3PL to order |

### AI & GenAI

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/ai/forecast/:productId` | Vendor | GBR ONNX forecast |
| POST | `/api/ai/assistant` | Vendor/Buyer | GenAI Sahayak conversation |
| POST | `/api/ai/generate-description` | Vendor | AI product description generator |
| POST | `/api/ai/scenario` | Vendor | What-If planner |
| GET | `/api/ai/reorder/:productId` | Vendor | Smart reorder point |

### Live Commerce

| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/live/create` | Vendor | Schedule/start live stream |
| GET | `/api/live/active` | Public | List active live streams |
| POST | `/api/live/:id/pin-product` | Vendor | Pin product during stream |
| WS | `/ws/live/:id` | Public | WebSocket for chat + reactions |

### Chat & Communication

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/chat/conversations` | Auth | List conversations |
| POST | `/api/chat/send` | Auth | Send message |
| WS | `/ws/chat` | Auth | Real-time messaging |
| POST | `/api/support/tickets` | Auth | Create support ticket |

### Billing & Subscriptions

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/billing/plans` | Public | List subscription plans |
| POST | `/api/billing/subscribe` | Vendor | Subscribe to plan |
| GET | `/api/billing/invoices` | Vendor | Billing history |
| GET | `/api/wallet/balance` | Buyer | Wallet balance |
| POST | `/api/wallet/load` | Buyer | Load wallet via bKash/Nagad |

### Social Commerce & Affiliates

| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/social/connect/facebook` | Vendor | Connect Facebook Shops |
| POST | `/api/social/sync` | Vendor | Trigger catalog sync |
| POST | `/api/affiliates/register` | Public | Apply as affiliate |
| GET | `/api/affiliates/dashboard` | Affiliate | Clicks, conversions, commissions |

---

## 16. UI Wireframes & Screens

### Screen 1 — Vendor AI Dashboard (Desktop 1440px)

```
┌──────────────────────────────────────────────────────────────────────────┐
│  PRISM Commerce                     [EN | বাংলা]  [💬 3]  [🔔 5]  [⚙️]  │
├──────────────────────────────────────────────────────────────────────────┤
│  [৳ Revenue]  [📦 Orders]  [🔴 Low-Stock]  [⭐ VPS: 87]  [🌧️ Rain]    │
│  [📊 Profit: ৳18,500]  [🎯 Plan: Growth]  [🔴 LIVE NOW]               │
├────────────────────────┬─────────────────────────────────────────────────┤
│  Product List (35%)    │  Selected Product (65%)                         │
│                        │                                                 │
│  🔍 Search + AI 🤖    │  Recharts: 30d history + 30d GBR forecast      │
│                        │  (dashed + confidence band + festival markers)  │
│  [Product A]           │  Weather overlay: 🌧️ monsoon                   │
│   Stock: 12  ✅ 92%    │                                                 │
│   🗓 Eid in 14 days   │  Feature Importance: "Eid: 43% | Weather: 12%" │
│                        │  Data Quality: ████████░░ 80%                   │
│  [Product B]           │                                                 │
│   Stock: 3 🚨 15%     │  ┌─ What-If Planner ──────────────────────┐    │
│                        │  │ Days to Eid: [━━━━●━━] 14              │    │
│  ── AI Sahayak ──      │  │ Monsoon: [ON] / OFF                    │    │
│  "আপনার কোন পণ্যে    │  │ → Scenario: 45 units (+8)              │    │
│   ডিসকাউন্ট দেওয়া    │  └────────────────────────────────────────┘    │
│   উচিত?"              │                                                 │
├────────────────────────┤  ┌─ Live Commerce ────────────────────────┐    │
│ 🔴 GO LIVE NOW        │  │ Next scheduled: Tomorrow 3PM           │    │
│ [Start Stream]         │  │ Last stream: 245 viewers, ৳8,400 sold │    │
│                        │  └────────────────────────────────────────┘    │
├────────────────────────┴─────────────────────────────────────────────────┤
│  [💬 3 unread chats]  [📊 Analytics]  [🔗 Facebook Sync ✅]            │
│  [Coupon Optimizer]  [Category Velocity ↑23%]  [Weather Impact 🌧️]     │
└──────────────────────────────────────────────────────────────────────────┘
```

### Screen 2 — Buyer Homepage (Mobile 375px)

```
┌──────────────────────────────┐
│  PRISM 🛒  [🔍] [🤖] [💬]  │ ← AI search + chat
├──────────────────────────────┤
│  🔴 LIVE NOW                 │ ← Live streams carousel
│  [Vendor A streaming...]     │
│  [Vendor B streaming...]     │
├──────────────────────────────┤
│  🤖 AI সহায়ক                │ ← GenAI assistant
│  "ঈদের জন্য কী কিনবেন?"    │
│  [Ask PRISM Sahayak...]     │
├──────────────────────────────┤
│  🔥 Trending Now             │
│  [Product] [Product] [→]     │
├──────────────────────────────┤
│  🗓 Eid Collection            │ ← Festival-curated
│  [Product] [Product] [→]     │
├──────────────────────────────┤
│  💰 Deals of the Day         │
│  [Product] [Product] [→]     │
├──────────────────────────────┤
│  🏠  🔍  🔴  💬  👤        │ ← Bottom nav
│  Home Search Live Chat Me    │
└──────────────────────────────┘
```

### Screen 3 — Live Commerce Stream View (Mobile)

```
┌──────────────────────────────┐
│  [← Back]     🔴 LIVE  245  │ ← Viewer count
│                              │
│  ┌──────────────────────┐   │
│  │                       │   │
│  │   VENDOR VIDEO FEED   │   │
│  │                       │   │
│  │                       │   │
│  └──────────────────────┘   │
│                              │
│  ┌─ Pinned Product ────────┐│
│  │[Img] Red Saree  ৳1,800  ││ ← Tap to buy
│  │      ⭐4.5  [Add to Cart]││
│  └──────────────────────────┘│
│                              │
│  💬 Live Chat                │
│  Rahim: "দাম কমানো যাবে?"   │
│  Fatima: "🔥🔥🔥"           │
│  [Type a message...]  [Send]│
│  ❤️ 😍 🔥  [Share]          │
└──────────────────────────────┘
```

---

## 17. Security Architecture

### 17.1 Defense-in-Depth Layers

| Layer | Mechanism | Detail |
|---|---|---|
| **L1 — Network** | Cloudflare WAF + DDoS protection | Edge filtering before traffic hits origin |
| **L2 — Gateway** | Kong / Nginx rate limiting | Per-IP and per-user rate limits. API key validation. |
| **L3 — Auth** | Auth.js + JWT (RS256) | Access token (15min) + Refresh token (7 days). Social login. MFA optional (TOTP). |
| **L4 — Authorization** | NestJS RBAC Guards | Role-based access control. 7 roles with permission matrix. |
| **L5 — Data Isolation** | PostgreSQL RLS | Row-level security policies per vendor. Vendor A cannot read Vendor B's data. |
| **L6 — Payment** | Server-side verification | All payment callbacks verified server-side. No client-side trust. Idempotency keys on all payment operations. |
| **L7 — Encryption** | TLS 1.3, AES-256 | All traffic encrypted in transit. Sensitive data (API keys, tokens) encrypted at rest. |
| **L8 — Audit** | Immutable audit logs | All write operations logged with actor, action, timestamp, IP. |
| **L9 — GenAI Safety** | Content filtering + hallucination guard | LLM outputs filtered for harmful content. Product recommendations verified against real DB records. |

### 17.2 OWASP Top 10 Coverage

| Vulnerability | Mitigation |
|---|---|
| Injection (SQL/NoSQL) | Prisma parameterized queries. No raw SQL in user-facing paths. |
| Broken Auth | JWT rotation, refresh token revocation, bcrypt password hashing (cost=12). |
| Sensitive Data Exposure | AES-256 for stored secrets. No PII in logs. GDPR-ready data deletion. |
| XSS | React auto-escapes. CSP headers. DOMPurify for user-generated content. |
| CSRF | SameSite cookies. CSRF tokens on state-changing POST requests. |
| Insecure Deserialization | JSON schema validation (class-validator in NestJS). |
| Security Misconfiguration | Docker security defaults. No default credentials. Environment-specific configs. |
| Rate Limiting | Per-endpoint rate limits via Kong. BullMQ for queue-based throttling. |

### 17.3 Payment Security

- **PCI DSS Level 4** (via gateway delegation to bKash/Nagad/SSLCommerz)
- **No card data stored** — all payment processing delegated to certified gateways
- **Webhook signature verification** for all payment callbacks
- **Idempotency keys** prevent duplicate charges
- **Server-side amount verification** — client never determines payment amount

---

## 18. Performance & Observability

### 18.1 Performance Targets

| Metric | Target |
|---|---|
| API P95 Latency | <200ms (standard), <80ms (GBR forecast) |
| Page Load (LCP) | <2.5s (mobile, 3G) |
| TTFB | <400ms |
| GBR Inference | <80ms (ONNX in-process) |
| GenAI Response | <3s (Ollama local), <5s (OpenAI fallback) |
| Live Stream Latency | <500ms (WebRTC) |
| Chat Message Delivery | <100ms (Socket.io) |
| Search (Meilisearch) | <50ms |
| Database Query P95 | <100ms |
| Concurrent Users Target | 10,000+ |

### 18.2 Optimization Strategy

- **Redis caching** for all read-heavy paths: forecasts (24h), weather (6h), category velocity (1h), search results (30min)
- **ISR (Incremental Static Regeneration)** for product pages — regenerated every 60s
- **React Server Components** — minimize client-side JS bundle
- **Image optimization** — Next.js `<Image>` with WebP, lazy loading, Cloudflare CDN
- **Database indexes** — B-tree on common filters, GIN on JSONB, IVFFlat on pgvector embeddings
- **Connection pooling** — PgBouncer for PostgreSQL connection management
- **BullMQ async processing** — all non-critical paths offloaded to background workers

### 18.3 Observability Stack

```
┌─────────────────────────────────────────────────────────────────┐
│                    OBSERVABILITY STACK                           │
│                                                                 │
│  Metrics:    NestJS → Prometheus → Grafana dashboards           │
│  Logging:    Winston → Loki → Grafana log explorer              │
│  Tracing:    OpenTelemetry → Jaeger (optional, Phase 6)         │
│  Errors:     Sentry → Slack alerts                              │
│  Uptime:     UptimeRobot / Better Uptime                        │
│  Analytics:  PostHog (self-hosted) → user behavior funnels      │
│                                                                 │
│  Dashboards:                                                    │
│  • System Health: CPU, memory, disk, network                    │
│  • API Performance: latency P50/P95/P99 per endpoint            │
│  • Business: GMV, orders/min, active users, vendor signups      │
│  • AI: forecast accuracy, GenAI usage, model latency            │
│  • Live Commerce: active streams, viewers, conversion rate       │
│                                                                 │
│  Alerting:                                                      │
│  • API P95 > 500ms → Slack + PagerDuty                          │
│  • Error rate > 1% → Slack                                      │
│  • Database CPU > 80% → Auto-scale alert                        │
│  • Payment webhook failure → Immediate alert                     │
└─────────────────────────────────────────────────────────────────┘
```

---

## 19. Development Roadmap — 12-Month Startup Plan

### Phase 1: Foundation Hardening (Months 1–2)

> Goal: Replace all free-tier dependencies with production-grade infrastructure.

| Week | Task | Detail |
|---|---|---|
| 1-2 | Database migration | PostgreSQL 16 + pgvector (Neon or self-hosted). Prisma schema migration. |
| 1-2 | Auth overhaul | Auth.js (NextAuth) replacing Supabase Auth. Social login (Google, Facebook). |
| 3-4 | Redis deployment | Redis 7 (managed). BullMQ event bus setup. Session management. |
| 3-4 | Docker containerization | Dockerize NestJS, PostgreSQL, Redis, Meilisearch. Docker Compose for local dev. |
| 5-6 | Next.js 15 upgrade | Turbopack, improved RSC. PWA config update. |
| 5-6 | Meilisearch integration | Full-text product search. Replace SQL LIKE queries. |
| 7-8 | API Gateway setup | Kong or Nginx. Rate limiting, routing, auth pre-processing. |
| 7-8 | Monitoring stack | Grafana + Prometheus + Loki + Sentry. Basic dashboards. |

### Phase 2: Revenue Engine (Months 3–4)

> Goal: Build the monetization infrastructure. Platform generates revenue.

| Week | Task | Detail |
|---|---|---|
| 9-10 | Subscription billing | Plan creation, bKash recurring payment, auto-renewal, dunning. |
| 9-10 | Commission system | Per-sale commission calculation. Vendor wallet deduction. |
| 11-12 | PRISM Wallet | Load (bKash/Nagad), spend, refund, withdrawal. Cashback logic. |
| 11-12 | Production payments | bKash + Nagad + SSLCommerz LIVE APIs. Server-side verification. |
| 13-14 | Vendor disbursement | Weekly auto-payout engine. Commission deduction. Reports. |
| 13-14 | Promoted listings | Vendor-sponsored product boosting in search results. |
| 15-16 | Vendor KYC | NID + trade license upload. Admin approval workflow. |

### Phase 3: GenAI & Communication (Months 5–7)

> Goal: Deploy the AI assistant and communication infrastructure.

| Week | Task | Detail |
|---|---|---|
| 17-18 | Ollama deployment | Docker container with Llama 3.2 or Mistral 7B. GPU/CPU selection. |
| 19-20 | RAG pipeline | pgvector embeddings. Product vectorization via BullMQ. Semantic search API. |
| 21-22 | PRISM Sahayak MVP | Vendor assistant (stock queries, discount suggestions). Buyer assistant (product discovery). |
| 23-24 | AI product descriptions | Bangla → SEO-optimized EN+BN descriptions. |
| 25-26 | Buyer-seller chat | Socket.io real-time messaging. Product card embedding. Read receipts. |
| 27-28 | Notification center | Unified inbox. Support ticket system. AI auto-response drafts. |

### Phase 4: Live & Social Commerce (Months 8–9)

> Goal: Launch live streaming and social commerce features.

| Week | Task | Detail |
|---|---|---|
| 29-30 | LiveKit deployment | Self-hosted WebRTC SFU. Docker container. Room management. |
| 31-32 | Live commerce UI | Vendor "Go Live" flow. Product pinning. Buyer stream view. Chat overlay. |
| 33-34 | Shoppable video | In-stream product cards. Add-to-cart from stream. Post-stream analytics. |
| 35-36 | Facebook Shops sync | Commerce API integration. Nightly catalog sync. Order import. |
| 37-38 | Referral/affiliate system | Referral codes, UTM tracking, commission tracking, affiliate dashboard. |

### Phase 5: Logistics & Analytics (Months 10–11)

> Goal: Connect delivery partners and build advanced analytics.

| Week | Task | Detail |
|---|---|---|
| 39-40 | 3PL integration | Pathao + Paperfly + RedX APIs. Order assignment. Tracking. |
| 41-42 | Auto-routing engine | Zone-based assignment. Cost optimization. SLA tracking. |
| 43-44 | COD reconciliation | COD tracking, collection verification, vendor payout adjustment. |
| 43-44 | BNPL integration | Partner API (ShopUp Pay / iPay). Installment checkout flow. |
| 45-46 | Advanced analytics | Profit dashboard, RFM segmentation, ABC analysis, AI weekly digest. |
| 47-48 | React Native MVP | Mobile app targeting Play Store. Core features: browse, buy, chat, track. |

### Phase 6: Polish, Scale & Launch (Month 12)

> Goal: Security audit, performance optimization, and market launch.

| Week | Task | Detail |
|---|---|---|
| 49-50 | Security audit | OWASP ZAP automated scan. Manual penetration testing. |
| 50 | Load testing | k6: simulate 10,000 concurrent users. Identify and fix bottlenecks. |
| 51 | WCAG 2.2 AA audit | axe-core scan + manual screen reader testing (NVDA). |
| 51 | Documentation | API docs, vendor onboarding guide, admin manual. |
| 52 | Beta launch | 50 vendors in Dhaka. Feedback collection. Bug fixes. |
| 52 | Investor preparation | Pitch deck, metrics dashboard, financial projections. |

---

## 20. Team & Hiring Plan

### MVP Team (Months 1–6) — 2-3 People

| Role | Responsibility | You? |
|---|---|---|
| **Full-Stack Lead (You)** | Architecture, NestJS backend, Next.js frontend, AI modules, DevOps | ✅ |
| **Frontend Developer** | React components, Tailwind, responsive design, PWA, live commerce UI | Hire |
| **Part-Time Designer** | UI/UX design, brand identity, wireframes | Contract |

### Growth Team (Months 7–12) — 5-7 People

| Role | Responsibility |
|---|---|
| **Backend Engineer** | Payment integrations, 3PL APIs, billing engine |
| **ML/AI Engineer** | GenAI fine-tuning, RAG pipeline optimization, model monitoring |
| **Mobile Developer** | React Native app |
| **Marketing / Growth** | Vendor acquisition, content, social media |
| **Customer Support** | Vendor onboarding, buyer support |

### Post-Launch (Month 12+)

Add: QA Engineer, DevOps Engineer, Finance/Operations, Business Development.

---

## 21. Risk Register & Mitigation

| # | Risk | Probability | Impact | Mitigation |
|---|---|---|---|---|
| R1 | **Vendor acquisition slow** | Medium | High | Free tier removes barrier. Facebook vendor group targeting. Referral program. |
| R2 | **3PL API instability** | Medium | Medium | Multi-partner failover. Manual assignment fallback. Circuit breaker pattern. |
| R3 | **LLM hallucination** | Medium | High | RAG-only responses (grounded in DB). Content filtering. Human review for edge cases. |
| R4 | **Payment gateway downtime** | Low | High | Multi-gateway (bKash + Nagad + SSLCommerz). Retry queue. Manual verification path. |
| R5 | **Infrastructure cost overrun** | Medium | Medium | Start with VPS ($50/mo). Scale only with revenue. Cost alerts. |
| R6 | **Regulatory compliance** | Low | High | Consult BD e-commerce regulations (BTRC, Bangladesh Bank). Legal review at Month 6. |
| R7 | **Data privacy breach** | Low | Critical | RLS, encryption at rest, audit logs, Sentry error monitoring. No PII in logs. |
| R8 | **Competitor replication** | Medium | Medium | Data moat (cross-vendor intelligence + festival IP). First-mover advantage. Community building. |
| R9 | **Team burnout (solo)** | High | High | Phased roadmap. MVP first. Hire at Phase 2. Sustainable pace. |
| R10 | **Live commerce low adoption** | Medium | Low | Start with Starter tier (2 free streams). Vendor training. Success stories. |
| R11 | **Bangla LLM quality** | Medium | Medium | Use multilingual models. OpenAI fallback. Collect feedback for fine-tuning. |
| R12 | **COD fraud/returns** | High | Medium | Vendor verification. Buyer rating system. Gradual COD limit increase. |

---

## 22. Novelty & Emergence Argument

### 22.1 Why PRISM is Novel

PRISM Commerce demonstrates **emergent intelligence** — behaviors that arise from the interaction of simple components, creating a system that is greater than the sum of its parts.

```
                    EMERGENCE MAP — PRISM V3

    ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
    │   Per-SKU    │     │   Weather    │     │  Festival    │
    │   Sales      │     │   Signals    │     │  Calendar    │
    │   History    │     │   (daily)    │     │  (auto)      │
    └──────┬──────┘     └──────┬──────┘     └──────┬──────┘
           │                   │                   │
           └──────────┬────────┘───────────────────┘
                      │
              ┌───────▼────────┐
              │   GBR ONNX     │ ────── Per-product prediction
              │   (13 features)│
              └───────┬────────┘
                      │
           ┌──────────┴──────────┐
           │                     │
    ┌──────▼──────┐      ┌──────▼──────┐
    │  Reorder    │      │  Coupon     │
    │  Point      │      │  Optimizer  │
    │  Engine     │      │  Engine     │
    └──────┬──────┘      └──────┬──────┘
           │                    │
           └──────┬─────────────┘
                  │
    ┌─────────────▼───────────┐     ┌────────────────────┐
    │   Feedback Loop         │     │  Cross-Vendor       │
    │   (actual vs predicted) │────►│  Category Velocity  │
    │   Model self-improves   │     │  (emergent signal)  │
    └─────────────────────────┘     └────────┬───────────┘
                                             │
    ┌────────────────────────────────────────▼────────────┐
    │           EMERGENCE: Each vendor's forecasts         │
    │           improve because OTHER vendors use PRISM    │
    │           → Network Intelligence Effect              │
    └─────────────────────────────────────────────────────┘
                              │
    ┌─────────────────────────▼───────────────────────────┐
    │     V3 — GenAI Layer Amplifies Emergence:            │
    │                                                      │
    │  • RAG search indexes ALL products → cross-vendor    │
    │    product discovery improves with more vendors       │
    │  • AI Weekly Digest learns from platform-wide data    │
    │  • Live Commerce trending products = emergent signal  │
    │  • Affiliate network = emergent distribution channel  │
    └──────────────────────────────────────────────────────┘
```

### 22.2 Five Layers of Emergence in PRISM V3

1. **Per-Product Feedback Loop** — The GBR model improves silently for each vendor's products as more data accumulates. No manual intervention needed.

2. **Cross-Vendor Category Velocity** — When multiple vendors in the same category experience demand changes, ALL vendors in that category benefit from the aggregated signal. This is true **network intelligence**.

3. **Environmental Adaptation** — Festival + weather signals create _contextual awareness_ that no single-vendor system can replicate. PRISM "knows" that an approaching Eid + monsoon combination will affect clothing demand differently than Eid + dry season.

4. **GenAI Amplification (NEW V3)** — The RAG pipeline means that every product added to the platform makes the AI assistant smarter for ALL users. More products → better search → more buyers → more orders → better forecasts → more value for vendors.

5. **Social Commerce Network Effect (NEW V3)** — Every affiliate link shared, every Facebook Shops sync, every live stream creates an expanding distribution network that benefits all vendors on the platform.

---

## 23. Testing Strategy

### 23.1 Test Pyramid

```
           ┌─────────────────┐
           │   E2E Tests      │  ← 15 critical user flows (Playwright)
           │   (~30 tests)    │
           ├─────────────────┤
           │  Integration     │  ← API endpoint tests (Supertest)
           │   (~100 tests)   │
           ├─────────────────┤
           │  Unit Tests      │  ← Service/module logic (Jest)
           │   (~300+ tests)  │  ← 80% coverage target
           └─────────────────┘
```

### 23.2 Test Categories

| Category | Tool | Target | Coverage |
|---|---|---|---|
| **Unit** | Jest | NestJS services, AI modules, business logic | 80% |
| **Integration** | Supertest + Jest | All API endpoints with DB | 100% of routes |
| **E2E** | Playwright | 15 critical browser flows | All roles |
| **Load** | k6 | 10,000 concurrent users | Phase 6 |
| **Security** | OWASP ZAP | Automated vulnerability scan | Phase 6 |
| **Accessibility** | axe-core + NVDA | WCAG 2.2 AA | All pages |
| **Visual** | Playwright screenshots | Regression detection | Key pages |

### 23.3 Critical E2E Flows (15)

1. Vendor registration with KYC → admin approval → first product listing
2. Buyer search (full-text + semantic) → product page → add to cart
3. Buyer checkout with bKash → payment callback → order created
4. Buyer checkout with PRISM Wallet → wallet deduction → order created
5. Vendor views GBR forecast → What-If scenario → coupon optimization
6. Low-stock alert triggers → WhatsApp notification sent → vendor restocks
7. Buyer-seller chat → send message → product card shared → order placed
8. Vendor goes LIVE → pins product → buyer buys in-stream → stream ends
9. GenAI Sahayak: vendor asks discount advice in Bangla → gets recommendation
10. GenAI Sahayak: buyer searches "ঈদের জন্য শাড়ি" → gets product cards
11. Vendor subscribes to Growth plan → bKash charge → features unlocked
12. Affiliate shares product → buyer uses referral link → commission tracked
13. Facebook Shops sync → product appears on Facebook → buyer redirected to PRISM
14. 3PL order assignment → tracking status updates → delivery completed
15. Admin views platform analytics → GMV, revenue, vendor health dashboard

### 23.4 CI/CD Pipeline

```
Push to main → GitHub Actions:
  1. Lint (ESLint + Prettier)
  2. Type check (tsc --noEmit)
  3. Unit tests (Jest, 80% threshold)
  4. Integration tests (Supertest with test DB)
  5. Build (Next.js + NestJS)
  6. Docker build + push (if tests pass)
  7. Deploy to staging (ArgoCD)
  8. E2E tests against staging (Playwright)
  9. Deploy to production (manual approval)
```

---

## 24. Accessibility & Inclusivity

### 24.1 WCAG 2.2 AA Compliance

| Criterion | Implementation |
|---|---|
| **Color Contrast** | All text meets 4.5:1 ratio (AA). Key actions meet 3:1 (AAA). |
| **Keyboard Navigation** | All interactive elements focusable. Visible focus indicators. |
| **Screen Readers** | Semantic HTML5. ARIA labels on custom components. Tested with NVDA. |
| **Focus Management** | Proper focus trap in modals. Focus returned after dialog close. |
| **Error Handling** | Form errors linked to fields via `aria-describedby`. Real-time validation. |
| **Text Sizing** | Responsive font sizes (rem-based). Content readable at 200% zoom. |
| **Motion** | `prefers-reduced-motion` respected. Animations can be disabled. |
| **Alt Text** | All images have descriptive alt text. Vendor product image alt auto-generated via AI. |

### 24.2 Bangladesh-Specific Inclusivity

| Feature | Detail |
|---|---|
| **Low-Literacy Onboarding** | Guided wizard with visual cues, progress bar, and tooltips in Bangla. Minimal text. |
| **Icons Over Text** | Primary actions use universally understood icons alongside text labels. |
| **Voice Input (Phase 2)** | Bangla voice commands for GenAI assistant — many BD users prefer voice over typing. |
| **Offline Support (PWA)** | Product catalog cached offline. Orders queued for sync when connectivity returns. |
| **2G/3G Optimization** | Critical JS under 100KB first load. Images lazy-loaded. API responses compressed (gzip). |
| **Data-Saver Mode** | Reduced image quality option. Video thumbnails instead of autoplay. |

---

## 25. Financial Projections

### 25.1 Cost Structure (Monthly)

| Cost Category | Month 1 | Month 6 | Month 12 |
|---|---|---|---|
| **VPS Hosting** | ৳6,000 ($50) | ৳12,000 ($100) | ৳24,000 ($200) |
| **Managed DB (Neon/Supabase)** | ৳1,200 ($10) | ৳3,600 ($30) | ৳6,000 ($50) |
| **Redis (Managed)** | ৳600 ($5) | ৳1,200 ($10) | ৳2,400 ($20) |
| **OpenAI API (Fallback)** | ৳1,200 ($10) | ৳3,600 ($30) | ৳6,000 ($50) |
| **SMS/OTP** | ৳0 | ৳1,200 ($10) | ৳2,400 ($20) |
| **CDN (Cloudflare Pro)** | ৳0 (free) | ৳2,400 ($20) | ৳2,400 ($20) |
| **Domain + SSL** | ৳1,200 ($10) | ৳100 ($1) | ৳100 ($1) |
| **Sentry / Monitoring** | ৳0 (free) | ৳0 (free) | ৳3,000 ($25) |
| **Salaries** | ৳0 (solo) | ৳50,000 | ৳150,000 |
| **Marketing** | ৳0 | ৳20,000 | ৳50,000 |
| **Total Monthly Cost** | **৳10,200** | **৳94,100** | **৳246,300** |
| **Total Monthly (USD)** | **~$86** | **~$791** | **~$2,070** |

### 25.2 Revenue vs. Cost

| Month | Revenue | Cost | Profit/Loss |
|---|---|---|---|
| 1 | ৳0 | ৳10,200 | -৳10,200 |
| 3 | ৳25,000 | ৳25,000 | ৳0 (breakeven on infra) |
| 6 | ৳128,000 | ৳94,100 | +৳33,900 |
| 12 | ৳1,100,000 | ৳246,300 | +৳853,700 |
| 24 | ৳7,550,000 | ৳600,000 | +৳6,950,000 |

### 25.3 Key Financial Metrics

| Metric | Value |
|---|---|
| **Seed Funding Needed** | ৳500,000–1,000,000 (~$4,200–$8,400) |
| **Runway (Self-Funded)** | 6 months at ৳10K–50K/month |
| **Break-Even (Infrastructure)** | Month 3 |
| **Break-Even (Full Cost)** | Month 8–10 |
| **Month 12 MRR** | ৳1,100,000 (~$9,240) |
| **Month 24 MRR** | ৳7,550,000 (~$63,450) |
| **M24 ARR** | ৳90,600,000 (~$761,400) |

---

## 26. Investor Pitch Summary

### One-Liner
> PRISM Commerce is Bangladesh's first AI-native, Bangla-first multi-vendor marketplace with predictive inventory intelligence, live commerce, and a SaaS model 7x cheaper than Shopify.

### The Problem
8M+ SME merchants in Bangladesh lose ৳100B+ annually to stock mismanagement, lack of digital tools, and fragmented operations. Existing platforms (Daraz, Shopify) are either too generic, too expensive, or lack Bangladesh-specific intelligence.

### The Solution
PRISM gives every Bangladeshi merchant an AI-powered co-pilot that predicts demand (weather + festival + cross-vendor signals), speaks Bangla, enables live selling, and costs ৳500/month.

### Market
- $7.5B Bangladesh e-commerce market (growing 10-17% CAGR)
- 80% mobile-first, 67M bKash accounts, 45M WhatsApp users
- Massive underserved SME segment — 300K+ Facebook sellers, 3M+ micro-merchants

### Traction (Target by Month 12)
- 1,000 active vendors
- ৳20M monthly GMV
- ৳1.1M monthly revenue
- 30% paid conversion rate

### Competitive Advantages
1. **Bangla GenAI** — first AI commerce assistant that speaks Bengali
2. **Festival + Weather Intelligence** — unique ML features no competitor has
3. **Cross-Vendor Learning** — network effect in forecasting accuracy
4. **7x Cheaper Than Shopify** — with MORE Bangladesh-specific features
5. **Zero-Commission Free Tier** — removes all vendor onboarding friction

### Ask
৳5,000,000 – ৳10,000,000 (~$42,000 – $84,000) seed round for:
- 12-month development runway
- Hire 3-4 team members
- Vendor acquisition (100 vendors first 3 months)
- Infrastructure scaling

### Team
- **[Your Name]** — Full-stack engineer, AI/ML, system architecture
- Building: Web Technology course → Startup

---

## 27. Glossary

| Term | Definition |
|---|---|
| **GBR** | Gradient Boosting Regressor — ML ensemble model for demand prediction |
| **ONNX** | Open Neural Network Exchange — portable ML model format (<80ms inference) |
| **ROP** | Reorder Point — threshold at which restock alert triggers |
| **VPS** | Vendor Performance Score — 0–100 composite trust metric |
| **EOQ** | Economic Order Quantity — optimal restock quantity formula |
| **NestJS** | Node.js framework for scalable server-side applications |
| **Next.js** | React meta-framework with SSR, ISR, and RSC support |
| **pgvector** | PostgreSQL extension for vector similarity search |
| **RAG** | Retrieval-Augmented Generation — LLM pattern that grounds responses in real data |
| **BullMQ** | Redis-based message queue for Node.js async processing |
| **LiveKit** | Open-source WebRTC SFU (Selective Forwarding Unit) for live video |
| **Socket.io** | Real-time bidirectional event-based communication library |
| **RLS** | Row-Level Security — PostgreSQL feature for tenant data isolation |
| **3PL** | Third-Party Logistics — outsourced delivery partners |
| **COD** | Cash on Delivery — dominant payment method in Bangladesh |
| **BNPL** | Buy Now, Pay Later — installment payment option |
| **MFS** | Mobile Financial Services — bKash, Nagad, Rocket |
| **GMV** | Gross Merchandise Value — total value of goods sold on platform |
| **MRR** | Monthly Recurring Revenue — from SaaS subscriptions |
| **ARR** | Annual Recurring Revenue — MRR × 12 |
| **CLV/LTV** | Customer Lifetime Value — total revenue from a customer over time |
| **CAC** | Customer Acquisition Cost — cost to acquire one new vendor |
| **RFM** | Recency, Frequency, Monetary — customer segmentation model |
| **WCAG** | Web Content Accessibility Guidelines — accessibility standard |
| **KYC** | Know Your Customer — vendor identity verification |
| **SLA** | Service Level Agreement — response/resolution time commitments |
| **CRON** | Scheduled task runner (e.g., hourly, daily, weekly jobs) |
| **ISR** | Incremental Static Regeneration — Next.js page caching strategy |
| **RSC** | React Server Components — server-rendered React components |
| **PWA** | Progressive Web App — installable, offline-capable web app |
| **PRISM Sahayak** | প্রিজম সহায়ক — PRISM's Bangla-native GenAI commerce assistant |
| **SFU** | Selective Forwarding Unit — media server for WebRTC |
| **WAF** | Web Application Firewall — edge security layer |
| **RBAC** | Role-Based Access Control — permission system based on user roles |

---

> **Document Version:** 3.0.0  
> **Last Updated:** April 2026  
> **Author:** Sagar Biswas  
> **Status:** Startup Plan — Ready for Execution  
> **Total AI Modules:** 13 (11 REST + 1 ONNX GBR + GenAI LLM)  
> **Total New Strategic Modules:** 8 (Live Commerce, Social Commerce, Wallet, Logistics, Chat, Analytics, Multi-Tenant, Affiliates)  
> **Total Database Tables:** 40+ (V2 core + 20 new V3 tables)  
> **Total API Endpoints:** 50+ (expanded from V2's ~25)  
> **Revenue Model:** Hybrid SaaS + Commission + Promoted Listings + Wallet + BNPL  

---

*"একটি প্লাটফর্ম যা বাংলাদেশের প্রতিটি ছোট দোকানদারকে AI-এর ক্ষমতা দিয়ে সজ্জিত করে — ভবিষ্যতের বিক্রি আগে থেকেই জানিয়ে দেয়, লাইভ সেলিং এ সাহায্য করে, এবং বাংলায় কথা বলে।"*

*"A platform that empowers every small shopkeeper in Bangladesh with the power of AI — predicting future sales in advance, helping with live selling, and speaking in Bangla."*
