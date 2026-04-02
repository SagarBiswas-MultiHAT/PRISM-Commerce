# 🚀 PRISM Commerce — V4.0 (Production-Grade Startup Edition)

<div align="center">
  <a href="https://github.com/SagarBiswas-MultiHAT/PRISM-Commerce">
    <img src="https://img.shields.io/badge/version-4.0.0--Beta-blue.svg?style=for-the-badge" alt="Version">
  </a>
  <img src="https://img.shields.io/badge/license-Proprietary-red.svg?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/build-passing-brightgreen.svg?style=for-the-badge" alt="Build">
  <img src="https://img.shields.io/badge/coverage-85%25-green.svg?style=for-the-badge" alt="Coverage">
</div>
<br/>

<div align="center">
  <img src="https://img.shields.io/badge/Next.js_15-black?style=flat-square&logo=next.js&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/AI-ONNX_%7C_Llama_3.2-FF6F00?style=flat-square" alt="AI">
</div>
<br/>

### Predictive Retail Intelligence & Stock Management

> Bangladesh's first **Bangla-native, AI-agentic, live commerce-enabled** multi-vendor marketplace with **regulatory compliance**, **marketplace trust**, and **production-grade architecture**.

---

## 🎯 What is PRISM? (For Everyone)

**Think of PRISM Commerce as a mix of Daraz, Shopify, and a smart business assistant, built entirely for Bangladesh.**

Small merchants in Bangladesh struggle with multiple platforms: selling on Facebook, tracking stock in notebooks or scattered software, managing bKash payments manually, and guessing what customers will buy next. 

PRISM Commerce is a unified platform that solves all of these problems at once by combining four major features:
1. **A Massive Marketplace:** Reach buyers directly.
2. **SaaS Tools:** Manage your inventory, sales, and payments from one dashboard.
3. **Local Payment & Trust Ecosystem:** Fully handles bKash, SSLCommerz, and Bangladesh Bank’s Escrow regulations.
4. **Agentic Artificial Intelligence:** PRISM doesn't just give you advice; it has a smart Bangla-speaking assistant (**Sahayak**) that can automatically create discounts, reply to customers, and re-order stock for you.

---

## 📁 Attached Project Documents & Navigation

To understand the full depth of PRISM Commerce, please refer to the attached detailed planning documents. They document our journey from a V1 academic concept to a V4 production-ready startup plan. 

### 🌟 Core Project Plans
* [**PRISM Commerce Project Plan V4.0.0**](./PRISM_Commerce_ProjectPlan_v4.0.0.md) — (Latest) Full production-grade startup plan (1640+ lines).
* [**PRISM Commerce Project Plan V3.0.0**](./PRISM_Commerce_ProjectPlan_v3.0.0.md) — The V3 phase introducing hybrid monetization.
* [**PRISM Commerce Project Plan V2.0.0**](./PRISM_Commerce_ProjectPlan_v2.0.0.md) — Enhanced course-level architecture plan.
* [**PRISM Commerce Project Plan V1.0.0**](./PRISM_Commerce_ProjectPlan-v1.0.0.md) — Original proof-of-concept plan.

### 👥 Team & Operations
* [**PRISM Team Plan (Markdown)**](./PRISM_Team_Plan.md) — Detailed 15-month roadmap, 4-person equity split, and specific role responsibilities.
* [**PRISM Team Plan (Docx)**](./PRISM_Team_Plan.docx) — Word document version of the team plan.
* [**Co-Founder Recruitment Drafts**](./recruitment_message.md) — Pitch messages designed to recruit Member B, C, and D.

### 🇧🇩 Regional Context & Explanations
* [**Bangla Overview (বাংলা সারসংক্ষেপ)**](./Bangla.md) — Visual diagrams and a layman’s explanation of the startup completely in Bengali.

### 🔄 Project Evolution Changelogs (Walkthroughs)
* [**V3 to V4 Changelog**](./walkthrough(v3-v4).md) — What changed to make the project production-ready.
* [**V2 to V3 Changelog**](./walkthrough(v2-v3).md)
* [**V1 to V2 Changelog**](./walkthrough(v1-v2).md)

*(Note: You are currently reading `readme.md`)*

---

## 🏗️ Elite Tech Stack

PRISM implements modern, robust technologies built to scale to millions of concurrent users.

| Layer | Technology |
|---|---|
| **Frontend** | Next.js 15 (App Router, PPR, PWA) |
| **Mobile App** | React Native (Expo) |
| **Styling** | Tailwind CSS + shadcn/ui + Radix |
| **Backend Core** | NestJS + TypeScript (CQRS + Event Sourcing) |
| **Database** | PostgreSQL 16 + pgvector + Read Replica |
| **Cache & Queue**| Redis 7 + BullMQ |
| **ML Engine** | ONNX Runtime (GBR demand forecasting) |
| **GenAI** | Ollama (Llama 3.2, agentic) + OpenAI GPT-4o fallback |
| **Search** | Meilisearch (full-text) + pgvector (semantic/RAG) |
| **Real-time** | Socket.io + SSE |
| **Live Video** | LiveKit (WebRTC SFU) + HLS Recording |
| **Payments** | bKash + Nagad + SSLCommerz + Bangla QR + Rocket + Escrow |
| **Notifications**| WhatsApp Business Cloud API + Email + Web Push |
| **Infrastructure**| Docker + Grafana + Prometheus + Sentry + OpenTelemetry |

---

## 🧠 AI Intelligence Layer — 15 Built-in Modules

Unlike typical software, PRISM has 15 interconnected AI modules acting as the "brain" of the platform.

| # | Module | What It Does |
|---|---|---|
| 01 | **ONNX GBR Forecasting** | Predicts sales (7/14/30d) using 13 features including weather + festival signals |
| 02 | **Smart Reorder Point** | Alerts vendors *before* stockout using AI-adjusted safety stock |
| 03 | **Sales Velocity Ranker** | Identifies trending and decelerating products |
| 04 | **Coupon Optimizer** | Recommends minimum discount to clear surplus stock |
| 05 | **Anomaly Detector** | Flags suspicious orders using Z-score (6 signals including COD history) |
| 06 | **Vendor Performance Score**| 0-100 composite trust metric with tier badges |
| 07 | **WhatsApp Notifications** | EN + বাংলা alerts (12 template types) |
| 08 | **Cross-Vendor Emergence** | Category velocity aggregated across all vendors securely |
| 09 | **Feedback Loop** | Auto-retrains ML model when forecast error > 25% |
| 10 | **Weather Engine** | Translates monsoon + heat metrics into sales demand via OpenWeatherMap |
| 11 | **What-If Planner** | Interactive scenario simulation with ONNX re-inference |
| 12 | **Agentic GenAI Sahayak** 🆕| Bangla & English AI that **ACTS** on requests (makes coupons, adds to cart, etc.) |
| 13 | **RAG Semantic Search** | Natural-language Bangla product discovery powered by pgvector |
| 14 | **Opportunity Engine** 🆕 | Proactive pricing intelligence refreshing every 15-minutes |
| 15 | **Bundle Recommender** 🆕 | AI-generated product pairing from co-purchase analytics patterns |

---

## 🇧🇩 Deeply Local: Bangladesh-Native Features

Built from day one to respect the reality of doing retail in Bangladesh.

- 🕌 **Festival Intelligence Calendar** — Accounts for sales surges during Eid, Puja, and Boishakh.
- 🌧️ **Weather-Aware Demand** — Lowers digital demand but boosts specific product sales during Monsoons.
- 💬 **WhatsApp Business API** — Sellers and Buyers communicate naturally over WhatsApp templates.
- 💳 **Bangla QR & Escrow** — Compliant up to the June 2026 mandates of Bangladesh Bank digital commerce.
- 🚚 **Local 3PL Ready** — Built-in shipping hooks for Pathao, Paperfly, RedX, Steadfast, and eCourier. 
- 🏪 **Offline POS Mode** — Accept sales offline inside the physical store; inventory syncs to the cloud automatically.

---

## 💰 The Business Model

PRISM Commerce offers an incredibly accessible **Hybrid SaaS + Commission** business model for our vendors:

| Tier | Price (৳/mo) | Products | Commission | Key Features |
|---|---|---|---|---|
| **Free** | ৳0 | 5 | 5% | Basic forecast, 3 AI queries/day |
| **Starter** | ৳500 | 50 | 4% | Full AI + POS + 2 live streams/mo |
| **Growth** | ৳2,000 | 500 | 3% | GenAI + What-If + Opportunity Engine + Unlimited Live |
| **Pro** | ৳5,000 | Unlimited| 2.5% | API access + Brand Store + Dedicated CSM |
| **Enterprise** | Custom | Unlimited| 2% | Everything + White-Label + SLA |

---

## 📊 Project Version Comparison Map

| Dimension | V1 (Course Demo) | V2 (Enhanced Plan) | V3 (Startup Vision) | V4 (Production Ready) |
|---|---|---|---|---|
| AI Modules | 9 | 11 | 13 | **15** |
| GenAI Type | None | None | Sahayak (Advisor Mode) | **Sahayak V2 (Agentic Mode)** |
| Commerce Scope| Static Web | PWA Web | Live Video + Social | **Live + Short-form Reels + POS** |
| Trust/Security| Minimal | Minimal | Vendor Performance | **Verified Vendors + Buyer Protect + BD Escrow** |
| Payments | Sandbox | Sandbox | Production Keys | **+ Bangla QR + Escrow Lifecycle** |
| Tech Architecture| Standard Monolith| Monolith | Modular Monolith | **CQRS + Event Sourcing + Read Replicas** |
| DB Tables | ~15 | ~20 | ~30 | **50+ Database Entities** |

---

*"একটি প্লাটফর্ম যা বাংলাদেশের প্রতিটি ছোট দোকানদারকে AI-এর ক্ষমতা দিয়ে সজ্জিত করে — এবং তাদের হয়ে কাজও করে।"*  
*"A platform that equips every small shopkeeper in Bangladesh with the power of AI — and acts on their behalf."*

---

## 📜 License

**License: Proprietary**

This project, its architecture, and the PRISM Commerce platform are the intellectual property of **Sagar Biswas**. All rights reserved. Do not distribute, modify, or use for commercial purposes without explicit permission.

---
© **Sagar Biswas** — [PRISM Commerce Platform](https://github.com/SagarBiswas-MultiHAT/PRISM-Commerce)
