# 🛒 PRISM Commerce
## Predictive Retail Intelligence & Stock Management

> **Course:** Advanced Programming in Web Technology — Final Project Plan  
> **Version:** 1.0
> **Total Deployment Cost: BDT 0.00/month**

---

```
Stack:  Next.js · NestJS · Supabase · ONNX GBR · Redis · WhatsApp · bKash
Extras: Bengali (বাংলা) Language · Festival Intelligence Calendar · Mobile-First Design
AI:     8 REST Engines + 1 ONNX Gradient Boosting Regressor ML Model
```

---

## 📋 Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Problem Statement](#2-problem-statement)
3. [Unique Value Proposition](#3-unique-value-proposition)
4. [User Architecture — 4 Roles](#4-user-architecture--4-roles-one-ecosystem)
5. [System Architecture](#5-system-architecture)
6. [Core Feature Set](#6-core-feature-set)
7. [AI Intelligence Layer — 9 Modules](#7-ai-intelligence-layer--8-engines--1-onnx-gbr-model)
8. [Bangladesh-Native Integrations](#8-bangladesh-native-integrations)
9. [Technology Stack — 100% Free](#9-technology-stack--100-free)
10. [Database Schema](#10-database-schema--complete-table-reference)
11. [Key API Endpoints](#11-key-api-endpoints-rest-contract-preview)
12. [UI Wireframes & Screens](#12-ui-wireframes--screen-specifications)
13. [Security Architecture](#13-security-architecture--defense-in-depth)
14. [Development Roadmap — 6 Phases](#14-development-roadmap--6-phases)
15. [Team Responsibility Matrix](#15-team-responsibility-matrix)
16. [Risk Register & Mitigation](#16-risk-register--mitigation-plan)
17. [Novelty & Emergence Argument](#17-novelty--emergence-argument)
18. [Testing Strategy](#18-testing-strategy)
19. [Free Tier Sustainability](#19-free-tier-sustainability--cost-breakdown)

---

## 1. Executive Summary

PRISM Commerce is a **Predictive Retail Intelligence and Stock Management** platform that unifies e-commerce operations with an AI-driven inventory intelligence layer.

### Who is it for?
Small-to-mid-scale businesses in the **Bangladeshi market** — vendors who currently rely on intuition, spreadsheets, or nothing at all.

### What problem does it solve?
No existing platform addresses: live commerce + built-in demand prediction + automated reorder alerts + vendor performance intelligence + Bengali-language support + a Bangladesh Festival Intelligence Calendar — **all in one system, at zero cost.**

### What makes it intelligent?
- A **Gradient Boosting Regressor (GBR)** model serialized to ONNX format, delivering superior accuracy for Bangladesh's non-linear, festival-driven retail demand.
- A **closed feedback loop** that creates emergent per-product intelligence — improving automatically over time.
- A **cross-vendor category emergence** layer that provides collective intelligence across the platform without exposing any vendor's private data.

### Bangladesh-Native Differentiators:
- WhatsApp Business Cloud API with **Bangla-language** template messages
- **bKash** push notifications (Bangladesh's #1 mobile money platform)
- **BD Festival Calendar** — Eid, Puja, Pohela Boishakh, and national holidays pre-loaded

### At a Glance

| Dimension | Detail |
|---|---|
| Category | E-Commerce + AI Inventory |
| Stack | Next.js, NestJS, Supabase, ONNX, Redis |
| User Roles | 4 distinct roles: Super Admin, Vendor, Buyer, Support |
| AI Modules | 8 REST engines + 1 ONNX GBR ML model (built into NestJS) |
| ML Model | Gradient Boosting Regressor → serialized via scikit-learn → ONNX |
| Language Support | English + Bengali (বাংলা) via next-intl i18n |
| Local Integrations | WhatsApp Business API + bKash |
| Festival Calendar | Eid, Puja, Boishakh + national holidays (built-in DB table) |
| Mobile Design | Responsive, mobile-first vendor dashboard (Tailwind breakpoints) |
| Cross-Vendor AI | Category-level demand signals across vendors (emergent intelligence) |
| Deployment Cost | **BDT 0 / month** (100% free-tier stack) |
| MVP Target | Forecast + Order Lifecycle (Weeks 1–4) |

---

## 2. Problem Statement

Small-to-mid-scale businesses in Bangladesh operate on **intuition**. They overstock slow-moving items, run out of bestsellers during Eid and Puja peaks, and have zero visibility into what will happen next week.

### The 5 Core Failure Modes

| # | Problem | Real-World Impact |
|---|---|---|
| **P1** | **Stock Loss** | Overstocking ties up capital. Stockouts during peak periods kill revenue. Manual tracking is always reactive. |
| **P2** | **Fragmented Operations** | Orders, inventory, and analytics live in separate tools. No single source of truth exists across the order lifecycle. |
| **P3** | **Zero Foresight** | Vendors react *after* problems occur. No system proactively tells them: *"Reorder this item — you will run out in 9 days."* |
| **P4** | **Language Barrier** | Existing digital tools are English-only. Vendors in informal markets like Chawkbazar are excluded from digital adoption. |
| **P5** | **Festival Blindness** | No tool accounts for Bangladesh's festival-driven demand surges (Eid, Puja, Pohela Boishakh). Vendors overprepare for the wrong events. |

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
| Daraz / Shopify | No native demand prediction, English-only | PRISM predicts what will sell, alerts in Bangla via WhatsApp |
| Netstock | No commerce layer | PRISM closes the loop: ML inventory intelligence built into a live commerce platform |
| sheba.xyz | No AI or inventory | PRISM has a full ML backend, GBR forecasting, and WhatsApp-native delivery |
| Any BD student project | Typically CRUD-only or static analytics | PRISM has a GBR ONNX model, self-improving feedback loop, cross-vendor emergence, and Bangla UI |

---

## 3. Unique Value Proposition

> **Core Thesis:**
> Most commerce platforms tell you **what happened.**
> PRISM tells you **what is about to happen** — and exactly what to do about it.
>
> Predictive inventory intelligence + production-ready commerce + WhatsApp-native alerts in Bangla,
> unified under a single mobile-first platform, built entirely with free tools, deployed at zero cost.

### Key Differentiators (10 of them):

1. **GBR Demand Forecasting per SKU** — Gradient Boosting Regressor serialized to ONNX predicts sales for 7, 14, and 30 days, with non-linear festival-peak modeling superior to linear regression.

2. **Smart Reorder Point Engine** — fires alerts *before* stockout using EOQ model with AI-adjusted safety stock.

3. **Bangladesh Festival Intelligence Calendar** — built-in table of Eid, Durga Puja, Pohela Boishakh, and national holidays auto-populates the `is_festival_week` ML feature with a 14-day pre-surge window.

4. **Bengali (বাংলা) Language Support** — full UI translation via `next-intl`, WhatsApp alerts sent in Bangla using Meta-approved Bangla templates.

5. **Cross-Vendor Category Emergence** — category-level demand signals aggregated anonymously across all vendors, providing each vendor with collective market intelligence without exposing any private data.

6. **Coupon Optimization** — recommends the minimum discount to clear surplus stock based on price elasticity.

7. **Anomaly Detection** — flags suspicious order patterns for fraud review using Z-score on behavioral signals.

8. **Vendor Performance Scoring** — composite trust tier fed by fulfillment, ratings, and speed.

9. **Mobile-First Design** — vendor dashboard built responsive-first at 375px (mobile), 768px (tablet), 1440px (desktop) using Tailwind CSS breakpoints.

10. **Closed-Loop ML Feedback** — GBR model retrains on new data every 7 days, improving forecast accuracy automatically.

**Bonus:** A cold-start solution ensures the platform is usable from Day 0, even without historical data, via a 3-tier seed strategy.

---

## 4. User Architecture — 4 Roles, One Ecosystem

PRISM has **four distinct user roles**, each with a tailored experience:

| | Super Admin | Buyer (General User) | Vendor (Service Provider) | Support & Billing |
|---|---|---|---|---|
| **Role Label** | System Controller | The Buyer | The Seller | Operations Manager |
| Full platform visibility | ✅ | — | — | — |
| Browse & search products | — | ✅ | — | — |
| Manage product listings | — | — | ✅ | — |
| Handle support tickets | — | — | — | ✅ |
| Manage categories & users | ✅ | — | — | — |
| Add to cart, apply coupons | — | ✅ | — | — |
| View GBR demand forecasts | — | — | ✅ | — |
| Manage payment records | — | — | — | ✅ |
| Monitor all transactions | ✅ | — | — | — |
| Checkout & payment | — | ✅ | — | — |
| Receive WhatsApp alerts (EN/বাংলা) | — | — | ✅ | — |
| Generate invoices | — | — | — | ✅ |
| View all order states | ✅ | — | — | — |
| Track orders real-time | — | ✅ | — | — |
| Update order status | — | — | ✅ | — |
| Resolve billing disputes | — | — | — | ✅ |
| AI model health checks | ✅ | — | — | — |
| Write reviews & ratings | — | ✅ | — | — |
| Create & manage coupons | — | — | ✅ | — |
| View financial reports | — | — | — | ✅ |
| Platform-wide reports | ✅ | — | — | — |
| AI recommendations | — | ✅ | — | — |
| Sales analytics dashboard | — | — | ✅ | — |
| Escalate to Super Admin | — | — | — | ✅ |
| Cross-vendor emergence panel | ✅ | — | — | — |
| Language toggle (EN/বাংলা) | — | ✅ | — | — |
| Festival demand calendar | — | — | ✅ | — |
| Billing PDF export | — | — | — | ✅ |

---

## 5. System Architecture

### 5.1 Architecture Overview

PRISM uses a **unified monorepo architecture (Turborepo)** with two primary runtime services:

```
┌─────────────────────────────────────────────────────────────┐
│                    PRISM COMMERCE SYSTEM                     │
├────────────────────────┬────────────────────────────────────┤
│   Next.js 14 Frontend  │        NestJS Backend API           │
│   (App Router + SSR)   │   (All features + AI modules)       │
│   Tailwind + shadcn/ui │                                     │
│   next-intl (EN + BN)  │  ┌──────────────────────────────┐  │
│   Recharts             │  │   ONNX GBR ML Model           │  │
│   Zustand (cart)       │  │   (onnxruntime-node)          │  │
│   375px / 768px /      │  │   Inference < 80ms            │  │
│   1440px breakpoints   │  │   Cached 24h in Redis         │  │
└────────────────────────┴──┴──────────────────────────────┴──┘
         │                              │
         │ HTTPS REST                   │ Prisma ORM
         ▼                              ▼
┌────────────────┐           ┌─────────────────────┐
│  Supabase      │           │   Upstash Redis      │
│  PostgreSQL    │           │   (Cache layer)       │
│  Auth + RLS    │           │  Forecasts: TTL 24h  │
│  Realtime WS   │           │  Category: TTL 1h    │
│  Storage       │           └─────────────────────┘
└────────────────┘
         │
         ├──── WhatsApp Business Cloud API (EN + বাংলা)
         ├──── bKash PGW + SSLCommerz (Payments)
         └──── festival_calendar table (GBR feature injection)
```

**Key Architecture Principle — Unified ML Backend:**
- All AI prediction engines are NestJS modules exposing REST endpoints.
- The ONNX GBR model runs **in-process** (no separate Python service, no extra deployment cost).
- Inference runs in **<80ms** per product. Result cached in Redis for 24h.
- The Festival Calendar table is queried at inference time to inject `is_festival_week` and `days_to_next_festival` features.
- The cross-vendor category signal is computed once per hour by a lightweight CRON job.

---

### 5.2 Data Flow — Two Core Journeys

#### Journey A: Vendor Views GBR Forecast

```
Vendor (Browser)
    │  Opens dashboard (locale from user.preferred_locale)
    ▼
Next.js Frontend
    │  GET /api/ai/forecast/:productId
    ▼
NestJS AI Module
    │  Checks Upstash Redis cache (TTL 24h)
    │  [Cache miss] → Query last 90 days from Supabase order_items
    ▼
NestJS Festival Module
    │  Injects: is_festival_week (0/1), days_to_next_festival (int), festival_type (enum)
    ▼
NestJS Category Module
    │  Injects: category_velocity_score (Redis cached hourly)
    ▼
NestJS GBR Module
    │  Loads ONNX model → GBR inference (<80ms)
    ▼
NestJS AI Module
    │  Writes result to ai_forecasts table + caches in Redis
    ▼
Vendor (Browser)
    └  Recharts renders trend chart + confidence interval in selected locale
```

#### Journey B: Buyer Places Order With WhatsApp Notification

```
Buyer (Browser)
    │  Adds items to cart (Zustand, persisted to Supabase)
    │  Checkout → applies coupon → selects language (EN/বাংলা)
    ▼
NestJS API
    │  Validates coupon → calculates final amount
    │  Redirects to SSLCommerz/bKash payment gateway
    ▼
Payment Gateway
    │  Returns success webhook → NestJS /api/payment/webhook
    ▼
NestJS API
    │  Creates order record + decrements inventory (Prisma atomic transaction)
    │  Triggers async reorder-point check for affected SKUs
    ▼
WhatsApp Module
    │  If stock <= ROP → sends WhatsApp in vendor's preferred locale (EN or বাংলা)
    ▼
Supabase Realtime
    │  Pushes order status update to buyer's browser via WebSocket
    ▼
audit_logs
    └  Immutable record: buyer_id, vendor_id, amount, timestamp, locale
```

---

### 5.3 Service Communication Map

| From | To | Protocol & Purpose |
|---|---|---|
| Next.js (RSC/Client) | NestJS REST API | HTTPS REST — all feature calls |
| NestJS API | Supabase PostgreSQL | Prisma ORM — queries and mutations |
| NestJS API | Upstash Redis | REST via @upstash/redis — forecast cache, category signals |
| NestJS API | Supabase Auth | JWT validation middleware |
| NestJS API | SSLCommerz / bKash | HTTPS REST — payment initiation |
| SSLCommerz / bKash | NestJS Webhook | HTTPS POST — payment callback |
| Supabase Realtime | Next.js Client | WebSocket — order status push |
| NestJS WhatsApp Module | Meta Cloud API | HTTPS POST — EN/বাংলা WhatsApp delivery |
| NestJS GBR Module | ONNX Runtime (in-process) | Node.js — demand inference <80ms |
| NestJS Festival Module | festival_calendar table | Prisma read — inject festival features |
| NestJS CRON (hourly) | Supabase + Redis | Compute category_velocity_score across all vendors |
| NestJS AI CRON (weekly) | Supabase + ONNX | Scheduled GBR retraining every 7 days |

---

## 6. Core Feature Set

### 6.1 Commerce Layer

| Feature | Detail |
|---|---|
| **Multi-Vendor Product Catalog** | Vendors list products with variants (size, color), pricing, and images. Buyers browse with smart filters by category, price, and rating. |
| **Cart, Coupons & Checkout** | Persistent Zustand cart with coupon validation. SSLCommerz and bKash payment integration. Order confirmation via email + WhatsApp (EN/বাংলা). |
| **Full Order Lifecycle** | State machine: Pending → Confirmed → Processing → Shipped → Delivered. Real-time push via Supabase Realtime WebSocket. |
| **Reviews & Vendor Ratings** | Post-delivery review system. Feeds into the Vendor Performance Score AI module. |
| **AI Product Recommendations** | Buyers see 'Trending Now' and 'You May Like' shelves powered by GBR sales velocity scoring. |

### 6.2 Inventory Layer

| Feature | Detail |
|---|---|
| **Real-Time Stock Tracking** | Per-product, per-variant inventory counter auto-decrements on purchase via atomic Prisma transaction. Full audit log. |
| **Context-Aware Low-Stock Alerts** | Alerts are GBR ML-triggered (not fixed threshold). The reorder engine considers demand velocity, seasonal peaks, and upcoming festival proximity from the ONNX model and festival_calendar. |
| **WhatsApp Low-Stock Notifications** | When stock drops below ROP, vendor receives a WhatsApp message via Meta Business Cloud API — delivered in the vendor's preferred language (English or বাংলা). No app needed. |
| **Sales Analytics Dashboard** | Revenue charts (Recharts), top-performing products, conversion rates, period-over-period comparison. |
| **Exportable Reports** | CSV, JSON and PDF exports for inventory state, sales summaries, and billing records. |

### 6.3 Admin & Operations Layer

| Feature | Detail |
|---|---|
| **Vendor Approval Workflow** | New vendor registrations require Super Admin approval before listings go live. |
| **Anomaly Alert Dashboard** | Flagged orders surface here for review by Support & Billing before fulfillment proceeds. |
| **Vendor Performance Leaderboard** | VPS scores displayed as a ranked table. Low-scoring vendors flagged for review or suspension. |
| **Platform-Wide Analytics** | Super Admin sees total GMV, order volume, user growth, and revenue attribution by vendor. |
| **Invoice Generation** | Auto-generated PDF invoices for each order, stored in Supabase Storage, downloadable by buyer and vendor. |
| **Cross-Vendor Emergence Panel** | Chart showing category_velocity_score trends and per-vendor forecast error rates across CRON cycles. Demonstrates system-level learning. |

---

### 6.4 Bengali (বাংলা) Language & Localization Layer

> This is a **first-class platform feature**, not an afterthought. All 5 vendors interviewed use Bangla as their primary language with suppliers and customers.

| Component | Implementation Detail |
|---|---|
| **Routing & Locale Detection** | Next.js App Router with next-intl locale middleware. Routes: `/en/...` and `/bn/...`. Auto-detects browser locale on first visit. User preference stored in `users.preferred_locale`. |
| **UI Translation Files** | JSON locale files at `/messages/en.json` and `/messages/bn.json`. Covers: all navigation labels, form fields, error messages, button text, status labels, alert messages. |
| **WhatsApp Bangla Templates** | Meta-approved message templates in Bengali for: `low_stock_alert_bn`, `order_confirmed_bn`, `order_shipped_bn`, `weekly_forecast_bn`. Submitted for Meta approval in Week 2. |
| **Number & Currency Formatting** | Bengali numeral support (১২৩৪) using `Intl.NumberFormat` with `locale='bn-BD'`. Currency displayed as ৳ (BDT). |
| **Onboarding in Bangla** | Vendor onboarding flow (seed data entry, product listing) fully available in Bangla. Reduces adoption friction for non-English-fluent vendors. |

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

**How the Festival Calendar Feeds the GBR Model:**

The `festival_calendar` table is queried at every inference call. Two features are injected:

- `is_festival_week`: **1** if today falls within any festival's surge_window, else **0**
- `days_to_next_festival`: integer count of days until the next festival's surge window opens

The GBR model has learned patterns like:
- Fabric & garment products spike 14 days before Eid
- Craft products spike 7 days before Pohela Boishakh
- The post-festival correction window (days 3–7 after festival) depresses demand

**Real-world example:** Vendor V1 (Chawkbazar fabric vendor) over-buys before Eid. With PRISM, she receives a WhatsApp alert 14 days before Eid with an accurate restock target — preventing dead stock.

---

### 6.6 Mobile-First Vendor Dashboard

> All 5 interviewed vendors use smartphones as their primary device. The desktop-first assumption is **incorrect** for this market.

| Breakpoint | Layout | Key Adaptations |
|---|---|---|
| **375px (Mobile)** | Single-column card stack | Top: 2 metric cards (Low-Stock SKUs + Today's Revenue). Mid: Scrollable product list with stock badge. Bottom: Forecast mini-chart. WhatsApp alert badge prominent. |
| **768px (Tablet)** | Two-column grid | Left: Product list (40%). Right: Forecast chart + reorder gauge (60%). All metric cards visible. |
| **1440px (Desktop)** | Full three-zone layout | Full dashboard with analytics, coupon optimizer, VPS leaderboard, and cross-vendor emergence panel. |

---

## 7. AI Intelligence Layer — 8 Engines + 1 ONNX GBR Model

All AI modules are NestJS modules (TypeScript) exposing REST endpoints. Redis caches expensive computation. A scheduled CRON job retrains the ONNX model weekly.

### Cold-Start Solution (Critical for Demo Day)

> **Problem:** All forecasting modules need historical sales data. A new platform has none on launch day.

**Three-Tier Bootstrap Strategy:**

| Tier | When | What Happens |
|---|---|---|
| **Tier 1 (Day 0)** | Onboarding | Vendor manually enters their past 30-day sales per product (in Bangla or English). Stored as `synthetic_sales_seed` records — the initial training dataset. |
| **Tier 2 (Week 1+)** | Early use | Real order data accumulates and gradually supplements seeded data. GBR model uses real data preferentially; seed data fills gaps. |
| **Tier 3 (Day 90+)** | Full maturity | Sufficient real data exists. Seed data is deprecated. Model retrains fully on real history. |

---

### Module 01 — ONNX Gradient Boosting Regressor (Real ML)

**Why GBR, Not Linear Regression?**

Linear Regression cannot model the exponential Eid surge, the post-festival correction dip, or category-level interaction effects. GBR builds an **ensemble of decision trees** that handles:

- Non-linear interactions (e.g., high `days_to_next_festival` + high `category_velocity` = much higher forecast)
- Feature importance ranking → interpretable output: *"Eid proximity drove 43% of this forecast"*
- Better generalization with sparse data (30-day seed) than linear models
- Model size: ~60–150KB (vs ~12KB for linear) — still negligible for Render free tier

| Property | Value |
|---|---|
| Endpoint | `GET /api/ai/forecast/:productId` |
| Model | GradientBoostingRegressor serialized to ONNX (~80–150KB) |
| Runtime | onnxruntime-node v1.17 — runs in NestJS process, inference **<80ms** |
| Input Features | `quantity_7d`, `quantity_14d`, `quantity_30d`, `day_of_week` (0–6), `is_festival_week` (0/1), `days_to_next_festival` (int), `festival_type` (enum encoded), `category_elasticity`, `category_velocity_score` (cross-vendor) |
| Output | `{ forecast_7d, forecast_14d, forecast_30d, confidence: float, feature_importance: object, model_version, generated_at }` |
| Training | GBR trained offline on public Bangladesh retail datasets + synthetic data. Exported via skl2onnx. Retrained weekly by CRON job. |
| Cache TTL | 24 hours (Upstash Redis) |
| Fallback | Uses `synthetic_sales_seed` if real order count < 14 days |

---

### Module 02 — Smart Reorder Point Calculator

**Endpoint:** `GET /api/ai/reorder/:productId`  
**Algorithm:** EOQ Model with GBR-Adjusted Safety Stock

```
ROP = (Average Daily Demand × Lead Time Days) + Safety Stock

Safety Stock = Z-score (1.65 for 95% service level)
             × Std Dev of Daily Demand
             × sqrt(Lead Time)
```

- Average Daily Demand sourced from GBR Module 01 forecast.
- If `days_to_next_festival < 14` → safety stock increased by the festival demand multiplier from `festival_calendar` table.
- When `current_inventory <= ROP` → low-stock alert fires to vendor via **WhatsApp** (preferred locale) + in-app notification.

---

### Module 03 — Sales Velocity Momentum Ranker

**Endpoint:** `GET /api/ai/velocity`  
**Algorithm:** Exponential Smoothing on Rolling 7-day Sales Rate

Every product receives a momentum score (rate-of-change in sales velocity):
- **Accelerating products** → promoted to the "Trending" shelf on the buyer homepage.
- **Plateauing products** → trigger a vendor WhatsApp notification suggesting action.
- Per-product velocity feeds the cross-vendor category signal (Module 08).

---

### Module 04 — Coupon Optimization Advisor

**Endpoint:** `POST /api/ai/coupon-optimize`  
**Algorithm:** Price Elasticity Model + Surplus Ratio Calculation

```
Optimal Discount = (Surplus Ratio - 1) / Price Elasticity of Demand
```

- Triggers when a vendor has surplus stock (supply days > 45).
- Calculates the **optimal discount** to clear inventory without margin collapse.
- Category-level elasticity values seeded from market research defaults, refined over time.
- Festival proximity increases recommended discount urgency when a post-festival correction is expected.

---

### Module 05 — Order Anomaly Detector

**Endpoint:** Triggered async on every new order via `POST /api/ai/anomaly/check`  
**Algorithm:** Z-Score on Order Behavioral Signals

Evaluates **4 signals**:
1. Order frequency per user per hour
2. Order quantity vs. category average
3. Shipping address vs. account registration region
4. Payment method age

Composite Z-score > 2.5 → flags the order + soft-pauses fulfillment. False-positive rate logged to tune the threshold via Admin panel slider.

---

### Module 06 — Vendor Performance Score (VPS)

**Endpoint:** `GET /api/ai/vps/:vendorId`  
**Algorithm:** Weighted Composite Score with Time Decay

Produces a **0–100 score** from 4 weighted components:

| Component | Weight |
|---|---|
| Fulfillment Rate | 40% |
| Avg Customer Rating | 30% |
| Avg Response-to-Ship Time | 20% |
| Dispute Rate | 10% |

> Time decay down-weights events older than 90 days.

**Trust Tier System:**

| Score Range | Trust Tier | Action |
|---|---|---|
| **85–100** | **Platinum** | Priority listing placement, featured badge, eligible for homepage promotion |
| 70–84 | Gold | Standard listing, eligible for promotions |
| 50–69 | Silver | No featured placement, monitored |
| **Below 50** | **Watch** | Admin review triggered, suspension risk |

---

### Module 07 — WhatsApp Business Notification Engine (EN + বাংলা)

| Property | Value |
|---|---|
| API | Meta WhatsApp Business Cloud API — free up to 1,000 conversations/month |
| Languages | English + Bengali (বাংলা) — Meta-approved templates for both locales |
| Trigger Events | Stock below ROP, new order placed, order status change, anomaly flag, weekly forecast summary, **festival pre-surge reminder** |
| Bangla Template Example | `low_stock_alert_bn`: *'আপনার [PRODUCT] এর স্টক কম! [QTY] টি বাকি আছে। রিঅর্ডার পয়েন্ট: [ROP]'* |
| Template Approval | English + Bangla templates submitted for Meta approval in Week 2. Demo uses Meta test number if approval is pending. |
| Fallback | In-app notification via Supabase Realtime if WhatsApp delivery fails |

---

### Module 08 — Cross-Vendor Category Emergence (NEW)

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

---

### Module 09 — Closed-Loop GBR Feedback (Emergence)

**How the Per-Product Feedback Loop Creates Emergence:**

```
Day N:    Module 01 (GBR ONNX) predicts units sold over next 7 days.
          → Result stored in ai_forecasts.

Day N+7:  Scheduled NestJS CRON job runs.
          → Queries actual order_items for that product over past 7 days.
          → Computes: forecast_error = abs(predicted - actual) / actual
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

## 8. Bangladesh-Native Integrations

PRISM is not merely a generic platform labelled for Bangladesh. Three integrations are meaningfully local.

### 8.1 WhatsApp Business Cloud API

| Property | Detail |
|---|---|
| **Why WhatsApp?** | Bangladesh has 45M+ WhatsApp users. Vendors in informal markets use WhatsApp groups to coordinate with suppliers daily. Push notifications to WhatsApp have far higher open rates than email for this demographic. |
| API | Meta WhatsApp Business Cloud API (free for first 1,000 conversations/month) |
| Language Support | Message templates approved in both English and Bengali. User's `preferred_locale` determines which template is sent. |
| Bangla Template Example | *'স্টক সতর্কতা: আপনার [পণ্যের নাম] এর স্টক [পরিমাণ] তে পৌঁছেছে। রিঅর্ডার এখনই করুন।'* |
| Message Types | Low-stock alert, order confirmed, order shipped, anomaly flag, weekly AI forecast digest, festival pre-surge reminder (14 days before Eid/Puja) |
| Fallback | In-app Supabase Realtime notification if WhatsApp delivery fails |

### 8.2 bKash Payment Integration

| Property | Detail |
|---|---|
| **Why bKash?** | bKash has **67M registered accounts** in Bangladesh — the dominant mobile money platform. Most small buyers do not have cards; bKash is their primary digital payment method. |
| Integration Mode | bKash PGW (Payment Gateway) sandbox — free for developers |
| Flow | NestJS redirects buyer to bKash checkout page → bKash POSTs success callback to `/api/payment/webhook` → NestJS creates order and decrements inventory atomically. |
| Fallback | SSLCommerz sandbox as secondary gateway for card-based payments |

### 8.3 Bengali (বাংলা) Language Support

| Property | Detail |
|---|---|
| **Why Bengali?** | All 5 interviewed vendors use Bangla as their primary language. An English-only platform creates an adoption barrier for the exact demographic PRISM targets. |
| Implementation | `next-intl` package with Next.js App Router locale middleware. Routes: `/en/...` and `/bn/...` |
| Translation Scope | Full UI: navigation, forms, error messages, button text, status labels, alert messages, onboarding flow, product listing flow |
| Number Formatting | `Intl.NumberFormat` with `locale='bn-BD'` supports Bengali numerals (১২৩৪) and ৳ currency symbol |
| Font | Google Fonts: 'Hind Siliguri' for Bengali text rendering, loaded conditionally when `locale=bn` |

### 8.4 Bangladesh Festival Intelligence Calendar

| Property | Detail |
|---|---|
| What it is | A Supabase table (`festival_calendar`) pre-seeded with annual Bangladeshi festivals and their demand surge windows. |
| Queried at | Every GBR inference call — injects `is_festival_week` and `days_to_next_festival` features. |
| WhatsApp Integration | 14 days before any major festival → vendors receive a WhatsApp message (in their locale) with a pre-surge restock recommendation. |
| Annual Updates | Eid dates change yearly (lunar calendar). A yearly admin task updates the `festival_calendar` rows. No code change required. |
| Demo Value | For demo day, `festival_calendar` is seeded to simulate an upcoming Eid in 10 days, demonstrating how the restock alert changes in real time as `days_to_next_festival` decreases. |

---

## 9. Technology Stack — 100% Free

### 9.1 Core Services

| Layer | Technology | Why Chosen | Free Tier |
|---|---|---|---|
| **Frontend** | Next.js 14 (App Router) | SSR, RSC, file-based routing, Vercel-native, locale routing via next-intl | Vercel Hobby |
| **Styling** | Tailwind CSS + shadcn/ui | Rapid, consistent design system. Mobile-first breakpoints (375/768/1440px) | Free / OSS |
| **i18n** | next-intl | Locale routing, server-side translation, Bengali + English locale files | Free / OSS |
| **Backend API** | NestJS + TypeScript | Modular, decorator-driven, built-in Swagger, CRON scheduler | Render 750h/mo |
| **ML Engine** | ONNX Runtime (onnxruntime-node) | In-process GBR inference, no Python, no extra container | Free / OSS (npm) |
| **ML Training** | scikit-learn + skl2onnx | GBR training in Python, exported to .onnx for Node.js inference | Free / OSS |
| **Database** | PostgreSQL via Supabase | Relational, realtime, RLS, 500MB free | Supabase Free |
| **Auth** | Supabase Auth + JWT | Built-in RBAC, session management, 50k MAU | Supabase Free |
| **Realtime** | Supabase Realtime | WebSocket order status push, 200 concurrent | Supabase Free |
| **Storage** | Supabase Storage | Product images, PDF invoices, 1GB free | Supabase Free |
| **Payments** | SSLCommerz + bKash Sandbox | Bangladesh-native, sandbox mode free forever | Free Sandbox |
| **Cache** | Upstash Redis | Serverless Redis, 10,000 commands/day free. Stores: forecasts (24h TTL), category velocity scores (1h TTL) | Upstash Free |
| **Notifications** | Meta WhatsApp Business Cloud API | 1,000 conversations/month free. EN + বাংলা templates | Meta Free Tier |

### 9.2 Development & DevOps

| Layer | Technology | Purpose | Free Tier |
|---|---|---|---|
| **Monorepo** | Turborepo | Shared types, unified builds, caching | Free / OSS |
| **ORM** | Prisma | Type-safe DB queries, migrations | Free / OSS |
| **Testing** | Jest + Playwright | Unit (NestJS) + E2E (Next.js), 80% coverage target | Free / OSS |
| **API Docs** | Swagger (NestJS built-in) | Auto-generated OpenAPI spec at `/api/docs` | Free / OSS |
| **Scheduling** | @nestjs/schedule | CRON jobs for AI feedback loop, ONNX retraining, category velocity | Free / OSS |
| **Charts** | Recharts | Vendor analytics dashboards + forecast visualization | Free / OSS |
| **Wireframes** | Figma (Starter Plan) | UI mockups for all 6 key screens | Figma Free |
| **Logging** | Winston (NestJS) | Structured server-side logs | Free / OSS |
| **Version Control** | GitHub | Branching, PRs, Actions CI | Free |
| **CI/CD** | GitHub Actions | Lint, test (Jest), deploy on merge to main | 2,000 min/mo free |
| **FE Hosting** | Vercel Hobby | Edge-optimized Next.js, custom domain | Free |
| **BE Hosting** | Render Free | NestJS container, 750h/mo free | Free |

---

## 10. Database Schema — Complete Table Reference

### 10.1 Core Tables

#### `users`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | Auto-generated |
| email | text unique | — |
| role | enum | `super_admin \| buyer \| vendor \| support` |
| name, avatar_url | text | — |
| whatsapp_number | text | For WhatsApp notification delivery |
| **preferred_locale** | enum | **`en \| bn`** — determines language for WhatsApp + UI |
| created_at | timestamptz | — |

#### `products`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| vendor_id | uuid FK → users | — |
| category_id | uuid FK → categories | — |
| name, slug | text | slug unique |
| price | numeric(10,2) | — |
| is_active | boolean | Default false until approved |

#### `inventory`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| product_id | uuid FK → products | 1:1 relation |
| quantity | int | Current stock count |
| reorder_point | int | GBR-calculated, updated on forecast refresh |
| alert_sent | boolean | Prevents duplicate WhatsApp alerts |

#### `orders`
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| buyer_id | uuid FK → users | — |
| status | enum | `pending\|confirmed\|processing\|shipped\|delivered\|cancelled` |
| total_amount | numeric(10,2) | — |
| payment_ref | text | SSLCommerz/bKash transaction ID |
| is_flagged | boolean | Set by anomaly detector |

#### `order_items`
| Column | Type | Notes |
|---|---|---|
| order_id | uuid FK → orders | — |
| product_id | uuid FK → products | — |
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
| **feature_importance** | jsonb | GBR feature importance map e.g. `{is_festival_week: 0.43}` |
| model_version | text | ONNX GBR model version tag e.g. `gbr-v2.1` |
| generated_at | timestamptz | — |

#### `forecast_accuracy` (Enables the feedback loop)
| Column | Type | Notes |
|---|---|---|
| forecast_id | uuid FK → ai_forecasts | — |
| predicted_7d / actual_7d | int | `actual_7d` populated by CRON job |
| error_rate | float | `abs(pred-actual)/actual` |
| retrain_triggered | boolean | Set true when `error_rate > 0.25` |

#### `festival_calendar` (Pre-seeded, updated annually)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| name_en / name_bn | text | e.g. 'Eid-ul-Fitr' / 'ঈদুল ফিত্র' |
| festival_date | date | Approximate date for current year |
| surge_window_days | int | Days before festival that surge starts (e.g. 14 for Eid) |
| demand_multiplier | jsonb | Per-category multipliers e.g. `{clothing: 1.8, grocery: 1.6}` |
| is_active | boolean | Set false for past festivals |

#### `category_velocity` (Updated by hourly CRON job)
| Column | Type | Notes |
|---|---|---|
| id | uuid PK | — |
| category_id | uuid FK → categories | — |
| velocity_score | float | Avg units sold/day across **ALL vendors** in category |
| vendor_count | int | Number of vendors contributing to this score |
| computed_at | timestamptz | When CRON last ran |

#### `audit_logs` (Append-only, no UPDATE/DELETE via RLS)
| Column | Type | Notes |
|---|---|---|
| actor_id | uuid FK → users | — |
| action_type | text | e.g. `STOCK_UPDATE`, `ORDER_STATUS_CHANGE` |
| payload | jsonb | Full before/after state snapshot |

#### `notifications`
| Column | Type | Notes |
|---|---|---|
| user_id | uuid FK → users | — |
| type | enum | `LOW_STOCK \| ORDER_UPDATE \| ANOMALY_FLAG \| FESTIVAL_ALERT` |
| channel | enum | `WHATSAPP \| IN_APP` |
| locale | enum | `en \| bn` — locale used for message delivery |
| delivered | boolean | Tracks WhatsApp delivery status |

#### `synthetic_sales_seed` (Cold-start solution)
| Column | Type | Notes |
|---|---|---|
| product_id | uuid FK | — |
| units_sold | int | Entered by vendor at onboarding (EN or বাংলা form) |
| period_start / end | timestamptz | — |
| is_deprecated | boolean | Set true when 90 days of real data exists |

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

### AI & ML Modules

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/ai/forecast/:productId` | Vendor | GBR ONNX inference — returns 7/14/30d forecast + confidence + feature_importance + model_version |
| GET | `/api/ai/reorder/:productId` | Vendor | Returns GBR-based ROP including festival surge adjustment and current alert status |
| GET | `/api/ai/velocity` | Vendor | Products ranked by sales momentum (exponential smoothing) |
| POST | `/api/ai/coupon-optimize` | Vendor | Recommends optimal discount % for surplus SKU, festival urgency factored |
| POST | `/api/ai/anomaly/check` | Internal | Called async on each new order (Z-score) |
| GET | `/api/ai/vps/:vendorId` | Admin | Vendor Performance Score breakdown |
| GET | `/api/ai/category-velocity/:categoryId` | Vendor/Admin | Cross-vendor category velocity score (cached hourly in Redis) |
| POST | `/api/notifications/whatsapp` | Internal | Sends WhatsApp message via Meta Cloud API in correct locale (en\|bn) |
| GET | `/api/ai/feedback/accuracy` | Admin | Shows forecast_accuracy table with error trends and GBR improvement chart |
| PATCH | `/api/ai/anomaly/config` | Admin | Adjust Z-score threshold via Admin panel slider |

### Festival Calendar

| Method | Endpoint | Role | Description |
|---|---|---|---|
| GET | `/api/festivals/upcoming` | Any Auth | Returns next 3 festivals with `days_until` and `demand_multiplier` by category |
| GET | `/api/festivals/current-window` | Internal | Returns `is_festival_week` boolean and active festival details for GBR feature injection |
| PATCH | `/api/festivals/:id` | Super Admin | Update festival date (annual Eid date update) |

---

## 12. UI Wireframes & Screen Specifications

> Full interactive wireframes for all 6 key screens available in Figma. All screens at 1440px (desktop), 768px (tablet), 375px (mobile).

---

### Screen 1 — Vendor AI Intelligence Dashboard (Desktop 1440px)

```
┌─────────────────────────────────────────────────────────────┐
│  [Today's Revenue] [Orders Pending] [Low-Stock SKUs 🔴] [VPS]  │ ← Top Stats Bar
│                                               [EN | বাংলা]     │
├──────────────────────────┬──────────────────────────────────┤
│  Product List (40%)       │  Selected Product (60%)           │
│                           │                                   │
│  🔍 Search products       │  Recharts Area Chart:             │
│                           │  30d history + 30d GBR forecast   │
│  [Product A]              │  (dashed line + confidence band)  │
│   Stock: 12 ↑ 92%        │                                   │
│   🗓 Eid in 14 days       │  Festival Markers: 🔴 Eid (x-axis) │
│                           │                                   │
│  [Product B]              │  Feature Importance Bar:          │
│   Stock: 3 ↓ 67%  🚨      │  "Eid proximity drove 43%"        │
│                           │                                   │
├──────────────────────────┴──────────────────────────────────┤
│  🟡 Product B below ROP  🔴 Order #1234 flagged  🔵 Eid in 7d   │ ← Alert Strip
│                                     WhatsApp ✅ (বাংলা)         │
├─────────────────────────────────────────────────────────────┤
│  [Coupon Optimizer] Surplus products → Generate Coupon       │
│  [Category Velocity] Your fabric category ↑ 23% platform-wide │ ← Cross-Vendor Signal
└─────────────────────────────────────────────────────────────┘
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
│  🟡 Product B stock low!     │ ← Alert Banner (full-width)
│     WhatsApp alert sent ✅   │
├──────────────────────────────┤
│  [Product A]  ████████ 85%   │ ← Scrollable Product Cards
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
Order #ORD-2024-001  |  Dec 10, 2024  |  [Paid ✅]

── Pending ──●── Confirmed ──●── Processing ──○── Shipped ──○── Delivered
                                                      ↑ Real-time via WebSocket

Order Items:
┌────────────────────────────────────────────────────┐
│ [Img]  Product Name         Qty: 2   ৳1,200 each   │
│ [Img]  Another Product      Qty: 1   ৳850 each      │
│                    Subtotal:  ৳3,250                │
│                    Coupon -10%: −৳325               │
│                    Total:  ৳2,925                   │
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
GBR Model: v2.1  |  Last Retrained: 6 hours ago

═══ Emergence Panel ═══
[Chart 1: Per-Product Error Rate over CRON Cycles → trending down]
[Chart 2: Category Velocity Score over time → rising pre-Eid]
```

---

## 13. Security Architecture — Defense in Depth

| Security Layer | Implementation Detail |
|---|---|
| **Role-Based Access Control** | Every endpoint decorated with `@Roles()` guard. Four roles each have an explicit permission set enforced at NestJS middleware level. |
| **JWT + Refresh Token Rotation** | Access tokens expire in **15 minutes**. Refresh tokens rotate on every use and are invalidated server-side after use. Stolen tokens are automatically invalidated. |
| **API Rate Limiting** | Redis-backed rate limiter via `@nestjs/throttler`. `/auth/login` and `/checkout` throttled at 10 req/min per IP. Prevents brute force and cart-flooding. |
| **Input Validation & Sanitization** | All DTOs validated via `class-validator`. XSS protection via DOMPurify on frontend. Parameterized queries via Prisma prevent SQL injection by design. |
| **Supabase Row-Level Security (RLS)** | Vendors can only read and write their own product and inventory rows. `category_velocity` queries are aggregate-only. RLS enforced at the database layer. |
| **Immutable Audit Log** | Every admin action, stock change, and payment event written to an append-only `audit_logs` table. RLS policy: no UPDATE or DELETE allowed. |
| **WhatsApp Number Validation** | Phone numbers validated to `+880` prefix and confirmed via Twilio Lookup API (free tier) before WhatsApp messages are sent. |
| **HTTPS Only** | Vercel and Render enforce HTTPS on all traffic. CORS configured to whitelist only the Vercel frontend origin. |
| **Environment Secrets** | All API keys, DB URLs, JWT secrets, Meta WhatsApp token, bKash credentials stored as encrypted environment variables. Never committed to GitHub. |
| **Cross-Vendor Data Isolation** | The `category_velocity` computation runs as a server-side aggregate query only. No endpoint exposes raw data from other vendors. Only the anonymized category score is surfaced. |

---

## 14. Development Roadmap — 6 Phases

### MVP Core vs. Stretch Goals

**MVP Core (must ship by Week 4):**
Auth system (EN+বাংলা), product catalog, cart + checkout, order lifecycle, inventory tracking, GBR ONNX demand forecasting, reorder alerts, WhatsApp notifications (EN+বাংলা).

**Stretch Goals (Weeks 5–6):**
Coupon optimizer, anomaly detector, VPS scorer, analytics dashboards, ML feedback CRON, cross-vendor category emergence, festival calendar WhatsApp alerts, PDF export, full E2E tests.

**Fallback if behind by Week 3:**
Defer Modules 04–06 and cross-vendor emergence. Prioritize GBR forecast + WhatsApp (EN+বাংলা) + Festival Calendar as the core AI demo story.

---

### Phase Overview

| Phase | Week | Name | Key Deliverables |
|---|---|---|---|
| **01** | Week 1 | Foundation & Auth | Monorepo (Turborepo + Next.js + NestJS), complete DB schema in Prisma (incl. `festival_calendar` + `category_velocity` tables), multi-role auth with JWT + refresh rotation, next-intl locale routing (en + bn), login/register/role-redirect UI, Figma wireframes for all 6 screens |
| **02** | Week 2 | Core Commerce + WhatsApp (EN+বাংলা) | Product catalog + category management, cart (Zustand) + coupon validation, checkout with SSLCommerz + bKash, WhatsApp Business API setup + template approval (English AND Bengali templates), Bengali locale JSON files for all UI strings, vendor onboarding with seed data entry (bilingual form) |
| **03** | Week 3 | Order Lifecycle & Inventory | Full order state machine (Pending → Delivered) with Supabase Realtime push, inventory auto-decrement via Prisma transaction, manual stock adjustment, audit log writes, WhatsApp order status notifications in vendor's preferred locale, festival calendar seeded and queried |
| **04** | Week 4 | GBR ONNX + AI Modules (MVP) | Train GBR model offline (scikit-learn), export to ONNX via skl2onnx, wire onnxruntime-node in NestJS, build Modules 01–03 (Forecast, Reorder, Velocity), Redis caching, Recharts forecast charts with confidence band + festival surge markers, pre-seed demo database for emergence simulation |
| **05** | Week 5 | Analytics, Emergence & Admin | Analytics dashboards (Recharts), @nestjs/schedule CRON for ML feedback + retraining trigger, cross-vendor category velocity CRON (hourly), Modules 04–06 (Coupon, Anomaly, VPS), Super Admin anomaly panel with Emergence Chart (per-product + cross-vendor), Support & Billing panel with PDF invoice export, mobile-responsive vendor dashboard (375px breakpoint) |
| **06** | Week 6 | Polish, Security Audit & Deploy | Reviews + ratings, RLS enforcement audit on all tables (incl. `category_velocity` privacy guarantee), rate limiting hardening, CI/CD pipeline via GitHub Actions, deploy to Vercel + Render, full E2E tests with Playwright (80% coverage), demo-ready rehearsal with pre-seeded Eid scenario and emergence chart |

---

## 15. Team Responsibility Matrix

| Feature Area | Scope | Phase | Owner |
|---|---|---|---|
| Monorepo & CI/CD | Turborepo setup, GitHub Actions pipeline, Render/Vercel deploy | 1, 6 | Lead Developer |
| Auth System | Supabase Auth, JWT, RBAC guards, refresh rotation, locale middleware | 1 | Backend Engineer |
| DB Schema & Prisma | All table definitions, migrations, RLS policies, seed scripts | 1 | Backend Engineer |
| next-intl i18n Setup | Locale routing, EN + Bengali JSON files, number/currency formatting | 1, 2 | Frontend Engineer |
| Figma Wireframes | All 6 screens (desktop + mobile), 1440px + 375px, shared with evaluators | 1 | UI/UX Designer |
| Product Catalog UI | Buyer browse, search, filters, product detail page (bilingual) | 2 | Frontend Engineer |
| Vendor Dashboard UI | Listing management, stock UI, GBR forecast charts, festival markers, mobile layout | 2, 4, 5 | Frontend Engineer |
| Cart & Checkout | Zustand cart, coupon logic, SSLCommerz + bKash integration | 2 | Frontend Engineer |
| Bengali WhatsApp Templates | Draft all templates in Bangla, submit to Meta for approval, implement locale routing in notification module | 2 | Backend Engineer |
| Order Lifecycle | State machine, Realtime WebSocket, buyer tracking UI | 3 | Backend Engineer |
| Inventory Engine | Auto-decrement, audit log, manual adjustment, ROP alerts | 3 | Backend Engineer |
| Festival Calendar Module | `festival_calendar` table, API endpoints, GBR feature injection, festival WhatsApp reminders | 3, 4 | Backend Engineer |
| GBR ONNX ML Module | Offline model training (Python), ONNX export via skl2onnx, onnxruntime-node integration, inference endpoint | 4 | ML Engineer |
| AI Modules 02–03 | Reorder Point Calculator (festival-adjusted), Sales Velocity Ranker | 4 | ML Engineer |
| AI Modules 04–06 | Coupon Optimizer, Anomaly Detector, VPS Scorer | 4, 5 | ML Engineer |
| Cross-Vendor Category Emergence | Hourly CRON, `category_velocity` table, Redis caching, privacy audit | 5 | ML Engineer |
| ML Feedback CRON | @nestjs/schedule job, `forecast_accuracy` table, GBR retraining trigger | 5 | ML Engineer |
| Admin & Support UI | Anomaly panel, Emergence Chart (per-product + cross-vendor), VPS leaderboard, support ticket UI | 5 | Frontend Engineer |
| Analytics Dashboards | Recharts charts, CSV/PDF export, billing reports | 5 | Frontend Engineer |
| Mobile Responsive Layout | 375px vendor dashboard, card-based layout, bottom nav, WhatsApp alert card | 5 | Frontend Engineer |
| Reviews & Security Audit | Review system, RLS audit (incl. `category_velocity` privacy), rate limiting, E2E tests (Playwright) | 6 | UI/UX Designer + All |

---

## 16. Risk Register & Mitigation Plan

| Risk | Likelihood | Impact | Mitigation Strategy |
|---|---|---|---|
| **GBR ONNX model returns bad predictions with seed data** | High | High | Pre-train on public Bangladesh retail dataset + synthetic data before Week 4. Validate against manually computed WMA baseline. If GBR diverges >50%, fall back to WMA for demo while logging GBR output for review. |
| **WhatsApp Bengali template approval delayed by Meta (2–5 business days)** | Medium | High | Submit EN + Bengali templates in **Week 1** simultaneously. Use English templates as fallback for demo if Bengali approval is pending. Demo Bengali flow using Meta test number with pre-approved sandbox templates. |
| **Render free tier cold start (15 min inactivity)** | High | Medium | UptimeRobot pings Render URL every 5 minutes. 30-second startup is acceptable for demo with prior warning to evaluators. |
| **AI modules 04–06 or cross-vendor emergence not complete by Week 4** | Medium | High | Scoped as stretch goals. MVP demo story is GBR forecast + WhatsApp alert + festival calendar — complete without Coupon/Anomaly/VPS/cross-vendor. Defer to Week 5. |
| **GBR ONNX model file too large for Render free tier** | Low | Low | GBR ONNX model is ~60–150KB. No risk. Even a multi-layer neural network ONNX is <5MB. Well within Render's container limits. |
| **Bengali font rendering issues on mobile browsers** | Medium | Low | Load 'Hind Siliguri' from Google Fonts only when `locale=bn` to avoid performance impact. Test on Android Chrome and iOS Safari. Fall back to system sans-serif if font fails to load. |
| **festival_calendar Eid dates become stale (lunar calendar)** | Low | Medium | Document annual admin task in README: update Eid dates each year. No code change required — simple DB row update via Super Admin panel. Flag in handover documentation. |
| **Supabase free tier storage exceeded by product images** | Low | Low | Enforce 500KB max image upload on frontend. 1GB easily handles hundreds of products at demo scale. |
| **Team member falls behind on assigned area** | Medium | Medium | Daily 15-min standups via Discord. GitHub Projects kanban board. If any area is yellow by Thursday of its phase week, whole team pivots to unblock it. |

---

## 17. Novelty & Emergence Argument

### 17.1 What Makes This Novel

PRISM is novel **at the intersection**, not at any individual component. What does not exist — especially for Bangladeshi SMEs — is a single platform combining:

- Live commerce with genuine GBR-based predictive inventory intelligence
- Self-improving ONNX feedback loops (per-product) AND cross-vendor category signals (network-level)
- Bangladesh Festival Intelligence Calendar injecting Eid, Puja, and Boishakh demand surge features directly into the ML model
- Full Bengali (বাংলা) language support — UI, WhatsApp templates, and onboarding
- Mobile-first design built for vendors who use smartphones, not laptops
- All of this at **zero cost**, on entirely free-tier infrastructure

---

### 17.2 Why This Qualifies as Emergence — Two Distinct Layers

> **Definition:** Emergence in software systems means system-level behavior that arises from component interactions and was **not explicitly programmed as a top-level rule.**

#### Layer 1: Per-Product Learning Emergence

```
Components (each narrow job):
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

#### Layer 2: Cross-Vendor Network Emergence (NEW)

```
Components (each narrow job):
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

---

### Summary Comparison

| Compared To | Their Gap | PRISM's Advantage |
|---|---|---|
| Shopify / Daraz | No native demand prediction, English-only | GBR ONNX predicts what will sell, alerts in Bangla via WhatsApp, festival calendar prevents Eid overstock |
| Netstock | No commerce layer, no Bangla support | PRISM closes the loop: ML inventory intelligence inside a live commerce platform, in Bengali |
| sheba.xyz | No AI or inventory | Full GBR ML backend, festival intelligence, and WhatsApp-native delivery |
| Any BD student project | Typically CRUD-only or static analytics | GBR ONNX model retraining on real data, per-product + cross-vendor emergence, Bengali UI, and a festival calendar — none of which have been combined before in a student project |

---

## 18. Testing Strategy

| Test Type | Tool | Coverage Target | What is Tested |
|---|---|---|---|
| **Unit Tests** | Jest (NestJS) | 80% line coverage on all NestJS services | GBR AI module logic, ONNX inference wrapper, order state machine transitions, coupon validation, ROP formula, anomaly Z-score calculation, festival feature injection, category_velocity computation, locale routing |
| **Integration Tests** | Jest + Supertest | All API endpoints | Auth flow (register → login → refresh), order checkout flow, payment webhook handler, WhatsApp notification dispatch (EN + বাংলা), festival calendar query, cross-vendor velocity aggregation |
| **E2E Tests** | Playwright | 6 critical user flows | Buyer: product browse → cart → checkout → order tracking. Vendor: forecast dashboard → reorder alert (with festival marker). Admin: anomaly review → escalate. Vendor: language toggle EN → বাংলা → all labels switch. |
| **GBR Model Validation** | Custom Jest test | Model output within 30% of WMA baseline | Smoke-test GBR ONNX inference against hand-computed WMA for 3 known seed products before each deploy. Validate that festival feature injection changes output as expected. |
| **Cross-Vendor Privacy Audit** | Manual + Supabase RLS test | Zero cross-vendor data leakage | Confirm that `/api/ai/category-velocity/:categoryId` returns only aggregate score, not individual vendor breakdown. RLS policy tested with two vendor JWTs. |
| **Security Tests** | Manual + OWASP ZAP | Auth endpoints, RLS policies | JWT expiry enforcement, RLS data isolation between vendors, rate limiter activation, CORS headers, locale parameter injection (ensure non-valid locales are rejected) |

---

## 19. Free Tier Sustainability — Cost Breakdown

| Service | Free Tier Limit | PRISM Usage Estimate | Status |
|---|---|---|---|
| Vercel Hobby | 100GB bandwidth, unlimited deploys | < 1GB for demo | ✅ Safe |
| Render Free | 750 hours/month | ~500h for 30-day demo period | ✅ Safe |
| Supabase Free | 500MB DB, 50k MAU, 1GB storage | < 50MB DB, < 100 users | ✅ Safe |
| Upstash Redis | 10,000 commands/day | ~600 commands/day (forecasts 24h TTL + category velocity 1h TTL) | ✅ Safe |
| GitHub Actions | 2,000 minutes/month | < 200 min/month (4 PRs/week) | ✅ Safe |
| SSLCommerz Sandbox | Unlimited sandbox transactions | Test transactions only | ✅ Safe |
| bKash PGW Sandbox | Unlimited sandbox transactions | Test transactions only | ✅ Safe |
| Meta WhatsApp Cloud API | 1,000 conversations/month free | < 50 conversations for demo (EN + বাংলা combined) | ✅ Safe |
| Figma Starter | 3 projects, unlimited viewers | 1 project (6 screens) | ✅ Safe |
| onnxruntime-node | Open source npm package | In-process GBR inference, no API calls | 💚 Zero cost |
| scikit-learn + skl2onnx | Open source Python packages | Run once offline to train and export GBR model | 💚 Zero cost |
| next-intl | Open source npm package | Locale routing, EN + Bengali translation files | 💚 Zero cost |
| UptimeRobot | 50 monitors, 5-min checks | 1 monitor for Render warmup | ✅ Safe |
| **Total Monthly Cost** | — | — | 🏆 **BDT 0.00** |

---

## Quick Summary: Why PRISM Commerce is a 10/10 Project

```
✅ Real AI — not fake AI. A proper Gradient Boosting Regressor (GBR) exported
   to ONNX format, running in < 80ms inside NestJS. No gimmicks.

✅ Two layers of genuine EMERGENCE:
   • Per-product self-improving forecasts (feedback loop via CRON)
   • Cross-vendor collective intelligence (market signals from all vendors)

✅ Bangladesh-specific — not a copy-paste platform:
   • Festival Intelligence Calendar (Eid, Puja, Boishakh pre-loaded)
   • Bengali (বাংলা) UI, WhatsApp templates, and onboarding
   • bKash + SSLCommerz payment integration

✅ Validated with real vendors — 5 interviews confirmed every feature decision.

✅ Production-grade security — RLS, JWT rotation, rate limiting, audit logs.

✅ Complete full-stack — 4 user roles, 9 AI modules, full order lifecycle,
   mobile-first dashboard, analytics, PDF exports.

✅ BDT 0.00/month — 100% free tier. Commercially viable from Day 1.

✅ 6-week phased plan — MVP by Week 4, all stretch goals by Week 6.
```

---

*Document generated from PRISM_Commerce_10_10_ProjectPlan.docx (Version 2.0)*  
*Course: Advanced Programming in Web Technology | Final Project Plan*
