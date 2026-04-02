# V2 → V3 Changelog

## What Changed (V3.0.0 — Startup Transformation)

### New Modules
- 🤖 GenAI Commerce Assistant ("PRISM Sahayak" / প্রিজম সহায়ক) — Bangla + English AI assistant
- 🔍 RAG Semantic Product Search — pgvector-powered natural language search
- 🔴 Live Commerce Engine — WebRTC live streaming with shoppable video
- 📱 Social Commerce Bridge — Facebook Shops, WhatsApp Catalog, affiliates
- 💰 PRISM Wallet — digital wallet with cashback + instant refunds
- 💳 BNPL — Buy Now Pay Later via local BD providers
- 🚚 3PL Logistics — Pathao, Paperfly, RedX, Steadfast, eCourier integration
- 💬 In-App Communication Hub — buyer-seller chat, support tickets, AI auto-response
- 📊 Advanced Analytics — profit reporting, RFM, CLV, ABC analysis, AI weekly digest
- 🏢 Multi-Tenant SaaS — subscription billing, plan enforcement, white-label
- 👥 Affiliate Platform — referral tracking, commissions, influencer dashboard

### Architecture Changes
- Modular monolith (NestJS) with Docker-first containerization
- BullMQ event bus for async processing
- LLM Gateway pattern (Ollama local + OpenAI fallback)
- pgvector for RAG semantic search
- Meilisearch for full-text search
- Socket.io for real-time chat and notifications
- LiveKit for WebRTC live video
- API Gateway (Kong/Nginx)
- Full observability: Grafana + Prometheus + Loki + Sentry

### Business Model
- Hybrid SaaS + Commission monetization
- 4 pricing tiers: Free (৳0) → Starter (৳500) → Growth (৳2,000) → Enterprise
- Revenue projections through Month 24
- Unit economics and financial analysis

### New Sections in V3 Plan
- Market Analysis & Opportunity (Section 2)
- Competitive Landscape — Deep Analysis (Section 3)
- Business Model & Monetization (Section 6)
- New Strategic Modules A-H (Section 11)
- Team & Hiring Plan (Section 20)
- Financial Projections (Section 25)
- Investor Pitch Summary (Section 26)
