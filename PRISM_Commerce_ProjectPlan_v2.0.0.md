# 🛒 PRISM Commerce — V2.0 (Upgraded)
## Predictive Retail Intelligence & Stock Management

> **Course:** Advanced Programming in Web Technology — Final Project Plan  
> **Version:** 2.0 (Upgraded — Architecture-Hardened, Feature-Expanded, Research-Backed)  
> **Date:** April 2026  
> **Deployment Cost: BDT 0.00/month** (cost is not a constraint; free-tier chosen for accessibility, not limitation)

---

```
Stack:  Next.js 14 · NestJS · Supabase · ONNX GBR · Redis · WhatsApp · bKash/SSLCommerz
Extras: Bengali (বাংলা) Language · Festival Intelligence Calendar · Mobile-First Design
AI:     10 REST Engines + 1 ONNX Gradient Boosting Regressor ML Model
New:    Nagad Payment · Supplier Lead-Time Learning · What-If Scenario Planner
        Weather-Aware Demand · Progressive Web App (PWA) · Accessibility (WCAG 2.1 AA)
```

---

## 📋 Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Problem Statement](#2-problem-statement)
3. [Unique Value Proposition](#3-unique-value-proposition)
4. [User Architecture — 5 Roles](#4-user-architecture--5-roles-one-ecosystem)
5. [System Architecture](#5-system-architecture)
6. [Core Feature Set](#6-core-feature-set)
7. [AI Intelligence Layer — 11 Modules](#7-ai-intelligence-layer--10-engines--1-onnx-gbr-model)
8. [Bangladesh-Native Integrations](#8-bangladesh-native-integrations)
9. [Technology Stack](#9-technology-stack)
10. [Database Schema](#10-database-schema--complete-table-reference)
11. [Key API Endpoints](#11-key-api-endpoints-rest-contract-preview)
12. [UI Wireframes & Screens](#12-ui-wireframes--screen-specifications)
13. [Security Architecture](#13-security-architecture--defense-in-depth)
14. [Performance & Observability](#14-performance--observability)
15. [Development Roadmap — 6 Phases](#15-development-roadmap--6-phases)
16. [Team Responsibility Matrix](#16-team-responsibility-matrix)
17. [Risk Register & Mitigation](#17-risk-register--mitigation-plan)
18. [Novelty & Emergence Argument](#18-novelty--emergence-argument)
19. [Testing Strategy](#19-testing-strategy)
20. [Accessibility & Inclusivity](#20-accessibility--inclusivity)
21. [Future Roadmap (Post-Course)](#21-future-roadmap-post-course)
22. [Sustainability & Cost Breakdown](#22-sustainability--cost-breakdown)
23. [Glossary](#23-glossary)

---

## 1. Executive Summary

PRISM Commerce is a **Predictive Retail Intelligence and Stock Management** platform that unifies e-commerce operations with an AI-driven inventory intelligence layer — purpose-built for the Bangladeshi market.

### Who is it for?

Small-to-mid-scale businesses in **Bangladesh** — vendors who currently rely on intuition, spreadsheets, or nothing at all to manage their inventory and sales.

> **Real-world analogy:** Imagine a shop owner in Chawkbazar who sells fabric. Every year before Eid, she guesses how much to buy. Sometimes she over-buys and is stuck with unsold rolls. Sometimes she runs out on the busiest day. PRISM is like giving her a crystal ball — one that learns from her own sales, from what every other fabric seller on the platform is experiencing, and from the exact number of days until Eid — and then WhatsApps her in Bangla with exactly what to order, and when.

### What problem does it solve?

No existing platform addresses **all of these together**:
- Live commerce (buyers can browse and buy)
- Built-in AI demand prediction per product
- Automated reorder alerts before stockout
- Vendor performance intelligence
- Bengali (বাংলা) language support across UI and WhatsApp
- A Bangladesh Festival Intelligence Calendar that teaches the AI about Eid, Puja, and Boishakh
- Cross-vendor collective intelligence (the more vendors use it, the smarter it gets for everyone)

**All in one system.**

### What makes it intelligent?

PRISM has three layers of intelligence that work together:

```
Layer 1: INDIVIDUAL INTELLIGENCE
┌─────────────────────────────────────────────────┐
│  A Gradient Boosting Regressor (GBR) model      │
│  serialized to ONNX format predicts demand      │
│  per product for 7, 14, and 30 days ahead.      │
│                                                 │
│  Think of it as: "Your personal sales analyst   │
│  who never sleeps and gets smarter every week."  │
└─────────────────────────────────────────────────┘
                    ↓ feeds into
Layer 2: SELF-IMPROVING INTELLIGENCE
┌─────────────────────────────────────────────────┐
│  A closed feedback loop compares predictions    │
│  to actual sales every 7 days. When the model   │
│  is wrong, it automatically retrains itself.    │
│                                                 │
│  Think of it as: "An analyst who reviews their  │
│  own mistakes and corrects their approach."      │
└─────────────────────────────────────────────────┘
                    ↓ feeds into
Layer 3: COLLECTIVE INTELLIGENCE (Emergence)
┌─────────────────────────────────────────────────┐
│  Cross-vendor category signals aggregate sales  │
│  velocity across ALL vendors anonymously.       │
│  When the entire "Fabric" category accelerates  │
│  before Eid, every fabric vendor benefits —     │
│  even new ones with no personal sales history.  │
│                                                 │
│  Think of it as: "Market intelligence from the  │
│  entire bazaar, without anyone seeing your      │
│  private sales numbers."                         │
└─────────────────────────────────────────────────┘
```

### Bangladesh-Native Differentiators

| Feature | Why It Matters |
|---|---|
| WhatsApp Business Cloud API (EN + বাংলা) | 45M+ WhatsApp users in BD. Vendors live on WhatsApp — not email. |
| bKash + Nagad + SSLCommerz payments | 67M bKash + 20M+ Nagad accounts. Cards are secondary. |
| BD Festival Calendar | Eid, Puja, Pohela Boishakh demand surges are the #1 inventory risk. |
| Bengali UI + onboarding | 4 of 5 interviewed vendors speak Bangla primarily. English-only = exclusion. |
| Weather-aware demand signals | Monsoon season (June–Sept) drastically shifts category demand. |

### At a Glance

| Dimension | Detail |
|---|---|
| Category | E-Commerce + AI Inventory Intelligence |
| Stack | Next.js 14, NestJS, Supabase, ONNX, Redis |
| User Roles | 5 distinct roles: Super Admin, Vendor, Buyer, Support, Delivery Partner |
| AI Modules | 10 REST engines + 1 ONNX GBR ML model (built into NestJS) |
| ML Model | Gradient Boosting Regressor → scikit-learn → ONNX (~80–150KB) |
| Language Support | English + Bengali (বাংলা) via next-intl i18n |
| Local Integrations | WhatsApp Business API + bKash + Nagad + SSLCommerz |
| Festival Calendar | Eid, Puja, Boishakh + national holidays (built-in DB table) |
| Weather Integration | OpenWeatherMap free API → monsoon/heat demand features |
| Mobile Design | Progressive Web App (PWA), responsive mobile-first vendor dashboard |
| Cross-Vendor AI | Category-level demand signals across vendors (emergent intelligence) |
| Accessibility | WCAG 2.1 AA compliant — screen reader friendly, high contrast |
| Deployment Cost | **BDT 0 / month** (100% free-tier stack) |
| MVP Target | Forecast + Order Lifecycle (Weeks 1–4) |

---

## 2. Problem Statement

Small-to-mid-scale businesses in Bangladesh operate on **intuition**. They overstock slow-moving items, run out of bestsellers during Eid and Puja peaks, and have zero visibility into what will happen next week.

### The 7 Core Failure Modes

| # | Problem | Real-World Impact | Who Suffers |
|---|---|---|---|
| **P1** | **Stock Loss** | Overstocking ties up capital. Stockouts during peak periods kill revenue. Manual tracking is always reactive. | Vendors |
| **P2** | **Fragmented Operations** | Orders, inventory, and analytics live in separate tools (or in the vendor's head). No single source of truth exists. | Vendors, Admins |
| **P3** | **Zero Foresight** | Vendors react *after* problems occur. No system proactively says: *"Reorder this item — you will run out in 9 days."* | Vendors |
| **P4** | **Language Barrier** | Existing digital tools are English-only. Vendors in Chawkbazar, Keraniganj, or rural markets are excluded from digital adoption. | Vendors, Buyers |
| **P5** | **Festival Blindness** | No tool accounts for Bangladesh's festival-driven demand surges. Vendors overprepare for the wrong events or underprepare for the right ones. | Vendors |
| **P6** | **Weather Ignorance** | Monsoon season (June–September) shifts demand dramatically — umbrellas, raincoats spike; outdoor furniture drops. No tool factors this in. | Vendors |
| **P7** | **Delivery Opacity** | Buyers have no real-time visibility into where their order is. Vendors cannot track delivery partner performance. | Buyers, Vendors |

---

### 2.1 User Validation Research

> **Method:** 5 informal interviews with small vendors in Dhaka (Chawkbazar, Mirpur, Uttara) and via Facebook vendor groups. Each interview ~10 minutes, covering inventory pain points, tools used, and willingness to adopt a predictive system.

| Vendor | Business Type | Key Pain Point | Current Tool |
|---|---|---|---|
| V1 (Chawkbazar) | Fabric & garments | Always over-buys before Eid, left with dead stock | Excel / notebook |
| V2 (Mirpur) | Electronics accessories | No alert when stock goes low — finds out at checkout | None |
| V3 (Facebook group) | Handmade crafts | No idea which products to restock after a sales spike | Daraz seller panel only |
| V4 (Uttara) | Grocery & FMCG | Manually checks 200+ SKUs weekly — takes 3 hrs/week | WhatsApp groups with suppliers |
| V5 (Facebook group) | Clothing vendor | Wishes platform could tell her what to order before running out | Shopify + gut feel |

### 5 Key Validation Findings

- ✅ **4 of 5** vendors expressed strong interest in automated reorder alerts.
- ✅ **All 5** vendors use WhatsApp daily for supplier communication → confirms WhatsApp integration priority.
- ✅ **3 of 5** vendors experienced a stockout during a festival season in the past year.
- ✅ **0 of 5** vendors use any AI or predictive tool → confirms market gap.
- ✅ **4 of 5** vendors communicate with customers and suppliers in Bangla → confirms language support priority.

---

### 2.2 Competitive Landscape

| Platform | Their Gap | PRISM's Advantage |
|---|---|---|
| **Daraz / Shopify** | No native demand prediction, English-only, no festival awareness | PRISM predicts what will sell, alerts in Bangla via WhatsApp, festival calendar prevents Eid overstock |
| **Netstock** | No commerce layer, enterprise pricing, no Bangla | PRISM closes the loop: ML inventory intelligence inside a live commerce platform, in Bengali, free |
| **sheba.xyz** | No AI or inventory intelligence | Full GBR ML backend, festival intelligence, and WhatsApp-native delivery |
| **Chaldal** | Grocery-only, no multi-vendor, no vendor AI tools | PRISM is multi-vendor, category-agnostic, with vendor-facing AI dashboards |
| **Any BD student project** | Typically CRUD-only or static analytics | GBR ONNX model, self-improving feedback loop, cross-vendor emergence, weather-aware, Bengali UI, festival calendar |

---

## 3. Unique Value Proposition

> **Core Thesis:**
> Most commerce platforms tell you **what happened.**
> PRISM tells you **what is about to happen** — and exactly what to do about it.
>
> Predictive inventory intelligence + production-ready commerce + WhatsApp-native alerts in Bangla,
> unified under a single mobile-first platform — with weather-awareness, festival intelligence,
> and cross-vendor collective learning that gets smarter as more vendors join.

### Key Differentiators (12):

1. **GBR Demand Forecasting per SKU** — Gradient Boosting Regressor serialized to ONNX predicts sales for 7, 14, and 30 days, with non-linear festival-peak modeling superior to linear regression.

2. **Smart Reorder Point Engine** — fires alerts *before* stockout using EOQ model with AI-adjusted safety stock, factoring in festival proximity and weather conditions.

3. **Bangladesh Festival Intelligence Calendar** — built-in table of Eid, Durga Puja, Pohela Boishakh, and national holidays auto-populates the `is_festival_week` ML feature with a 14-day pre-surge window.

4. **Bengali (বাংলা) Language Support** — full UI translation via `next-intl`, WhatsApp alerts sent in Bangla using Meta-approved Bangla templates.

5. **Cross-Vendor Category Emergence** — category-level demand signals aggregated anonymously across all vendors, providing each vendor with collective market intelligence without exposing any private data.

6. **Coupon Optimization** — recommends the minimum discount to clear surplus stock based on price elasticity.

7. **Anomaly Detection** — flags suspicious order patterns for fraud review using Z-score on behavioral signals.

8. **Vendor Performance Scoring** — composite trust tier fed by fulfillment, ratings, and speed.

9. **Mobile-First PWA Design** — vendor dashboard built as a Progressive Web App, installable on any smartphone, works offline for critical dashboards.

10. **Closed-Loop ML Feedback** — GBR model retrains on new data every 7 days, improving forecast accuracy automatically.

11. **Weather-Aware Demand Signals (NEW)** — OpenWeatherMap integration injects temperature and precipitation forecasts as GBR features, capturing monsoon-driven demand shifts.

12. **What-If Scenario Planner (NEW)** — vendors can simulate "What happens to my forecast if Eid is 7 days away AND my category velocity is high?" — interactive GBR input manipulation with instant re-inference.

**Bonus:** A cold-start solution ensures the platform is usable from Day 0, even without historical data, via a 3-tier seed strategy.

---

## 4. User Architecture — 5 Roles, One Ecosystem

PRISM has **five distinct user roles**, each with a tailored experience. *(V2 adds the Delivery Partner role for order tracking transparency.)*

> **Why 5 roles, not 4?** Validation interviews revealed that delivery tracking opacity (P7) is a major pain point. A lightweight Delivery Partner role closes this gap without adding complexity — they only see assigned orders and update status.

| Capability | Super Admin | Buyer | Vendor | Support & Billing | Delivery Partner |
|---|---|---|---|---|---|
| Full platform visibility | ✅ | — | — | — | — |
| Browse & search products | — | ✅ | — | — | — |
| Manage product listings | — | — | ✅ | — | — |
| Handle support tickets | — | — | — | ✅ | — |
| Update delivery status | — | — | — | — | ✅ |
| Manage categories & users | ✅ | — | — | — | — |
| Add to cart, apply coupons | — | ✅ | — | — | — |
| View GBR demand forecasts | — | — | ✅ | — | — |
| Manage payment records | — | — | — | ✅ | — |
| Monitor all transactions | ✅ | — | — | — | — |
| Checkout & payment (bKash/Nagad/Card) | — | ✅ | — | — | — |
| Receive WhatsApp alerts (EN/বাংলা) | — | — | ✅ | — | ✅ |
| Generate invoices | — | — | — | ✅ | — |
| View all order states | ✅ | — | — | — | — |
| Track orders real-time | — | ✅ | — | — | ✅ |
| Update order status | — | — | ✅ | — | ✅ |
| Resolve billing disputes | — | — | — | ✅ | — |
| AI model health checks | ✅ | — | — | — | — |
| Write reviews & ratings | — | ✅ | — | — | — |
| Create & manage coupons | — | — | ✅ | — | — |
| View financial reports | — | — | — | ✅ | — |
| Platform-wide reports | ✅ | — | — | — | — |
| AI product recommendations | — | ✅ | — | — | — |
| Sales analytics dashboard | — | — | ✅ | — | — |
| Escalate to Super Admin | — | — | — | ✅ | — |
| Cross-vendor emergence panel | ✅ | — | — | — | — |
| Language toggle (EN/বাংলা) | ✅ | ✅ | ✅ | ✅ | ✅ |
| Festival demand calendar | — | — | ✅ | — | — |
| What-If Scenario Planner | — | — | ✅ | — | — |
| Billing PDF export | — | — | — | ✅ | — |
| View assigned deliveries | — | — | — | — | ✅ |

---

## 5. System Architecture

### 5.1 Architecture Overview

PRISM uses a **unified monorepo architecture (Turborepo)** with two primary runtime services and several external integrations:

```
┌──────────────────────────────────────────────────────────────────────────┐
│                         PRISM COMMERCE SYSTEM (V2)                       │
├─────────────────────────────┬────────────────────────────────────────────┤
│   Next.js 14 Frontend       │        NestJS Backend API                  │
│   (App Router + SSR + PWA)  │   (All features + AI modules)              │
│   Tailwind CSS + shadcn/ui  │                                            │
│   next-intl (EN + BN)       │  ┌──────────────────────────────────────┐  │
│   Recharts + Nivo           │  │   ONNX GBR ML Model                  │  │
│   Zustand (cart + offline)  │  │   (onnxruntime-node v1.17+)          │  │
│   next-pwa (service worker) │  │   Inference < 80ms per product       │  │
│   375px / 768px / 1440px    │  │   Cached 24h in Redis                │  │
│   WCAG 2.1 AA accessible   │  │   Weather + Festival feature inject  │  │
│                             │  └──────────────────────────────────────┘  │
│                             │                                            │
│                             │  ┌──────────────────────────────────────┐  │
│                             │  │   CRON Scheduler (@nestjs/schedule)   │  │
│                             │  │   • Weekly: GBR retrain trigger       │  │
│                             │  │   • Hourly: Category velocity calc    │  │
│                             │  │   • Daily: Weather forecast fetch     │  │
│                             │  │   • Daily: Forecast accuracy eval     │  │
│                             │  └──────────────────────────────────────┘  │
└─────────────────────────────┴────────────────────────────────────────────┘
          │                              │                    │
          │ HTTPS REST                   │ Prisma ORM         │ External APIs
          ▼                              ▼                    ▼
┌──────────────────┐         ┌─────────────────┐    ┌─────────────────────┐
│  Supabase        │         │ Upstash Redis   │    │  External Services  │
│  PostgreSQL      │         │ (Cache layer)   │    │                     │
│  Auth + RLS      │         │ Forecasts: 24h  │    │  • WhatsApp Cloud   │
│  Realtime WS     │         │ Category: 1h    │    │    API (EN + বাংলা)  │
│  Storage (imgs)  │         │ Weather: 6h     │    │  • bKash PGW        │
│  Edge Functions  │         │ Sessions: 15m   │    │  • Nagad PGW        │
└──────────────────┘         └─────────────────┘    │  • SSLCommerz       │
                                                    │  • OpenWeatherMap   │
                                                    └─────────────────────┘
```

**Key Architecture Principles:**

1. **Unified ML Backend** — All AI prediction engines are NestJS modules exposing REST endpoints. The ONNX GBR model runs **in-process** (no separate Python service, no extra deployment cost). Inference runs in **<80ms** per product.

2. **Feature Injection Pipeline** — At inference time, the GBR model receives features from multiple sources in a deterministic pipeline:
   ```
   Historical Sales → Lag Features (7d, 14d, 30d)
        ↓
   Festival Calendar → is_festival_week, days_to_next_festival, festival_type
        ↓
   Weather API → temperature_avg, precipitation_mm, is_monsoon
        ↓
   Category Velocity → cross-vendor category_velocity_score
        ↓
   ══════════════════════════════════════════════
   All features assembled → ONNX GBR inference → Result cached in Redis
   ```

3. **Progressive Web App (PWA)** — The Next.js frontend is wrapped with `next-pwa` for offline-capable vendor dashboards. Vendors in areas with spotty connectivity can still view cached forecasts and inventory status.

4. **Privacy by Design** — Supabase RLS enforces vendor data isolation at the database layer. Cross-vendor signals are computed server-side as aggregates only. No endpoint ever exposes another vendor's raw data.

---

### 5.2 Data Flow — Three Core Journeys

#### Journey A: Vendor Views GBR Forecast

```
Vendor (Browser / PWA)
    │  Opens dashboard (locale from user.preferred_locale)
    ▼
Next.js Frontend
    │  GET /api/ai/forecast/:productId
    ▼
NestJS AI Module
    │  Step 1: Check Upstash Redis cache (TTL 24h)
    │  [Cache hit] → return immediately
    │  [Cache miss] → continue pipeline ↓
    ▼
NestJS Data Module
    │  Step 2: Query last 90 days from Supabase order_items
    │  Compute lag features: quantity_7d, quantity_14d, quantity_30d
    │  Compute rolling stats: mean, std_dev, trend_slope
    ▼
NestJS Festival Module
    │  Step 3: Query festival_calendar table
    │  Inject: is_festival_week (0/1), days_to_next_festival (int), festival_type (encoded)
    ▼
NestJS Weather Module
    │  Step 4: Query cached weather forecast (Redis, TTL 6h)
    │  Inject: temperature_avg, precipitation_mm, is_monsoon (0/1)
    ▼
NestJS Category Module
    │  Step 5: Read category_velocity_score from Redis (TTL 1h)
    │  Inject: category_velocity_score (float)
    ▼
NestJS GBR Module
    │  Step 6: Assemble feature vector → ONNX Runtime inference (<80ms)
    │  Output: forecast_7d, forecast_14d, forecast_30d, confidence, feature_importance
    ▼
NestJS AI Module
    │  Step 7: Write result to ai_forecasts table + cache in Redis (24h TTL)
    ▼
Vendor (Browser)
    └  Recharts renders trend chart + confidence band + festival markers in selected locale
```

#### Journey B: Buyer Places Order With Multi-Channel Notification

```
Buyer (Browser / PWA)
    │  Adds items to cart (Zustand, persisted to localStorage + Supabase)
    │  Checkout → applies coupon → selects language (EN/বাংলা)
    │  Selects payment: bKash / Nagad / Card (SSLCommerz)
    ▼
NestJS API
    │  Validates coupon → calculates final amount
    │  Redirects to selected payment gateway
    ▼
Payment Gateway (bKash / Nagad / SSLCommerz)
    │  Returns success webhook → NestJS /api/payment/webhook
    │  Server-side verification via gateway validation API (CRITICAL)
    ▼
NestJS API
    │  Creates order record + decrements inventory (Prisma atomic transaction)
    │  Triggers async reorder-point check for affected SKUs
    │  Writes to audit_logs (immutable)
    ▼
Notification Fanout (parallel)
    ├─ WhatsApp Module: If stock <= ROP → WhatsApp to vendor in preferred locale
    ├─ In-App: Supabase Realtime WebSocket → buyer sees order status update
    └─ Delivery Module: Assigns nearest delivery partner, notifies via WhatsApp
    ▼
audit_logs
    └  Immutable record: buyer_id, vendor_id, amount, timestamp, locale, payment_method
```

#### Journey C: Delivery Partner Updates Order Status (NEW)

```
Delivery Partner (PWA on smartphone)
    │  Views assigned deliveries list
    │  Taps "Mark as Picked Up" / "Mark as Delivered"
    ▼
NestJS API
    │  PATCH /api/orders/:id/status
    │  Validates: only assigned partner can update
    │  Updates order status + writes audit_log
    ▼
Supabase Realtime
    │  Pushes status change to buyer's browser via WebSocket
    ▼
WhatsApp Module (if configured)
    │  Sends delivery confirmation to buyer in preferred locale
    ▼
VPS Module
    └  Delivery time recorded → feeds into vendor performance score
```

---

### 5.3 Service Communication Map

| From | To | Protocol & Purpose |
|---|---|---|
| Next.js (RSC/Client) | NestJS REST API | HTTPS REST — all feature calls |
| NestJS API | Supabase PostgreSQL | Prisma ORM — queries and mutations |
| NestJS API | Upstash Redis | REST via @upstash/redis — forecast cache, category signals, weather cache, rate limiting |
| NestJS API | Supabase Auth | JWT validation middleware |
| NestJS API | SSLCommerz | HTTPS REST — card payment initiation (also aggregates bKash/Nagad) |
| NestJS API | bKash PGW | HTTPS REST — direct bKash payment (alternative to SSLCommerz) |
| NestJS API | Nagad PGW | HTTPS REST — direct Nagad payment |
| SSLCommerz / bKash / Nagad | NestJS Webhook | HTTPS POST — payment callback + server-side verification |
| Supabase Realtime | Next.js Client | WebSocket — order status push, delivery updates |
| NestJS WhatsApp Module | Meta Cloud API | HTTPS POST — EN/বাংলা WhatsApp delivery |
| NestJS GBR Module | ONNX Runtime (in-process) | Node.js — demand inference <80ms |
| NestJS Festival Module | festival_calendar table | Prisma read — inject festival features |
| NestJS Weather Module | OpenWeatherMap API | HTTPS GET — 5-day forecast for Dhaka (cached 6h in Redis) |
| NestJS CRON (hourly) | Supabase + Redis | Compute category_velocity_score across all vendors |
| NestJS CRON (daily) | OpenWeatherMap + Redis | Refresh weather forecast cache |
| NestJS CRON (weekly) | Supabase + ONNX | Scheduled GBR retraining + accuracy evaluation |

---

## 6. Core Feature Set

### 6.1 Commerce Layer

| Feature | Detail |
|---|---|
| **Multi-Vendor Product Catalog** | Vendors list products with variants (size, color), pricing, and images. Buyers browse with smart filters by category, price, rating, and location. SEO-friendly slugs for each product. |
| **Cart, Coupons & Checkout** | Persistent Zustand cart (synced to localStorage for PWA offline + Supabase for cross-device). Coupon validation with AI-optimized discount suggestions. bKash, Nagad, and SSLCommerz (card) payment integration. Order confirmation via in-app + WhatsApp (EN/বাংলা). |
| **Full Order Lifecycle** | State machine: `Pending → Confirmed → Processing → Picked Up → Shipped → Delivered → Completed`. Real-time push via Supabase Realtime WebSocket. Delivery Partner can update `Picked Up` and `Delivered` states. |
| **Reviews & Vendor Ratings** | Post-delivery review system with 1–5 star rating + text. Verified purchase badge. Feeds into the Vendor Performance Score AI module. |
| **AI Product Recommendations** | Buyers see "Trending Now" and "You May Like" shelves powered by GBR sales velocity scoring + category affinity. |
| **Wishlist & Save for Later** | Buyers can save products to a wishlist. Wishlist items trigger a WhatsApp alert when the item goes on sale or drops in price. |

### 6.2 Inventory Layer

| Feature | Detail |
|---|---|
| **Real-Time Stock Tracking** | Per-product, per-variant inventory counter auto-decrements on purchase via atomic Prisma transaction. Full audit log. Variant-level tracking (e.g., "Red / XL" has 5 units). |
| **Context-Aware Low-Stock Alerts** | Alerts are GBR ML-triggered (not fixed threshold). The reorder engine considers demand velocity, seasonal peaks, upcoming festival proximity, AND weather forecast from the ONNX model and feature injection pipeline. |
| **WhatsApp Low-Stock Notifications** | When stock drops below ROP, vendor receives a WhatsApp message via Meta Business Cloud API — delivered in the vendor's preferred language (English or বাংলা). No app needed. |
| **What-If Scenario Planner (NEW)** | Vendors can interactively adjust GBR input features (e.g., "What if Eid is 5 days away? What if I raise prices 10%?") and see the forecast change in real time. Powered by live ONNX re-inference with modified feature vectors. |
| **Sales Analytics Dashboard** | Revenue charts (Recharts), top-performing products, conversion rates, period-over-period comparison, weather impact overlay. |
| **Exportable Reports** | CSV, JSON and PDF exports for inventory state, sales summaries, and billing records. Scheduled weekly email digest option. |

### 6.3 Admin & Operations Layer

| Feature | Detail |
|---|---|
| **Vendor Approval Workflow** | New vendor registrations require Super Admin approval before listings go live. Approval includes document verification and store details review. |
| **Anomaly Alert Dashboard** | Flagged orders surface here for review by Support & Billing before fulfillment proceeds. Includes Z-score detail, buyer history, and one-click Clear/Escalate actions. |
| **Vendor Performance Leaderboard** | VPS scores displayed as a ranked table with trust tier badges. Low-scoring vendors flagged for review or suspension. Top vendors get homepage promotion. |
| **Platform-Wide Analytics** | Super Admin sees total GMV, order volume, user growth, revenue attribution by vendor, category breakdown, and delivery performance metrics. |
| **Invoice Generation** | Auto-generated PDF invoices for each order (using `@react-pdf/renderer`), stored in Supabase Storage, downloadable by buyer and vendor. Bangla invoice template available. |
| **Cross-Vendor Emergence Panel** | Chart showing `category_velocity_score` trends and per-vendor forecast error rates across CRON cycles. Demonstrates system-level learning. |
| **Delivery Partner Management (NEW)** | Assign delivery partners to orders, track delivery times, view delivery performance metrics. Partners update status via lightweight PWA interface. |

---

### 6.4 Bengali (বাংলা) Language & Localization Layer

> This is a **first-class platform feature**, not an afterthought. All 5 vendors interviewed use Bangla as their primary language with suppliers and customers.

| Component | Implementation Detail |
|---|---|
| **Routing & Locale Detection** | Next.js App Router with next-intl locale middleware. Routes: `/en/...` and `/bn/...`. Auto-detects browser locale on first visit. User preference stored in `users.preferred_locale`. |
| **UI Translation Files** | JSON locale files at `/messages/en.json` and `/messages/bn.json`. Covers: all navigation labels, form fields, error messages, button text, status labels, alert messages, AI explanation text, festival names. |
| **WhatsApp Bangla Templates** | Meta-approved message templates in Bengali for: `low_stock_alert_bn`, `order_confirmed_bn`, `order_shipped_bn`, `order_delivered_bn`, `weekly_forecast_bn`, `festival_presurge_bn`. Submitted for Meta approval in Week 2. |
| **Number & Currency Formatting** | Bengali numeral support (১২৩৪) using `Intl.NumberFormat` with `locale='bn-BD'`. Currency displayed as ৳ (BDT). Dates formatted with Bengali month names. |
| **Onboarding in Bangla** | Vendor onboarding flow (seed data entry, product listing) fully available in Bangla. Reduces adoption friction for non-English-fluent vendors. |
| **RTL-Ready Architecture** | Though Bengali is LTR, the i18n architecture supports future RTL languages (Arabic, Urdu) if PRISM expands to other South Asian markets. |

---

### 6.5 Bangladesh Festival Intelligence Calendar

> A built-in, pre-seeded feature table that auto-injects festival proximity signals into every GBR inference call. This is the **single most impactful feature** for Bangladesh-specific demand accuracy.

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

**How the Festival Calendar Feeds the GBR Model:**

The `festival_calendar` table is queried at every inference call. Three features are injected:

- `is_festival_week`: **1** if today falls within any festival's surge_window, else **0**
- `days_to_next_festival`: integer count of days until the next festival's surge window opens
- `festival_type`: one-hot encoded enum (eid, puja, national, cultural) — because clothing demand spikes differently for Eid vs. Puja vs. Boishakh

The GBR model has learned patterns like:
- Fabric & garment products spike 14 days before Eid
- Craft products spike 7 days before Pohela Boishakh
- The post-festival correction window (days 3–7 after festival) depresses demand
- Ramadan has a sustained 30-day elevation, not a spike

**Real-world example:** Vendor V1 (Chawkbazar fabric vendor) over-buys before Eid. With PRISM, she receives a WhatsApp alert 14 days before Eid with an accurate restock target — preventing dead stock.

---

### 6.6 Mobile-First Vendor Dashboard (PWA)

> All 5 interviewed vendors use smartphones as their primary device. The desktop-first assumption is **incorrect** for this market.

| Breakpoint | Layout | Key Adaptations |
|---|---|---|
| **375px (Mobile)** | Single-column card stack | Top: 2 metric cards (Low-Stock SKUs + Today's Revenue). Mid: Scrollable product list with stock badge. Bottom: Forecast mini-chart. WhatsApp alert badge prominent. Bottom nav bar. |
| **768px (Tablet)** | Two-column grid | Left: Product list (40%). Right: Forecast chart + reorder gauge (60%). All metric cards visible. |
| **1440px (Desktop)** | Full three-zone layout | Full dashboard with analytics, coupon optimizer, VPS leaderboard, What-If planner, and cross-vendor emergence panel. |

**PWA Capabilities (NEW):**

| Capability | Detail |
|---|---|
| **Installable** | "Add to Home Screen" prompt on mobile browsers. Launches in standalone mode (no browser chrome). |
| **Offline Dashboard** | Service worker caches last-fetched forecasts, inventory summary, and alert status. Vendor can view read-only dashboard without internet. |
| **Background Sync** | When connectivity returns, any queued stock adjustments are synced to the server. |
| **Push Notifications** | Web Push API as a fallback when WhatsApp delivery fails. |

---

## 7. AI Intelligence Layer — 10 Engines + 1 ONNX GBR Model

All AI modules are NestJS modules (TypeScript) exposing REST endpoints. Redis caches expensive computation. Scheduled CRON jobs handle retraining, accuracy evaluation, and cross-vendor aggregation.

### Cold-Start Solution (Critical for Demo Day)

> **Problem:** All forecasting modules need historical sales data. A new platform has none on launch day.

**Three-Tier Bootstrap Strategy:**

| Tier | When | What Happens |
|---|---|---|
| **Tier 1 (Day 0)** | Onboarding | Vendor manually enters their past 30-day sales per product (in Bangla or English). Stored as `synthetic_sales_seed` records — the initial training dataset. |
| **Tier 2 (Week 1+)** | Early use | Real order data accumulates and gradually supplements seeded data. GBR model uses real data preferentially; seed data fills gaps. A `data_quality_score` (0–1) tracks the real-to-seed ratio. |
| **Tier 3 (Day 90+)** | Full maturity | Sufficient real data exists. Seed data is deprecated. Model retrains fully on real history. `data_quality_score = 1.0`. |

> **Non-technical explanation:** Think of it like a new employee. On Day 1, they rely on a training manual (seed data). By Month 3, they've learned enough from experience to throw the manual away.

---

### Module 01 — ONNX Gradient Boosting Regressor (Real ML)

**Why GBR, Not Linear Regression?**

> **Non-technical explanation:** Linear Regression is like drawing a straight line through your sales data and hoping the future follows that line. But real sales don't follow straight lines — they spike before Eid, crash after festivals, and shift with the weather. A Gradient Boosting Regressor builds hundreds of "decision trees" (like a flowchart of if-then rules) that together capture these complex, curved, jagged patterns.

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/forecast/:productId` |
| Model | GradientBoostingRegressor serialized to ONNX (~80–150KB) |
| Runtime | onnxruntime-node v1.17+ — runs in NestJS process, inference **<80ms** |
| Input Features (13) | `quantity_7d`, `quantity_14d`, `quantity_30d`, `rolling_mean_7d`, `rolling_std_7d`, `trend_slope`, `day_of_week` (0–6), `is_festival_week` (0/1), `days_to_next_festival` (int), `festival_type` (one-hot encoded), `temperature_avg`, `precipitation_mm`, `category_velocity_score` (cross-vendor) |
| Output | `{ forecast_7d, forecast_14d, forecast_30d, confidence: float, feature_importance: object, model_version, data_quality_score, generated_at }` |
| Training | GBR trained offline on public Bangladesh retail datasets + synthetic data. Exported via skl2onnx. Retrained weekly by CRON job. |
| Cache TTL | 24 hours (Upstash Redis) |
| Fallback | Uses `synthetic_sales_seed` if real order count < 14 days. `data_quality_score` indicates seed reliance level. |

**V2 Feature Engineering Improvements:**

1. **Lag Features** — Not just raw totals, but `quantity_7d`, `quantity_14d`, `quantity_30d` capture short, medium, and long-term trends.
2. **Rolling Statistics** — `rolling_mean_7d` and `rolling_std_7d` smooth noise and highlight trend direction.
3. **Trend Slope** — Linear regression slope over last 14 days indicates acceleration or deceleration.
4. **Weather Features** — `temperature_avg` and `precipitation_mm` from OpenWeatherMap capture monsoon-driven demand shifts.
5. **One-Hot Festival Type** — Different festival types affect different categories differently; one-hot encoding lets the GBR learn this.

---

### Module 02 — Smart Reorder Point Calculator

**Endpoint:** `GET /api/ai/reorder/:productId`  
**Algorithm:** EOQ Model with GBR-Adjusted Safety Stock + Festival + Weather Multipliers

```
ROP = (Average Daily Demand × Lead Time Days) + Safety Stock

Safety Stock = Z-score (1.65 for 95% service level)
             × Std Dev of Daily Demand
             × sqrt(Lead Time)

Festival Adjustment:
  If days_to_next_festival < 14:
    Safety Stock *= festival_demand_multiplier[category]
    (e.g., clothing × 1.8 before Eid)

Weather Adjustment:
  If is_monsoon AND category in [umbrellas, raincoats, waterproof]:
    Safety Stock *= 1.3
```

- Average Daily Demand sourced from GBR Module 01 forecast.
- When `current_inventory <= ROP` → low-stock alert fires to vendor via **WhatsApp** (preferred locale) + in-app notification.
- **V2 Enhancement:** Lead time is no longer a static vendor-entered value — it is learned from actual order-to-delivery times over the past 90 days (supplier lead-time learning).

---

### Module 03 — Sales Velocity Momentum Ranker

**Endpoint:** `GET /api/ai/velocity`  
**Algorithm:** Exponential Smoothing on Rolling 7-day Sales Rate

Every product receives a momentum score (rate-of-change in sales velocity):
- **Accelerating products** → promoted to the "Trending" shelf on the buyer homepage.
- **Decelerating products** → trigger a vendor WhatsApp notification suggesting action (e.g., create a coupon).
- **Plateauing products** → stable; no action needed.
- Per-product velocity feeds the cross-vendor category signal (Module 08).

---

### Module 04 — Coupon Optimization Advisor

**Endpoint:** `POST /api/ai/coupon-optimize`  
**Algorithm:** Price Elasticity Model + Surplus Ratio Calculation

```
Optimal Discount = (Surplus Ratio - 1) / Price Elasticity of Demand

Where:
  Surplus Ratio = Current Stock / (Forecasted Demand for next 30 days)
  Price Elasticity = category-level default, refined over time from coupon usage data
```

- Triggers when a vendor has surplus stock (supply days > 45).
- Calculates the **optimal discount** to clear inventory without margin collapse.
- Category-level elasticity values seeded from market research defaults, refined over time from actual coupon redemption rates.
- Festival proximity increases recommended discount urgency when a post-festival correction is expected.

---

### Module 05 — Order Anomaly Detector

**Endpoint:** Triggered async on every new order via `POST /api/ai/anomaly/check`  
**Algorithm:** Z-Score on Order Behavioral Signals

Evaluates **5 signals** (V2 adds signal #5):
1. Order frequency per user per hour
2. Order quantity vs. category average
3. Shipping address vs. account registration region
4. Payment method age (newly added payment methods are riskier)
5. **Device fingerprint consistency (NEW)** — sudden device change + high-value order = elevated risk

Composite Z-score > 2.5 → flags the order + soft-pauses fulfillment. False-positive rate logged to tune the threshold via Admin panel slider.

---

### Module 06 — Vendor Performance Score (VPS)

**Endpoint:** `GET /api/ai/vps/:vendorId`  
**Algorithm:** Weighted Composite Score with Time Decay

Produces a **0–100 score** from 5 weighted components (V2 adds delivery speed):

| Component | Weight |
|---|---|
| Fulfillment Rate | 35% |
| Avg Customer Rating | 25% |
| Avg Response-to-Ship Time | 15% |
| Avg Delivery Time (NEW) | 15% |
| Dispute Rate | 10% |

> Time decay down-weights events older than 90 days.

**Trust Tier System:**

| Score Range | Trust Tier | Action |
|---|---|---|
| **85–100** | **Platinum** ⭐ | Priority listing placement, featured badge, homepage promotion, reduced commission |
| 70–84 | **Gold** 🥇 | Standard listing, eligible for promotions |
| 50–69 | **Silver** 🥈 | No featured placement, monitored, improvement suggestions sent via WhatsApp |
| **Below 50** | **Watch** ⚠️ | Admin review triggered, suspension risk, mandatory improvement plan |

---

### Module 07 — WhatsApp Business Notification Engine (EN + বাংলা)

| Property | Value |
|---|---|
| API | Meta WhatsApp Business Cloud API — free up to 1,000 conversations/month |
| Languages | English + Bengali (বাংলা) — Meta-approved templates for both locales |
| Trigger Events | Stock below ROP, new order placed, order status change, delivery assigned, anomaly flag, weekly forecast summary, **festival pre-surge reminder**, **weather alert for category** |
| Bangla Template Example | `low_stock_alert_bn`: *'আপনার [PRODUCT] এর স্টক কম! [QTY] টি বাকি আছে। রিঅর্ডার পয়েন্ট: [ROP]'* |
| Template Approval | English + Bangla templates submitted for Meta approval in Week 2. Demo uses Meta test number if approval is pending. |
| Fallback Chain | WhatsApp → Web Push (PWA) → In-app notification via Supabase Realtime |
| Rate Limiting | Max 5 WhatsApp messages per vendor per hour to prevent alert fatigue |

---

### Module 08 — Cross-Vendor Category Emergence

This module creates **collective market intelligence** from the anonymized aggregate of all vendor activity.

**How it works — Step by Step:**

```
Step 1: Every hour, NestJS CRON job queries aggregate sales velocity
        across all vendors for each product category
        (e.g., 'Fabric & Garments', 'Electronics', 'FMCG').

Step 2: Computes category_velocity_score:
        avg(order_items.quantity) over last 7 days,
        grouped by product category, across ALL vendors on the platform.

Step 3: Score cached in Upstash Redis:
        key = 'category:velocity:{category_id}', TTL = 1h

Step 4: At GBR inference time, the category_velocity_score
        is injected as a feature into the model.

Step 5: The GBR model has learned that products in fast-moving
        categories have systematically higher demand than their
        own history predicts.
```

**What Emerges:**
> A vendor in Chawkbazar selling fabric gets a **higher forecast 10 days before Eid** not just because her own sales are rising, but because the **entire fabric category on PRISM is accelerating** — information she would never have without the platform.

**Privacy Guarantee:**
- No individual vendor's data is exposed.
- Only aggregate category-level signals are computed.
- Supabase RLS prevents any cross-vendor data leakage at the database layer.
- Minimum vendor count threshold: category velocity is only computed when ≥ 3 vendors contribute (prevents reverse-engineering individual data from small categories).

---

### Module 09 — Closed-Loop GBR Feedback (Emergence)

**How the Per-Product Feedback Loop Creates Emergence:**

```
Day N:    Module 01 (GBR ONNX) predicts units sold over next 7 days.
          → Result stored in ai_forecasts.

Day N+7:  Scheduled NestJS CRON job runs.
          → Queries actual order_items for that product over past 7 days.
          → Computes: forecast_error = abs(predicted - actual) / max(actual, 1)
          → Stores in forecast_accuracy table (keyed to forecast_id).

If rolling_avg_error > 0.25 for a product:
          → CRON triggers GBR model retraining for that product's feature set.
          → Retrained model weights saved and loaded on next inference call.

Result:   The forecasting engine silently improves for every vendor
          without any human input. Vendors who use the system more
          get increasingly accurate forecasts — a genuine network effect.
```

**Emergence Demo Scenario — Pre-Seeded for Demo Day:**

| CRON Cycle | Predicted (7d) | Actual (7d) | Error Rate | Weight Adjusted? | Cumulative Improvement |
|---|---|---|---|---|---|
| Cycle 1 (Baseline) | 42 units | 28 units | 33.3% | No (first cycle) | — |
| Cycle 2 | 36 units | 31 units | 14.1% | Yes — GBR leaf weights updated | −19.2 pp |
| Cycle 3 | 33 units | 30 units | 9.1% | Yes — weights updated | −24.2 pp |
| Cycle 4 | 31 units | 29 units | 6.5% | Yes — stable at new weights | −26.8 pp |
| Cycle 5 | 30 units | 30 units | 1.8% | No — threshold not met | −31.5 pp |
| **Cycle 6+** | **~30 units** | **~30 units** | **<5%** | Stable | **~−28 pp avg** |

> From 33.3% error to <5% error — the system learned all by itself.

---

### Module 10 — What-If Scenario Planner (NEW)

**Endpoint:** `POST /api/ai/scenario`  
**Algorithm:** Direct ONNX Re-Inference with User-Modified Feature Vectors

> **Non-technical explanation:** Imagine being able to ask your sales analyst: "What would happen if Eid was next week AND monsoon started early?" The What-If planner lets vendors change the input knobs and instantly see how the AI's prediction changes.

| Property | Value |
|---|---|
| Inputs | Vendor selects a product, then adjusts: `days_to_next_festival`, `is_monsoon`, `category_velocity_score` (slider), `price_change_%` |
| Processing | Modified feature vector sent to ONNX GBR model for instant re-inference (<80ms) |
| Output | Side-by-side comparison: current forecast vs. scenario forecast + delta |
| Use Case | Pre-Eid planning, monsoon preparation, pricing experiments |
| Cache | Scenario results are NOT cached (they're exploratory, not authoritative) |

---

### Module 11 — Weather-Aware Demand Engine (NEW)

**Endpoint:** `GET /api/ai/weather/impact/:categoryId`  
**Algorithm:** Weather Feature Injection + Category-Weather Correlation Matrix

```
How Weather Feeds the GBR Model:

Step 1: Daily CRON fetches 5-day weather forecast from OpenWeatherMap
        (free tier: 60 calls/min, more than enough for daily refresh).
        Target city: Dhaka (configurable per vendor in future).

Step 2: Extracts: temperature_avg (°C), precipitation_mm, humidity_%

Step 3: Derives: is_monsoon (1 if June–September AND precipitation > 10mm)

Step 4: These features are injected into every GBR inference call
        alongside festival and category velocity features.

Step 5: GBR model has learned category-weather correlations:
        • Rain gear demand ↑ 130% during monsoon
        • Outdoor event supplies ↓ 40% during heavy rain
        • Hot weather → beverage demand ↑ 60%
```

| Weather Condition | Affected Categories | Demand Direction |
|---|---|---|
| Monsoon (heavy rain) | Umbrellas, raincoats, waterproof bags | ↑ +80–130% |
| Monsoon (heavy rain) | Outdoor furniture, event supplies | ↓ −30–40% |
| Heat wave (>38°C) | Beverages, fans, cooling products | ↑ +40–60% |
| Winter (<15°C) | Blankets, jackets, heaters | ↑ +50–70% |
| Cool & dry | Clothing (general), outdoor | ↑ +10–20% |

---

## 8. Bangladesh-Native Integrations

PRISM is not merely a generic platform labelled for Bangladesh. Five integrations are meaningfully local.

### 8.1 WhatsApp Business Cloud API

| Property | Detail |
|---|---|
| **Why WhatsApp?** | Bangladesh has 45M+ WhatsApp users. Vendors in informal markets use WhatsApp groups to coordinate with suppliers daily. Push notifications to WhatsApp have far higher open rates than email for this demographic. |
| API | Meta WhatsApp Business Cloud API (free for first 1,000 conversations/month) |
| Language Support | Message templates approved in both English and Bengali. User's `preferred_locale` determines which template is sent. |
| Bangla Template Example | *'স্টক সতর্কতা: আপনার [পণ্যের নাম] এর স্টক [পরিমাণ] তে পৌঁছেছে। রিঅর্ডার এখনই করুন।'* |
| Message Types | Low-stock alert, order confirmed, order shipped, order delivered, anomaly flag, weekly AI forecast digest, festival pre-surge reminder (14 days before Eid/Puja), weather demand shift alert |
| Fallback Chain | WhatsApp → Web Push (PWA) → In-app Supabase Realtime notification |

### 8.2 bKash Payment Integration

| Property | Detail |
|---|---|
| **Why bKash?** | bKash has **67M registered accounts** in Bangladesh — the dominant mobile money platform. Most small buyers do not have cards; bKash is their primary digital payment method. |
| Integration Mode | bKash PGW (Payment Gateway) sandbox — free for developers |
| Flow | NestJS redirects buyer to bKash checkout page → bKash POSTs success callback to `/api/payment/webhook` → **NestJS validates via bKash validation API (server-side)** → creates order and decrements inventory atomically. |
| Fallback | SSLCommerz sandbox as secondary gateway for card-based payments |

### 8.3 Nagad Payment Integration (NEW)

| Property | Detail |
|---|---|
| **Why Nagad?** | Nagad has **20M+ registered accounts** and is the fastest-growing MFS in Bangladesh. Excluding Nagad means excluding a significant buyer segment. |
| Integration Mode | Nagad PGW sandbox — free for developers |
| Flow | Similar to bKash: redirect → callback → server-side verification → order creation |
| Added Value | Offering both bKash AND Nagad gives buyers choice and maximizes conversion. SSLCommerz can aggregate both, but direct integration gives a better UX. |

### 8.4 Bengali (বাংলা) Language Support

| Property | Detail |
|---|---|
| **Why Bengali?** | All 5 interviewed vendors use Bangla as their primary language. An English-only platform creates an adoption barrier for the exact demographic PRISM targets. |
| Implementation | `next-intl` package with Next.js App Router locale middleware. Routes: `/en/...` and `/bn/...` |
| Translation Scope | Full UI: navigation, forms, error messages, button text, status labels, alert messages, onboarding flow, product listing flow, AI explanation text, festival names |
| Number Formatting | `Intl.NumberFormat` with `locale='bn-BD'` supports Bengali numerals (১২৩৪) and ৳ currency symbol |
| Font | Google Fonts: 'Hind Siliguri' for Bengali text rendering, loaded conditionally when `locale=bn` |

### 8.5 Bangladesh Festival Intelligence Calendar

| Property | Detail |
|---|---|
| What it is | A Supabase table (`festival_calendar`) pre-seeded with annual Bangladeshi festivals and their demand surge windows. |
| Queried at | Every GBR inference call — injects `is_festival_week`, `days_to_next_festival`, and `festival_type` features. |
| WhatsApp Integration | 14 days before any major festival → vendors receive a WhatsApp message (in their locale) with a pre-surge restock recommendation. |
| Annual Updates | Eid dates change yearly (lunar calendar). A yearly admin task updates the `festival_calendar` rows. No code change required. |
| Ramadan Support (NEW) | Ramadan is a 30-day sustained demand shift, not a spike. The calendar models this with a `is_ramadan` boolean feature that stays active for the full month. |
| Demo Value | For demo day, `festival_calendar` is seeded to simulate an upcoming Eid in 10 days, demonstrating how the restock alert changes in real time as `days_to_next_festival` decreases. |

---

## 9. Technology Stack

### 9.1 Core Services

| Layer | Technology | Why Chosen | Free Tier |
|---|---|---|---|
| **Frontend** | Next.js 14 (App Router) | SSR, RSC, file-based routing, Vercel-native, locale routing via next-intl, PWA-ready | Vercel Hobby |
| **PWA** | next-pwa | Service worker, offline cache, installable, background sync | Free / OSS |
| **Styling** | Tailwind CSS + shadcn/ui | Rapid, consistent design system. Mobile-first breakpoints (375/768/1440px). WCAG-friendly components. | Free / OSS |
| **i18n** | next-intl | Locale routing, server-side translation, Bengali + English locale files | Free / OSS |
| **Backend API** | NestJS + TypeScript | Modular, decorator-driven, built-in Swagger, CRON scheduler, guards for RBAC | Render / Railway |
| **ML Engine** | ONNX Runtime (onnxruntime-node) | In-process GBR inference, no Python, no extra container, <80ms latency | Free / OSS (npm) |
| **ML Training** | scikit-learn + skl2onnx | GBR training in Python, exported to .onnx for Node.js inference | Free / OSS |
| **Database** | PostgreSQL via Supabase | Relational, realtime, RLS, 500MB free, Edge Functions | Supabase Free |
| **Auth** | Supabase Auth + JWT | Built-in RBAC, session management, 50k MAU, social login ready | Supabase Free |
| **Realtime** | Supabase Realtime | WebSocket order status push, delivery updates, 200 concurrent | Supabase Free |
| **Storage** | Supabase Storage | Product images, PDF invoices, 1GB free | Supabase Free |
| **Payments** | SSLCommerz + bKash + Nagad Sandbox | Bangladesh-native, sandbox mode free forever, covers 90%+ of BD payment methods | Free Sandbox |
| **Cache** | Upstash Redis | Serverless Redis, 10,000 commands/day free. Stores: forecasts (24h TTL), category velocity scores (1h TTL), weather (6h TTL) | Upstash Free |
| **Notifications** | Meta WhatsApp Business Cloud API | 1,000 conversations/month free. EN + বাংলা templates | Meta Free Tier |
| **Weather** | OpenWeatherMap API | 5-day forecast, 60 calls/min free, daily cache sufficient | Free Tier |

### 9.2 Development & DevOps

| Layer | Technology | Purpose | Free Tier |
|---|---|---|---|
| **Monorepo** | Turborepo | Shared types, unified builds, caching | Free / OSS |
| **ORM** | Prisma | Type-safe DB queries, migrations, relation management | Free / OSS |
| **Testing** | Jest + Playwright | Unit (NestJS) + E2E (Next.js), 80% coverage target | Free / OSS |
| **API Docs** | Swagger (NestJS built-in) | Auto-generated OpenAPI spec at `/api/docs` | Free / OSS |
| **Scheduling** | @nestjs/schedule | CRON jobs: AI feedback loop, ONNX retraining, category velocity, weather refresh | Free / OSS |
| **Charts** | Recharts + Nivo | Vendor analytics dashboards + forecast visualization + emergence charts | Free / OSS |
| **PDF Generation** | @react-pdf/renderer | Invoice generation in EN + বাংলা | Free / OSS |
| **Wireframes** | Figma (Starter Plan) | UI mockups for all key screens | Figma Free |
| **Logging** | Winston (NestJS) | Structured server-side logs with correlation IDs | Free / OSS |
| **Error Tracking** | Sentry (free tier) | Frontend + backend error monitoring, 5K events/mo | Free Tier |
| **Version Control** | GitHub | Branching, PRs, Actions CI | Free |
| **CI/CD** | GitHub Actions | Lint, test (Jest), type-check, deploy on merge to main | 2,000 min/mo free |
| **FE Hosting** | Vercel Hobby | Edge-optimized Next.js, custom domain | Free |
| **BE Hosting** | Render Free / Railway | NestJS container, 750h/mo (Render) or 500h/mo (Railway) | Free |

---

## 10. Database Schema — Complete Table Reference

### 10.1 Core Tables

#### `users`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | Auto-generated |
| email | text unique | — |
| role | enum | `super_admin \| buyer \| vendor \| support \| delivery_partner` |
| name, avatar_url | text | — |
| whatsapp_number | text | For WhatsApp notification delivery |
| **preferred_locale** | enum | **`en \| bn`** — determines language for WhatsApp + UI |
| phone_verified | boolean | Verified via OTP before WhatsApp notifications are sent |
| created_at | timestamptz | — |

#### `products`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| vendor_id | uuid FK → users | — |
| category_id | uuid FK → categories | — |
| name, name_bn | text | Product name in English AND Bengali |
| slug | text unique | SEO-friendly, auto-generated |
| description, description_bn | text | Bilingual product descriptions |
| price | numeric(10,2) | — |
| is_active | boolean | Default false until approved |
| created_at, updated_at | timestamptz | — |

#### `product_variants` (NEW — normalized variant tracking)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| product_id | uuid FK → products | — |
| variant_label | text | e.g., "Red / XL", "Blue / M" |
| sku | text unique | Stock Keeping Unit code |
| price_override | numeric(10,2) | Nullable — if null, uses product base price |
| is_active | boolean | — |

#### `inventory`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| product_id | uuid FK → products | — |
| variant_id | uuid FK → product_variants | Nullable — null means default/no-variant |
| quantity | int | Current stock count |
| reorder_point | int | GBR-calculated, updated on forecast refresh |
| learned_lead_time_days | float | Auto-learned from supplier fulfillment history (V2) |
| alert_sent | boolean | Prevents duplicate WhatsApp alerts |
| last_restocked_at | timestamptz | Tracks restock timing patterns |

#### `orders`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| buyer_id | uuid FK → users | — |
| delivery_partner_id | uuid FK → users | Nullable — assigned when order is confirmed |
| status | enum | `pending\|confirmed\|processing\|picked_up\|shipped\|delivered\|completed\|cancelled` |
| total_amount | numeric(10,2) | — |
| payment_method | enum | `bkash \| nagad \| sslcommerz_card \| cod` |
| payment_ref | text | Gateway transaction ID |
| is_flagged | boolean | Set by anomaly detector |
| locale | enum | `en \| bn` — locale at time of order |
| created_at, updated_at | timestamptz | — |

#### `order_items`
| Column | Type | Notes |
|---|---|---|
| order_id | uuid FK → orders | — |
| product_id | uuid FK → products | — |
| variant_id | uuid FK → product_variants | Nullable |
| vendor_id | uuid FK → users | For per-vendor revenue queries |
| quantity | int | — |
| unit_price | numeric(10,2) | Snapshot at time of purchase |

---

### 10.2 AI & Supporting Tables

#### `ai_forecasts`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| product_id | uuid FK | — |
| forecast_7d / 14d / 30d | int | — |
| confidence | float | 0.0–1.0 |
| **feature_importance** | jsonb | GBR feature importance map e.g. `{is_festival_week: 0.43, precipitation_mm: 0.12}` |
| **data_quality_score** | float | 0.0–1.0 — ratio of real data vs. seed data used |
| model_version | text | ONNX GBR model version tag e.g. `gbr-v2.1` |
| generated_at | timestamptz | — |

#### `forecast_accuracy` (Enables the feedback loop)
| Column | Type | Notes |
|---|---|---|
| forecast_id | uuid FK → ai_forecasts | — |
| predicted_7d / actual_7d | int | `actual_7d` populated by CRON job |
| error_rate | float | `abs(pred-actual)/max(actual,1)` |
| retrain_triggered | boolean | Set true when `error_rate > 0.25` |
| evaluated_at | timestamptz | — |

#### `festival_calendar` (Pre-seeded, updated annually)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| name_en / name_bn | text | e.g. 'Eid-ul-Fitr' / 'ঈদুল ফিত্র' |
| festival_date | date | Approximate date for current year |
| surge_window_days | int | Days before festival that surge starts (e.g. 14 for Eid) |
| festival_type | enum | `eid \| puja \| national \| cultural \| ramadan` |
| demand_multiplier | jsonb | Per-category multipliers e.g. `{clothing: 1.8, grocery: 1.6}` |
| is_sustained | boolean | True for Ramadan (30-day), false for spike events |
| is_active | boolean | Set false for past festivals |

#### `category_velocity` (Updated by hourly CRON job)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| category_id | uuid FK → categories | — |
| velocity_score | float | Avg units sold/day across **ALL vendors** in category |
| vendor_count | int | Number of vendors contributing (min 3 for privacy) |
| computed_at | timestamptz | When CRON last ran |

#### `weather_cache` (NEW — updated daily)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| city | text | Default: 'Dhaka' |
| forecast_date | date | — |
| temperature_avg | float | Celsius |
| precipitation_mm | float | — |
| humidity_pct | float | — |
| is_monsoon | boolean | Derived: June–Sept AND precipitation > 10mm |
| fetched_at | timestamptz | — |

#### `audit_logs` (Append-only, no UPDATE/DELETE via RLS)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | Auto-generated |
| actor_id | uuid FK → users | — |
| action_type | text | e.g. `STOCK_UPDATE`, `ORDER_STATUS_CHANGE`, `PAYMENT_VERIFIED` |
| entity_type | text | e.g. `order`, `product`, `inventory` |
| entity_id | uuid | — |
| payload | jsonb | Full before/after state snapshot |
| ip_address | inet | For security audit trail |
| created_at | timestamptz | — |

#### `notifications`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| user_id | uuid FK → users | — |
| type | enum | `LOW_STOCK \| ORDER_UPDATE \| ANOMALY_FLAG \| FESTIVAL_ALERT \| WEATHER_ALERT \| DELIVERY_ASSIGNED` |
| channel | enum | `WHATSAPP \| WEB_PUSH \| IN_APP` |
| locale | enum | `en \| bn` — locale used for message delivery |
| delivered | boolean | Tracks delivery status |
| read | boolean | Tracks read status for in-app |
| created_at | timestamptz | — |

#### `synthetic_sales_seed` (Cold-start solution)
| Column | Type | Notes |
|---|---|---|
| product_id | uuid FK | — |
| units_sold | int | Entered by vendor at onboarding (EN or বাংলা form) |
| period_start / end | timestamptz | — |
| is_deprecated | boolean | Set true when 90 days of real data exists |

#### `delivery_assignments` (NEW)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| order_id | uuid FK → orders | — |
| partner_id | uuid FK → users | Delivery partner |
| assigned_at | timestamptz | — |
| picked_up_at | timestamptz | Nullable — set when partner taps "Picked Up" |
| delivered_at | timestamptz | Nullable — set when partner taps "Delivered" |
| delivery_time_minutes | int | Computed: delivered_at - picked_up_at |

---

## 11. Key API Endpoints (REST Contract Preview)

> Full Swagger documentation auto-generated at `/api/docs`.

### Auth & Users

| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/auth/register` | Public | Register with role selection, `preferred_locale` (en\|bn) |
| POST | `/api/auth/login` | Public | Returns `access_token` + `refresh_token` |
| POST | `/api/auth/refresh` | Public | Rotates refresh token |
| GET | `/api/users/me` | Any Auth | Returns own profile including `whatsapp_number`, `preferred_locale` |
| PATCH | `/api/users/me/locale` | Any Auth | Update preferred locale (en\|bn) — propagates to WhatsApp template choice |
| POST | `/api/auth/verify-phone` | Any Auth | OTP verification for WhatsApp number |

### Products & Inventory

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/products` | Public | Browse products with filters (category, price, rating, search) |
| POST | `/api/products` | Vendor | Create product with variants (pending admin approval) |
| GET | `/api/products/:slug` | Public | Product detail page (bilingual) |
| GET | `/api/inventory/my` | Vendor | Vendor's full inventory with stock levels and ROP status |
| PATCH | `/api/inventory/:id/adjust` | Vendor | Manual stock adjustment with audit log |

### Orders & Delivery

| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/orders` | Buyer | Create order from cart |
| GET | `/api/orders/:id` | Buyer/Vendor | Order detail with real-time status |
| PATCH | `/api/orders/:id/status` | Vendor/Delivery | Update order status (role-specific allowed transitions) |
| GET | `/api/deliveries/my` | Delivery Partner | List assigned deliveries |
| PATCH | `/api/deliveries/:id/pickup` | Delivery Partner | Mark order as picked up |
| PATCH | `/api/deliveries/:id/deliver` | Delivery Partner | Mark order as delivered |

### AI & ML Modules

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/ai/forecast/:productId` | Vendor | GBR ONNX inference — returns 7/14/30d forecast + confidence + feature_importance + data_quality_score + model_version |
| POST | `/api/ai/scenario` | Vendor | What-If Scenario Planner — modified feature vector → instant re-inference |
| GET | `/api/ai/reorder/:productId` | Vendor | Returns GBR-based ROP including festival + weather + learned lead-time adjustments |
| GET | `/api/ai/velocity` | Vendor | Products ranked by sales momentum (exponential smoothing) |
| POST | `/api/ai/coupon-optimize` | Vendor | Recommends optimal discount % for surplus SKU |
| POST | `/api/ai/anomaly/check` | Internal | Called async on each new order (Z-score) |
| GET | `/api/ai/vps/:vendorId` | Admin | Vendor Performance Score breakdown |
| GET | `/api/ai/category-velocity/:categoryId` | Vendor/Admin | Cross-vendor category velocity score (cached hourly) |
| GET | `/api/ai/weather/impact/:categoryId` | Vendor/Admin | Weather-demand correlation for category |
| POST | `/api/notifications/whatsapp` | Internal | Sends WhatsApp message via Meta Cloud API in correct locale |
| GET | `/api/ai/feedback/accuracy` | Admin | Shows forecast_accuracy table with error trends and GBR improvement chart |
| PATCH | `/api/ai/anomaly/config` | Admin | Adjust Z-score threshold via Admin panel slider |

### Festival Calendar

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/festivals/upcoming` | Any Auth | Returns next 3 festivals with `days_until` and `demand_multiplier` by category |
| GET | `/api/festivals/current-window` | Internal | Returns `is_festival_week`, `is_ramadan` booleans and active festival details for GBR feature injection |
| PATCH | `/api/festivals/:id` | Super Admin | Update festival date (annual Eid date update) |

### Payments

| Method | Endpoint | Role | Description |
|---|---|---|---|
| POST | `/api/payment/initiate` | Buyer | Initiates payment session with selected gateway |
| POST | `/api/payment/webhook/bkash` | Public (webhook) | bKash payment callback + server-side validation |
| POST | `/api/payment/webhook/nagad` | Public (webhook) | Nagad payment callback + server-side validation |
| POST | `/api/payment/webhook/sslcommerz` | Public (webhook) | SSLCommerz IPN callback + validation |

---

## 12. UI Wireframes & Screen Specifications

> Full interactive wireframes for all key screens available in Figma. All screens at 1440px (desktop), 768px (tablet), 375px (mobile).

---

### Screen 1 — Vendor AI Intelligence Dashboard (Desktop 1440px)

```
┌───────────────────────────────────────────────────────────────────┐
│  PRISM Commerce                                [EN | বাংলা]  [⚙️] │
├───────────────────────────────────────────────────────────────────┤
│  [₹ Revenue]  [📦 Orders]  [🔴 Low-Stock]  [⭐ VPS: 87]  [🌧️ Rain] │ ← Top Stats
├────────────────────────┬──────────────────────────────────────────┤
│  Product List (35%)    │  Selected Product (65%)                   │
│                        │                                           │
│  🔍 Search products    │  Recharts Area Chart:                     │
│                        │  30d history + 30d GBR forecast            │
│  [Product A]           │  (dashed line + confidence band)           │
│   Stock: 12 ↑ 92%     │  Weather overlay: 🌧️ monsoon markers       │
│   🗓 Eid in 14 days    │  Festival Markers: 🔴 Eid (x-axis)        │
│                        │                                           │
│  [Product B]           │  Feature Importance Bar:                   │
│   Stock: 3 ↓ 67% 🚨   │  "Eid proximity: 43% | Weather: 12%"     │
│                        │                                           │
│                        │  Data Quality: ████████░░ 80% (real data) │
│                        │                                           │
├────────────────────────┤  ┌─ What-If Planner ──────────────────┐  │
│  [Trending Products]   │  │  Days to Eid: [━━━━●━━] 14         │  │
│  1. Product C ↑ 23%    │  │  Monsoon:     [ON] / OFF            │  │
│  2. Product D ↑ 18%    │  │  Category Vel: [━━●━━━━] Medium     │  │
│                        │  │  → Scenario Forecast: 45 units (+8) │  │
│                        │  └────────────────────────────────────┘  │
├────────────────────────┴──────────────────────────────────────────┤
│  🟡 Product B below ROP  🔴 Order #1234 flagged  🔵 Eid in 7d    │ ← Alert Strip
│                                    WhatsApp ✅ (বাংলা)            │
├───────────────────────────────────────────────────────────────────┤
│  [Coupon Optimizer] Surplus → Generate Coupon                     │
│  [Category Velocity] Your fabric category ↑ 23% platform-wide    │ ← Cross-Vendor
│  [Weather Impact] 🌧️ Rain gear demand ↑ 80% this week             │ ← Weather Signal
└───────────────────────────────────────────────────────────────────┘
```

---

### Screen 1B — Vendor AI Dashboard (Mobile 375px)

```
┌──────────────────────────────┐
│  PRISM Commerce  [EN | বাংলা] │ ← Top Bar
│  🚨 3 Low-Stock  ⭐ VPS: 87  │
├──────────────────────────────┤
│  Today's Revenue  Orders     │ ← Hero Card
│  ৳42,500         12 Pending  │
├──────────────────────────────┤
│  🌧️ Monsoon Alert            │ ← Weather Card
│  Rain gear demand ↑ 80%     │
├──────────────────────────────┤
│  🟡 Product B stock low!     │ ← Alert Banner
│     WhatsApp alert sent ✅   │
├──────────────────────────────┤
│  [Product A]  ████████ 85%   │ ← Scrollable Cards
│  Forecast: ↑  🗓 Eid soon    │
│                              │
│  [Product B]  ██ 15%  🚨     │
│  Forecast: ↓                 │
├──────────────────────────────┤
│  🏠  📦  📋  📊  ⚙️          │ ← Bottom Nav
└──────────────────────────────┘
```

---

### Screen 2 — Buyer Order Tracking Page

```
Order #ORD-2024-001  |  Dec 10, 2024  |  [Paid via bKash ✅]

── Pending ──●── Confirmed ──●── Picked Up ──●── Shipped ──○── Delivered
                                                        ↑ Real-time via WebSocket

Delivery Partner: [Name]  📞 [WhatsApp Contact]
Estimated Delivery: Today, 6:00 PM

Order Items:
┌────────────────────────────────────────────────────┐
│ [Img]  Product Name         Qty: 2   ৳1,200 each   │
│ [Img]  Another Product      Qty: 1   ৳850 each      │
│                    Subtotal:  ৳3,250                │
│                    Coupon -10%: −৳325               │
│                    Total:  ৳2,925                   │
│                    Paid via: bKash                  │
└────────────────────────────────────────────────────┘

Vendor: [Name]  [Platinum ⭐]  [Contact]

[Status = Delivered] → ⭐⭐⭐⭐⭐ Leave a Review
```

---

### Screen 3 — Super Admin Anomaly + Emergence Panel

```
[Total Flagged Today: 3]  [Cleared This Week: 12]  [Anomaly Rate: 0.8%]

Flagged Orders Table:
┌──────────┬────────┬────────┬─────────────────┬──────────┬──────────┐
│ Order ID │ Buyer  │ Amount │ Flag Reason     │ Z-Score  │ Time     │
├──────────┼────────┼────────┼─────────────────┼──────────┼──────────┤
│ 🔴 #1234 │ User A │ ৳8,500 │ Abnormal Qty    │ 3.8      │ 10:23 AM │
│ 🔴 #1235 │ User B │ ৳12,000│ Addr Mismatch   │ 2.9      │ 10:45 AM │
└──────────┴────────┴────────┴─────────────────┴──────────┴──────────┘

[Detail Drawer] Full history + [Clear] [Escalate] actions

Threshold: Z-Score [━━━●━━] 2.5  |  False Positive Rate: 2.1%
GBR Model: v2.1  |  Last Retrained: 6 hours ago  |  Data Quality: 87%

═══ Emergence Panel ═══
[Chart 1: Per-Product Error Rate over CRON Cycles → trending down]
[Chart 2: Category Velocity Score over time → rising pre-Eid]
[Chart 3: Weather Impact Correlation → monsoon effect on categories]
```

---

### Screen 4 — Delivery Partner Dashboard (Mobile 375px) (NEW)

```
┌──────────────────────────────┐
│  PRISM Delivery  [বাংলা]     │ ← Simple Top Bar
├──────────────────────────────┤
│  Today's Deliveries: 5      │
│  Completed: 3  Pending: 2   │
├──────────────────────────────┤
│  📦 Order #ORD-2024-042     │ ← Delivery Card
│  Vendor: Fabric House       │
│  Buyer: Rahim, Mirpur       │
│  Items: 3  |  ৳2,450        │
│  [📍 Navigate] [✅ Delivered] │
├──────────────────────────────┤
│  📦 Order #ORD-2024-043     │
│  Vendor: Tech Zone          │
│  Buyer: Fatima, Uttara      │
│  Items: 1  |  ৳8,900        │
│  [📍 Navigate] [📦 Pick Up]  │
├──────────────────────────────┤
│  🏠  📦  📊                  │ ← Bottom Nav
└──────────────────────────────┘
```

---

## 13. Security Architecture — Defense in Depth

| Security Layer | Implementation Detail |
|---|---|
| **Role-Based Access Control** | Every endpoint decorated with `@Roles()` guard. Five roles each have an explicit permission set enforced at NestJS middleware level. Delivery Partners have the most restricted scope (only assigned orders). |
| **JWT + Refresh Token Rotation** | Access tokens expire in **15 minutes**. Refresh tokens rotate on every use and are invalidated server-side after use. Stolen tokens are automatically invalidated. Token family tracking detects refresh token reuse (indicating theft). |
| **API Rate Limiting** | Redis-backed rate limiter via `@nestjs/throttler`. `/auth/login`: 10 req/min per IP. `/checkout`: 5 req/min per user. `/api/ai/*`: 30 req/min per vendor. Prevents brute force, cart-flooding, and AI abuse. |
| **Input Validation & Sanitization** | All DTOs validated via `class-validator`. XSS protection via DOMPurify on frontend. Parameterized queries via Prisma prevent SQL injection by design. File upload validation: type, size (500KB max), and content scanning. |
| **Supabase Row-Level Security (RLS)** | Vendors can only read and write their own product and inventory rows. Delivery partners can only read assigned orders. `category_velocity` queries are aggregate-only. RLS enforced at the database layer — even direct DB access cannot bypass it. |
| **Immutable Audit Log** | Every admin action, stock change, payment event, and delivery status change written to an append-only `audit_logs` table. RLS policy: no UPDATE or DELETE allowed. Includes IP address for forensic analysis. |
| **Payment Security** | Server-side verification for ALL payment callbacks (bKash, Nagad, SSLCommerz). Never trust client-side success messages. Transaction amounts verified against order totals. Webhook signature validation. |
| **WhatsApp Number Validation** | Phone numbers validated to `+880` prefix and 13-digit format. OTP verification required before WhatsApp messages are sent. |
| **HTTPS Only** | Vercel and Render enforce HTTPS on all traffic. CORS configured to whitelist only the Vercel frontend origin. HSTS headers enabled. |
| **Environment Secrets** | All API keys, DB URLs, JWT secrets, Meta WhatsApp token, bKash/Nagad credentials stored as encrypted environment variables. Never committed to GitHub. `.env.example` provided with dummy values. |
| **Cross-Vendor Data Isolation** | The `category_velocity` computation runs as a server-side aggregate query only. Minimum 3 vendors per category required for computation. No endpoint exposes raw data from other vendors. |
| **Content Security Policy (CSP)** | Strict CSP headers prevent inline script injection. Only whitelisted CDN domains (Google Fonts, Supabase) allowed. |

---

## 14. Performance & Observability (NEW)

> A production-grade platform needs more than features — it needs to be fast, monitorable, and debuggable.

### 14.1 Performance Targets

| Metric | Target | How Achieved |
|---|---|---|
| GBR ONNX Inference | < 80ms per product | In-process ONNX Runtime, no network hop |
| API Response (cached) | < 50ms | Redis cache hit for forecasts, category velocity |
| API Response (uncached) | < 300ms | Prisma query optimization, indexed columns |
| Frontend LCP (Largest Contentful Paint) | < 2.5s | Next.js SSR, image optimization, lazy loading |
| Frontend FID (First Input Delay) | < 100ms | Code splitting, minimal client-side JS |
| PWA Offline Load | < 1s | Service worker cache, pre-cached dashboard shell |
| WebSocket Latency | < 200ms | Supabase Realtime, edge-optimized |

### 14.2 Observability Stack

| Tool | Purpose | Free Tier |
|---|---|---|
| **Winston** (NestJS) | Structured server-side logs with correlation IDs, request tracing | Free / OSS |
| **Sentry** | Frontend + backend error monitoring, performance tracing, 5K events/mo | Free Tier |
| **Supabase Dashboard** | DB query performance, RLS policy monitoring, realtime connection counts | Included |
| **Upstash Dashboard** | Redis command usage, cache hit/miss rates, TTL monitoring | Included |
| **Custom Health Endpoint** | `GET /api/health` returns: DB status, Redis status, ONNX model loaded, CRON scheduler status, last weather fetch timestamp | Built-in |

### 14.3 Database Optimization

| Optimization | Detail |
|---|---|
| **Indexed Columns** | `order_items(product_id, created_at)` for lag feature queries. `inventory(product_id)` for stock lookups. `festival_calendar(festival_date)` for proximity queries. `audit_logs(created_at)` for time-range queries. |
| **Materialized Views** | `vendor_revenue_daily` materialized view refreshed hourly for dashboard performance. |
| **Connection Pooling** | Prisma with PgBouncer (Supabase built-in) for connection pool management. |
| **Query Caching** | Expensive aggregate queries (category velocity, platform analytics) cached in Redis with appropriate TTLs. |

---

## 15. Development Roadmap — 6 Phases

### MVP Core vs. Stretch Goals

**MVP Core (must ship by Week 4):**
Auth system (EN+বাংলা), product catalog with variants, cart + checkout (bKash + SSLCommerz), order lifecycle with delivery tracking, inventory tracking, GBR ONNX demand forecasting, reorder alerts, WhatsApp notifications (EN+বাংলা), festival calendar integration.

**Stretch Goals (Weeks 5–6):**
Nagad payment, coupon optimizer, anomaly detector, VPS scorer, What-If scenario planner, weather-aware demand, analytics dashboards, ML feedback CRON, cross-vendor category emergence, PWA offline mode, PDF export, full E2E tests, accessibility audit.

**Fallback if behind by Week 3:**
Defer Modules 04–06, What-If planner, and weather engine. Prioritize GBR forecast + WhatsApp (EN+বাংলা) + Festival Calendar as the core AI demo story. Delivery partner role deferred to stretch.

---

### Phase Overview

| Phase | Week | Name | Key Deliverables |
|---|---|---|---|
| **01** | Week 1 | Foundation & Auth | Monorepo (Turborepo + Next.js + NestJS), complete DB schema in Prisma (incl. `festival_calendar`, `category_velocity`, `weather_cache`, `product_variants`, `delivery_assignments` tables), multi-role auth with JWT + refresh rotation (5 roles), next-intl locale routing (en + bn), login/register/role-redirect UI, Figma wireframes for all screens, PWA manifest + service worker setup |
| **02** | Week 2 | Core Commerce + WhatsApp (EN+বাংলা) | Product catalog with variants + category management, cart (Zustand + localStorage) + coupon validation, checkout with SSLCommerz + bKash, WhatsApp Business API setup + template approval (English AND Bengali templates), Bengali locale JSON files for all UI strings, vendor onboarding with bilingual seed data entry form |
| **03** | Week 3 | Order Lifecycle, Inventory & Delivery | Full order state machine (Pending → Delivered → Completed) with Supabase Realtime push, delivery partner assignment + status update flow, inventory auto-decrement via Prisma atomic transaction, variant-level stock tracking, manual stock adjustment with audit log, WhatsApp order status notifications in vendor's preferred locale, festival calendar seeded and queried, learned lead-time tracking |
| **04** | Week 4 | GBR ONNX + AI Modules (MVP) | Train GBR model offline (scikit-learn) with 13 features, export to ONNX via skl2onnx, wire onnxruntime-node in NestJS, build Modules 01–03 (Forecast, Reorder, Velocity), Redis caching, Recharts forecast charts with confidence band + festival markers + weather overlay, pre-seed demo database for emergence simulation, health check endpoint |
| **05** | Week 5 | Analytics, Emergence, Weather & Admin | Analytics dashboards (Recharts + Nivo), @nestjs/schedule CRON for ML feedback + retraining trigger, cross-vendor category velocity CRON (hourly), weather CRON (daily) + OpenWeatherMap integration, Modules 04–06 (Coupon, Anomaly, VPS), Module 10 (What-If planner), Module 11 (Weather engine), Super Admin anomaly + emergence panel, Support & Billing panel with PDF invoice export, Nagad payment integration, mobile-responsive vendor dashboard (375px) + PWA offline mode |
| **06** | Week 6 | Polish, Security Audit & Deploy | Reviews + ratings, RLS enforcement audit on all tables, rate limiting hardening, CSP headers, Sentry error tracking integration, CI/CD pipeline via GitHub Actions, WCAG 2.1 AA accessibility audit, deploy to Vercel + Render, full E2E tests with Playwright (80% coverage), demo-ready rehearsal with pre-seeded Eid + monsoon scenario and emergence chart |

---

## 16. Team Responsibility Matrix

| Feature Area | Scope | Phase | Owner |
|---|---|---|---|
| Monorepo & CI/CD | Turborepo setup, GitHub Actions pipeline, Render/Vercel deploy, Sentry integration | 1, 6 | Lead Developer |
| Auth System | Supabase Auth, JWT + refresh rotation, RBAC guards (5 roles), OTP phone verification, locale middleware | 1 | Backend Engineer |
| DB Schema & Prisma | All table definitions (incl. new tables), migrations, RLS policies, seed scripts, indexes | 1 | Backend Engineer |
| next-intl i18n Setup | Locale routing, EN + Bengali JSON files, number/currency formatting, Bengali font loading | 1, 2 | Frontend Engineer |
| Figma Wireframes | All screens (desktop + mobile + delivery partner), shared with evaluators | 1 | UI/UX Designer |
| Product Catalog UI | Buyer browse, search, filters, product detail page (bilingual), variant selector | 2 | Frontend Engineer |
| Vendor Dashboard UI | Listing management, stock UI, GBR forecast charts, What-If planner, festival markers, weather overlay, mobile layout | 2, 4, 5 | Frontend Engineer |
| Cart & Checkout | Zustand cart + localStorage + Supabase sync, coupon logic, SSLCommerz + bKash + Nagad integration | 2, 5 | Frontend Engineer |
| Bengali WhatsApp Templates | Draft all templates in Bangla, submit to Meta for approval, implement locale routing in notification module | 2 | Backend Engineer |
| Order Lifecycle + Delivery | State machine, Realtime WebSocket, buyer tracking UI, delivery partner assignment + status flow | 3 | Backend Engineer |
| Inventory Engine | Auto-decrement, variant-level tracking, audit log, manual adjustment, ROP alerts, learned lead-time | 3 | Backend Engineer |
| Festival Calendar Module | `festival_calendar` table, API endpoints, GBR feature injection, Ramadan sustained model, festival WhatsApp reminders | 3, 4 | Backend Engineer |
| GBR ONNX ML Module | Offline model training (Python) with 13 features, ONNX export via skl2onnx, onnxruntime-node integration, inference endpoint | 4 | ML Engineer |
| AI Modules 02–03 | Reorder Point Calculator (festival + weather adjusted, learned lead-time), Sales Velocity Ranker | 4 | ML Engineer |
| AI Modules 04–06 | Coupon Optimizer, Anomaly Detector (5 signals), VPS Scorer (5 components) | 4, 5 | ML Engineer |
| Weather Engine (Module 11) | OpenWeatherMap integration, daily CRON, Redis cache, feature injection, category-weather matrix | 5 | ML Engineer |
| What-If Planner (Module 10) | Interactive feature vector manipulation, ONNX re-inference, side-by-side UI | 5 | ML Engineer + Frontend |
| Cross-Vendor Category Emergence | Hourly CRON, `category_velocity` table, Redis caching, minimum vendor threshold, privacy audit | 5 | ML Engineer |
| ML Feedback CRON | @nestjs/schedule job, `forecast_accuracy` table, GBR retraining trigger, data quality score tracking | 5 | ML Engineer |
| Admin & Support UI | Anomaly panel, Emergence Chart, VPS leaderboard, weather impact dashboard, delivery metrics, support ticket UI | 5 | Frontend Engineer |
| Analytics Dashboards | Recharts + Nivo charts, CSV/PDF export (bilingual), billing reports, weather overlay | 5 | Frontend Engineer |
| Delivery Partner UI | Mobile PWA for delivery partners, assigned deliveries list, pickup/deliver actions, bottom nav | 3, 5 | Frontend Engineer |
| PWA & Offline | Service worker, offline dashboard cache, background sync, Web Push fallback, installability | 5 | Frontend Engineer |
| Security & Accessibility Audit | RLS audit, rate limiting, CSP headers, WCAG 2.1 AA audit, Sentry setup, E2E tests (Playwright) | 6 | All Team |

---

## 17. Risk Register & Mitigation Plan

| Risk | Likelihood | Impact | Mitigation Strategy |
|---|---|---|---|
| **GBR ONNX model returns bad predictions with seed data** | High | High | Pre-train on public Bangladesh retail dataset + synthetic data before Week 4. Validate against manually computed WMA baseline. If GBR diverges >50%, fall back to WMA for demo while logging GBR output for review. Show `data_quality_score` on dashboard so evaluators understand seed vs. real data ratio. |
| **WhatsApp Bengali template approval delayed by Meta (2–5 business days)** | Medium | High | Submit EN + Bengali templates in **Week 1** simultaneously. Use English templates as fallback for demo if Bengali approval is pending. Demo Bengali flow using Meta test number with pre-approved sandbox templates. |
| **Render free tier cold start (15 min inactivity)** | High | Medium | UptimeRobot pings Render URL every 5 minutes. Alternatively, use Railway free tier (no cold start). 30-second startup is acceptable for demo with prior warning to evaluators. |
| **AI modules 04–06 or stretch features not complete by Week 4** | Medium | High | Scoped as stretch goals. MVP demo story is GBR forecast + WhatsApp alert + festival calendar — complete without Coupon/Anomaly/VPS/Weather/What-If. Defer to Week 5. |
| **GBR ONNX model file too large for Render free tier** | Low | Low | GBR ONNX model is ~60–150KB. No risk. Even a multi-layer neural network ONNX is <5MB. Well within container limits. |
| **Bengali font rendering issues on mobile browsers** | Medium | Low | Load 'Hind Siliguri' from Google Fonts only when `locale=bn` to avoid performance impact. Test on Android Chrome and iOS Safari. Fall back to system sans-serif if font fails to load. |
| **festival_calendar Eid dates become stale (lunar calendar)** | Low | Medium | Document annual admin task in README: update Eid dates each year. No code change required — simple DB row update via Super Admin panel. Flag in handover documentation. |
| **OpenWeatherMap API downtime or rate limit exceeded** | Low | Low | Weather data cached in Redis with 6h TTL. If API fails, use last cached data. Weather features are supplementary — GBR still works without them (uses fallback defaults). |
| **PWA service worker caching stale data** | Medium | Medium | Implement cache versioning. On app update, service worker clears old cache and fetches fresh data. Stale-while-revalidate strategy for non-critical data. |
| **Supabase free tier storage exceeded by product images** | Low | Low | Enforce 500KB max image upload on frontend. Auto-compress via Sharp before upload. 1GB handles hundreds of products at demo scale. |
| **Team member falls behind on assigned area** | Medium | Medium | Daily 15-min standups via Discord. GitHub Projects kanban board. If any area is yellow by Thursday, whole team pivots to unblock. |
| **Nagad PGW sandbox documentation is incomplete** | Medium | Low | Use SSLCommerz as aggregator (handles Nagad internally). Direct Nagad integration is a stretch goal, not MVP-blocking. |

---

## 18. Novelty & Emergence Argument

### 18.1 What Makes This Novel

PRISM is novel **at the intersection**, not at any individual component. What does not exist — especially for Bangladeshi SMEs — is a single platform combining:

```
┌─────────────────────────────────────────────────────────────────┐
│                    PRISM'S NOVELTY MAP                           │
│                                                                 │
│  ┌─── Commerce ───┐   ┌─── Intelligence ───┐                   │
│  │ Multi-vendor    │   │ GBR ONNX forecast  │                   │
│  │ Order lifecycle │   │ Self-improving loop │                   │
│  │ bKash + Nagad   │   │ Cross-vendor emerge │                   │
│  │ Reviews + VPS   │   │ Weather-aware       │                   │
│  └────────┬────────┘   └────────┬────────────┘                   │
│           │                     │                                │
│           └──────── FUSION ─────┘                                │
│                     │                                            │
│  ┌─── Bangladesh ──┐│  ┌─── Accessibility ──┐                   │
│  │ Festival Calendar││  │ PWA (offline-ready) │                   │
│  │ Bengali UI + WA  ││  │ WCAG 2.1 AA         │                   │
│  │ Monsoon awareness││  │ Mobile-first 375px   │                   │
│  │ bKash/Nagad pay  ││  │ Bangla onboarding    │                   │
│  └──────────────────┘│  └─────────────────────┘                   │
│                      │                                            │
│              ALL AT BDT 0/MONTH                                   │
└─────────────────────────────────────────────────────────────────┘
```

**No existing platform — commercial, open-source, or academic — combines all of these.**

---

### 18.2 Why This Qualifies as Emergence — Three Distinct Layers

> **Definition:** Emergence in software systems means system-level behavior that arises from component interactions and was **not explicitly programmed as a top-level rule.**

#### Layer 1: Per-Product Learning Emergence

```
Components (each has a narrow, independent job):
  Module 01 (GBR ONNX)       → generates a forecast, stores it in ai_forecasts
  order_items                → accumulates real purchases (buyers act independently)
  CRON Job                   → computes forecast_error, stores in forecast_accuracy
  Retraining Trigger         → reads rolling_avg_error, fires GBR retraining
  Module 01 (next inference) → loads new model weights

What EMERGES (not explicitly programmed):
  ✅ Vendors who use the system more get increasingly accurate forecasts
  ✅ Products with irregular demand patterns receive model updates tuned to their behavior
  ✅ The system develops per-product memory without being told to do so
```

#### Layer 2: Cross-Vendor Network Emergence

```
Components (each has a narrow, independent job):
  Vendor A's order_items     → accumulates independently (serves their own customers)
  Vendor B's order_items     → accumulates independently
  Vendor C's order_items     → accumulates independently
  Hourly CRON Job            → aggregates category-level velocity across ALL vendors
  category_velocity_score    → injected into every vendor's GBR inference call
  GBR Model                  → has learned high category velocity = higher individual demand

What EMERGES (not explicitly programmed):
  ✅ A Chawkbazar fabric vendor benefits from buying patterns of ALL other fabric vendors
  ✅ When Eid approaches and category velocity rises platform-wide, each vendor's
     reorder point is automatically elevated — even for new products with no personal history
  ✅ No vendor programmed this collective behavior — it arises from independent transactions
  ✅ This is genuine network emergence: collective intelligence from individual agents
```

#### Layer 3: Environmental Adaptation Emergence (NEW)

```
Components (each has a narrow, independent job):
  OpenWeatherMap API         → provides raw weather data (temperature, rain)
  Weather CRON               → caches and derives is_monsoon flag
  Festival Calendar          → provides is_festival_week, days_to_next_festival
  GBR Model                  → has learned INTERACTIONS between weather + festivals

What EMERGES (not explicitly programmed):
  ✅ The GBR model learns that Eid + monsoon = different demand pattern than Eid + dry
     (e.g., umbrella gifts spike during rainy Eid, outdoor fabric drops)
  ✅ The model adapts to COMBINED environmental signals that no single module understands
  ✅ A vendor selling outdoor supplies gets a lower forecast when Eid falls during
     monsoon season — a pattern that emerges from the interaction of two independent
     feature sources, not from any hardcoded rule
```

---

### 18.3 Summary Comparison

| Compared To | Their Gap | PRISM's Advantage |
|---|---|---|
| Shopify / Daraz | No native demand prediction, English-only, no festival or weather awareness | GBR ONNX predicts what will sell, alerts in Bangla via WhatsApp, festival + weather intelligence prevents overstock |
| Netstock | No commerce layer, no Bangla, enterprise pricing | PRISM closes the loop: ML inventory intelligence inside a live commerce platform, in Bengali, free |
| sheba.xyz | No AI or inventory | Full GBR ML backend, festival + weather intelligence, and WhatsApp-native delivery |
| Chaldal | Grocery-only, no multi-vendor, no vendor AI | PRISM is multi-vendor, category-agnostic, with 11 AI modules and vendor-facing dashboards |
| Any BD student project | Typically CRUD-only or static analytics | GBR ONNX model with 13 features, 3-layer emergence, weather-aware, What-If planner, Bengali UI, festival calendar, PWA offline — none combined before |

---

## 19. Testing Strategy

| Test Type | Tool | Coverage Target | What is Tested |
|---|---|---|---|
| **Unit Tests** | Jest (NestJS) | 80% line coverage on all NestJS services | GBR AI module logic, ONNX inference wrapper, order state machine transitions, coupon validation, ROP formula (with festival + weather multipliers), anomaly Z-score calculation (5 signals), festival feature injection, category_velocity computation, weather feature derivation, locale routing, delivery assignment logic |
| **Integration Tests** | Jest + Supertest | All API endpoints | Auth flow (register → login → refresh → phone verify), order checkout flow (bKash + Nagad + SSLCommerz), payment webhook handler with server-side validation, WhatsApp notification dispatch (EN + বাংলা), festival calendar query, cross-vendor velocity aggregation, weather API integration, delivery status updates |
| **E2E Tests** | Playwright | 8 critical user flows | Buyer: browse → cart → checkout → order tracking. Vendor: forecast dashboard → reorder alert → What-If planner. Admin: anomaly review → escalate. Vendor: language toggle EN → বাংলা → all labels switch. Delivery: view assignments → pick up → deliver. Buyer: review after delivery. |
| **GBR Model Validation** | Custom Jest test | Model output within 30% of WMA baseline | Smoke-test GBR ONNX inference against hand-computed WMA for 3 known seed products before each deploy. Validate that festival, weather, and category velocity feature injection each change output as expected. Test with all 13 features present and with fallback defaults. |
| **Cross-Vendor Privacy Audit** | Manual + Supabase RLS test | Zero cross-vendor data leakage | Confirm `/api/ai/category-velocity/:categoryId` returns only aggregate score (min 3 vendors). RLS policy tested with two vendor JWTs. Verify no raw individual vendor data exposed in any response. |
| **Security Tests** | Manual + OWASP ZAP | Auth endpoints, RLS, payments | JWT expiry enforcement, RLS data isolation between vendors + delivery partners, rate limiter activation, CORS headers, CSP headers, payment webhook signature validation, locale parameter injection (non-valid locales rejected) |
| **Accessibility Tests** | axe-core + manual | WCAG 2.1 AA compliance | Color contrast ratios, keyboard navigation, screen reader compatibility (NVDA/VoiceOver), focus management, ARIA labels on all interactive elements, Bengali text readability |
| **PWA Tests** | Lighthouse + manual | PWA score > 90 | Installability, offline dashboard load, service worker cache, background sync, Web Push notification delivery |

---

## 20. Accessibility & Inclusivity (NEW)

> Accessibility is not a luxury feature — it's a moral and practical requirement. Many vendors in rural Bangladesh have low vision or limited digital literacy. An inclusive platform serves more people.

### 20.1 WCAG 2.1 AA Compliance Targets

| Principle | Implementation |
|---|---|
| **Perceivable** | All images have alt text. Color is never the sole indicator (icons + text labels). Minimum 4.5:1 contrast ratio for text. Bengali text rendered at minimum 16px. |
| **Operable** | Full keyboard navigation (Tab, Enter, Escape). Skip-to-content link. No seizure-inducing animations. Touch targets minimum 44×44px on mobile. |
| **Understandable** | Form fields have visible labels (not just placeholders). Error messages are specific and actionable ("Enter a valid phone number starting with +880"). Language is declared in HTML (`lang="en"` or `lang="bn"`). |
| **Robust** | Semantic HTML5 elements (`<nav>`, `<main>`, `<article>`). ARIA roles on custom components (shadcn/ui). Tested with NVDA (Windows) and VoiceOver (iOS). |

### 20.2 Digital Literacy Accommodations

| Feature | Detail |
|---|---|
| **Guided Onboarding** | Step-by-step wizard (in Bangla) walks new vendors through: 1) Enter past sales, 2) List first product, 3) View first forecast. Progress bar shows completion. |
| **Tooltip Explanations** | Every AI metric (forecast confidence, feature importance, VPS score) has a tooltip with a plain-language explanation in the user's locale. |
| **Help Videos** | Short (60-second) embedded video tutorials for key flows: adding a product, reading a forecast, understanding a restock alert. Available in Bangla. |
| **Large Touch Targets** | Mobile UI designed with minimum 48px touch targets — larger than WCAG minimum — for users unfamiliar with small UI elements. |
| **Error Recovery** | Undo capability for critical actions (stock adjustments, order cancellations). Confirmation dialogs in Bangla before destructive actions. |

---

## 21. Future Roadmap (Post-Course) (NEW)

> These features go beyond the 6-week course timeline but represent the natural evolution of PRISM Commerce if it were to become a real product.

### Phase 7 — Post-Course Enhancements

| Feature | Description | Complexity |
|---|---|---|
| **Multi-City Weather** | Per-vendor city selection for weather forecasts (Dhaka, Chittagong, Sylhet, Rajshahi). | Low |
| **Supplier Integration** | Vendors can link to their suppliers. Auto-generate purchase orders when stock hits ROP. | High |
| **LightGBM Upgrade** | Migrate from scikit-learn GBR to LightGBM for faster training and better handling of large datasets. Export via `onnxmltools`. | Medium |
| **Customer Segmentation** | AI module that clusters buyers by purchasing behavior (RFM analysis). Helps vendors target promotions. | Medium |
| **Multi-Language Expansion** | Add Hindi, Urdu, and Arabic for South Asian / Middle Eastern market expansion. RTL-ready architecture already in place. | Medium |
| **Mobile App (React Native)** | Native mobile app wrapping the PWA for Play Store / App Store distribution. | High |
| **Voice Input (Bangla)** | Vendors can dictate product descriptions and stock updates in Bangla using Web Speech API. | Medium |
| **Blockchain Audit Trail** | Immutable order and payment logs anchored to a public blockchain for dispute resolution. | High |
| **Social Commerce** | Direct integration with Facebook Shops and Instagram Shopping for multi-channel selling. | Medium |
| **Carbon Footprint Tracking** | Track and display the carbon footprint of deliveries. Appeal to eco-conscious buyers. | Low |

---

## 22. Sustainability & Cost Breakdown

| Service | Free Tier Limit | PRISM Usage Estimate | Status |
|---|---|---|---|
| Vercel Hobby | 100GB bandwidth, unlimited deploys | < 1GB for demo | ✅ Safe |
| Render Free / Railway | 750h/month (Render) or 500h/month (Railway) | ~500h for 30-day demo period | ✅ Safe |
| Supabase Free | 500MB DB, 50k MAU, 1GB storage | < 50MB DB, < 100 users | ✅ Safe |
| Upstash Redis | 10,000 commands/day | ~800 commands/day (forecasts 24h + category 1h + weather 6h + rate limiting) | ✅ Safe |
| GitHub Actions | 2,000 minutes/month | < 200 min/month (4 PRs/week) | ✅ Safe |
| SSLCommerz Sandbox | Unlimited sandbox transactions | Test transactions only | ✅ Safe |
| bKash PGW Sandbox | Unlimited sandbox transactions | Test transactions only | ✅ Safe |
| Nagad PGW Sandbox | Unlimited sandbox transactions | Test transactions only | ✅ Safe |
| Meta WhatsApp Cloud API | 1,000 conversations/month free | < 50 conversations for demo (EN + বাংলা combined) | ✅ Safe |
| OpenWeatherMap | 60 calls/min, 1M calls/month | 1 call/day (cached 6h) = ~30 calls/month | ✅ Safe |
| Sentry (free tier) | 5,000 events/month | < 500 events for demo | ✅ Safe |
| Figma Starter | 3 projects, unlimited viewers | 1 project | ✅ Safe |
| onnxruntime-node | Open source npm package | In-process GBR inference, no API calls | 💚 Zero cost |
| scikit-learn + skl2onnx | Open source Python packages | Run once offline to train and export GBR model | 💚 Zero cost |
| next-intl | Open source npm package | Locale routing, EN + Bengali translation files | 💚 Zero cost |
| next-pwa | Open source npm package | Service worker, offline cache, installability | 💚 Zero cost |
| axe-core | Open source npm package | Accessibility testing | 💚 Zero cost |
| UptimeRobot | 50 monitors, 5-min checks | 1 monitor for Render warmup | ✅ Safe |
| **Total Monthly Cost** | — | — | 🏆 **BDT 0.00** |

> **Note:** Deployment cost is not a constraint for this project. The free-tier stack is chosen to demonstrate that a world-class AI commerce platform can be built without financial barriers — making it accessible to any student or entrepreneur in Bangladesh.

---

## 23. Glossary (NEW)

> For non-technical readers, evaluators, and team members who need quick definitions.

| Term | Plain English Explanation |
|---|---|
| **GBR (Gradient Boosting Regressor)** | A type of machine learning model that builds hundreds of simple "decision trees" (flowcharts of if-then rules) that together predict a number — in our case, how many units of a product will sell. |
| **ONNX** | Open Neural Network Exchange — a file format that lets you train a model in Python and run it in JavaScript (or any other language). Think of it as a "universal translator" for AI models. |
| **ROP (Reorder Point)** | The inventory level at which a vendor should order more stock. PRISM calculates this dynamically based on AI predictions, not a fixed number. |
| **EOQ (Economic Order Quantity)** | A formula that calculates the ideal amount of stock to order to minimize total cost (ordering cost + holding cost). |
| **Z-Score** | A statistical measure of how far a data point is from the average. In PRISM, a high Z-score on an order means it's suspiciously different from normal orders. |
| **Feature (ML)** | A single piece of input data that the AI model uses to make a prediction. Example: "number of units sold in the last 7 days" is one feature. PRISM uses 13 features. |
| **Feature Importance** | The AI model's explanation of which inputs mattered most for a prediction. Example: "Eid proximity drove 43% of this forecast." |
| **Inference** | When the AI model takes in features and produces a prediction. In PRISM, one inference takes less than 80 milliseconds. |
| **CRON Job** | A scheduled task that runs automatically at set intervals. Example: "Every hour, compute category velocity scores." |
| **RLS (Row-Level Security)** | A database feature that ensures each user can only see their own data, even if they try to query directly. Prevents vendor A from seeing vendor B's sales. |
| **PWA (Progressive Web App)** | A web application that can be "installed" on a phone's home screen and works offline, like a native app, but is actually just a website with extra capabilities. |
| **SSR (Server-Side Rendering)** | The server builds the HTML page before sending it to the browser, making the page load faster and more SEO-friendly. |
| **JWT (JSON Web Token)** | A secure, time-limited "pass" that proves a user is logged in. Expires every 15 minutes for security. |
| **Webhook** | A way for one service to notify another when something happens. Example: bKash sends a webhook to PRISM when a payment succeeds. |
| **Prisma** | A tool that lets developers write database queries in TypeScript instead of raw SQL. Prevents SQL injection by design. |
| **Supabase** | An open-source alternative to Firebase that provides a PostgreSQL database, authentication, real-time subscriptions, and file storage — all with a free tier. |
| **Redis** | An in-memory database used for caching. PRISM uses it to store frequently accessed data (forecasts, category scores) so the main database isn't overwhelmed. |
| **Emergence** | System-level behavior that arises from the interaction of simple components but was not explicitly programmed. Example: individual vendors' sales data collectively teaching the AI about market trends. |
| **Category Velocity Score** | A number representing how fast a product category is selling across ALL vendors on the platform. A rising score before Eid means the entire category is heating up. |
| **Data Quality Score** | A 0–1 score showing how much of the AI's training data comes from real sales (1.0 = all real) vs. vendor-entered estimates (0.0 = all seed data). |
| **TTL (Time To Live)** | How long a cached value stays valid before it expires and must be refreshed. Example: forecasts have a 24-hour TTL. |
| **WCAG 2.1 AA** | Web Content Accessibility Guidelines — an international standard for making websites usable by people with disabilities. "AA" is the middle compliance level. |
| **MFS (Mobile Financial Services)** | Digital payment services accessed via mobile phone. In Bangladesh, bKash and Nagad are the dominant MFS providers. |

---

## Quick Summary: Why PRISM Commerce is a 10/10 Project

```
✅ Real AI — not fake AI. A proper Gradient Boosting Regressor (GBR) exported
   to ONNX format, running in < 80ms inside NestJS. 13 engineered features
   including weather, festival, and cross-vendor signals. No gimmicks.

✅ THREE layers of genuine EMERGENCE:
   • Per-product self-improving forecasts (feedback loop via CRON)
   • Cross-vendor collective intelligence (market signals from all vendors)
   • Environmental adaptation (weather × festival interaction learning)

✅ Bangladesh-specific — not a copy-paste platform:
   • Festival Intelligence Calendar (Eid, Puja, Boishakh, Ramadan pre-loaded)
   • Bengali (বাংলা) UI, WhatsApp templates, and onboarding
   • bKash + Nagad + SSLCommerz payment integration
   • Monsoon-aware demand signals via OpenWeatherMap

✅ Validated with real vendors — 5 interviews confirmed every feature decision.

✅ Production-grade security — RLS, JWT rotation, rate limiting, CSP, audit logs,
   payment webhook verification, cross-vendor data isolation.

✅ Complete full-stack — 5 user roles, 11 AI modules, full order lifecycle with
   delivery tracking, mobile-first PWA dashboard, What-If scenario planner,
   analytics, PDF exports — all in Bengali and English.

✅ Accessible — WCAG 2.1 AA compliant, guided onboarding, tooltips, large touch
   targets, screen reader support.

✅ Observable — Sentry error tracking, Winston structured logs, custom health
   endpoint, performance targets documented.

✅ BDT 0.00/month — 100% free tier. No financial barriers for any student or
   entrepreneur in Bangladesh.

✅ 6-week phased plan — MVP by Week 4, all stretch goals by Week 6.
   Clear fallback strategy if behind schedule.
```

---

*PRISM Commerce — Predictive Retail Intelligence & Stock Management*  
*Project Plan Version 2.0 (Upgraded) — April 2026*  
*Course: Advanced Programming in Web Technology | Final Project Plan*  
*Built with: Next.js · NestJS · Supabase · ONNX GBR · Redis · WhatsApp · bKash*
