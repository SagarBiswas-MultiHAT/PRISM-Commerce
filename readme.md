# 🚀 PRISM Commerce — V3.0 (Startup Edition)

### Predictive Retail Intelligence & Stock Management

> Bangladesh's first **Bangla-native, AI-powered, live commerce-enabled** multi-vendor marketplace.

---

## 🎯 What is PRISM?

PRISM Commerce is an AI-driven e-commerce platform that combines **predictive inventory intelligence** with a **full multi-vendor marketplace**, a **Bangla-speaking GenAI assistant**, **live commerce**, and **social commerce** — purpose-built for Bangladeshi SMEs.

> **One sentence:** The platform that makes Daraz, Shopify, and Netstock unnecessary for Bangladeshi merchants — by combining marketplace reach, SaaS power, and forecasting intelligence with local relevance that none of them have.

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Next.js 15 (App Router, SSR, PWA) |
| **Mobile** | React Native (Phase 3) |
| **Styling** | Tailwind CSS + shadcn/ui + Radix |
| **Backend** | NestJS + TypeScript |
| **Database** | PostgreSQL 16 + pgvector |
| **Cache & Queue** | Redis 7 + BullMQ |
| **ML Engine** | ONNX Runtime (GBR demand forecasting) |
| **GenAI** | Ollama (Llama 3.2 / Mistral) + OpenAI fallback |
| **Search** | Meilisearch (full-text) + pgvector (semantic/RAG) |
| **Real-time** | Socket.io (chat, notifications) |
| **Live Video** | LiveKit (WebRTC SFU) |
| **Payments** | bKash + Nagad + SSLCommerz (Production) |
| **Notifications** | WhatsApp Business Cloud API + Email + SMS |
| **Infrastructure** | Docker + Grafana + Prometheus + Sentry |

---

## 🧠 AI Intelligence Layer

| # | Module | What It Does |
|---|---|---|
| 01 | **ONNX GBR Forecasting** | Predicts sales (7/14/30d) using 13 features including weather + festival signals |
| 02 | **Smart Reorder Point** | Alerts vendors *before* stockout using AI-adjusted safety stock |
| 03 | **Sales Velocity Ranker** | Identifies trending and decelerating products |
| 04 | **Coupon Optimizer** | Recommends minimum discount to clear surplus stock |
| 05 | **Anomaly Detector** | Flags suspicious orders using Z-score behavioral analysis |
| 06 | **Vendor Performance Score** | 0-100 composite trust metric with tier badges |
| 07 | **WhatsApp Notifications** | EN + বাংলা alerts for low stock, orders, weather, festivals |
| 08 | **Cross-Vendor Emergence** | Category velocity aggregated across all vendors |
| 09 | **Feedback Loop** | Auto-retrains model when forecast error > 25% |
| 10 | **What-If Planner** | Interactive scenario simulation with ONNX re-inference |
| 11 | **Weather Engine** | OpenWeatherMap signals for monsoon-driven demand |
| 12 | **GenAI Sahayak** 🆕 | Bangla + English AI assistant for vendors and buyers |
| 13 | **RAG Search** 🆕 | Semantic product search via pgvector embeddings |

---

## 🆕 What's New in V3 (Startup Transformation)

| Module | Description |
|---|---|
| **🔴 Live Commerce** | Vendors go LIVE, pin products, buyers buy in-stream |
| **📱 Social Commerce** | Facebook Shops sync, WhatsApp Catalog, affiliate system |
| **🤖 GenAI Assistant** | "PRISM Sahayak" — AI shopping/vendor assistant in Bangla |
| **💰 PRISM Wallet** | Digital wallet with cashback, instant refunds |
| **💳 BNPL** | Buy Now Pay Later via local BD providers |
| **🚚 3PL Logistics** | Pathao, Paperfly, RedX, Steadfast integration |
| **💬 In-App Chat** | Real-time buyer-seller messaging with AI auto-response |
| **📊 Advanced Analytics** | Profit reporting, RFM, CLV, ABC analysis, AI weekly digest |
| **🏢 Multi-Tenant SaaS** | Subscription tiers, white-label, plan enforcement |
| **👥 Affiliate System** | Referral tracking, commission payouts, influencer dashboard |
| **💵 Monetization** | Hybrid SaaS + Commission + Promoted Listings + Wallet |

---

## 💰 Business Model

**Hybrid SaaS + Commission + Advertising**

| Tier | Price (৳/mo) | Products | Commission | Key Features |
|---|---|---|---|---|
| **Free** | ৳0 | 5 | 5% | Basic AI forecast |
| **Starter** | ৳500 | 50 | 4% | Full AI + 2 live streams/mo |
| **Growth** | ৳2,000 | Unlimited | 3% | Full AI + GenAI + What-If + Unlimited Live |
| **Enterprise** | Custom | Unlimited | 2% | Everything + API + White-Label |

---

## 🇧🇩 Bangladesh-Native Features

- 🕌 **Festival Intelligence Calendar** — Eid, Puja, Boishakh surge prediction with 14-day pre-alerts
- 🌧️ **Weather-Aware Demand** — monsoon and heat signals via OpenWeatherMap
- 💬 **WhatsApp Business API** — notifications in English + Bengali (বাংলা)
- 💳 **bKash + Nagad + SSLCommerz** — production payment integration
- 🤖 **Bangla GenAI** — PRISM Sahayak speaks Bengali
- 🚚 **Local 3PL** — Pathao, Paperfly, RedX, Steadfast, eCourier

---

## 📁 Project Structure

```
PRISM-Commerce/
├── PRISM_Commerce_ProjectPlan_v3.0.0.md   # Full V3 startup plan (1780+ lines)
├── PRISM_Commerce_ProjectPlan_v2.0.0.md   # Original V2 course project plan
├── Bangla.md                               # Bengali project summary
├── readme.md                               # This file
└── walkthrough.md                          # V2→V3 changelog
```

---

## 📊 V2 → V3 Comparison

| Dimension | V2 (Course Project) | V3 (Startup) |
|---|---|---|
| Revenue | BDT 0/month | SaaS + Commission + Ads |
| Scale | ~100 products | 10K+ vendors, 1M+ users |
| AI | 11 modules + GBR | 13 modules + GenAI + RAG |
| Commerce | Static pages | Live Commerce + Social |
| Chat | WhatsApp only | In-app + WhatsApp + SMS |
| Delivery | Basic role | 3PL integration |
| Payments | Sandbox | Production APIs + Wallet + BNPL |
| Infra | Free-tier | Docker + VPS + Managed DB |
| Mobile | PWA only | PWA + React Native |
| Timeline | 6 weeks | 12-month phased launch |

---

## 📜 License

This project plan and architecture is the intellectual property of Sagar Biswas.

---

*"একটি প্লাটফর্ম যা বাংলাদেশের প্রতিটি ছোট দোকানদারকে AI-এর ক্ষমতা দিয়ে সজ্জিত করে।"*
