# PRISM Commerce
## Predictive Retail Intelligence & Stock Management

> This repository is the documentation hub for the PRISM Commerce capstone. The full specification is in the project plan files below; this README is the fastest way to understand the idea, the features, and how the parts fit together.

PRISM Commerce is a Bangladesh-focused commerce platform that combines a multi-vendor storefront with AI-driven inventory planning, real-time order tracking, and Bangla-first notifications. The goal is simple: help small and mid-sized sellers know what to stock, when to restock, how to price surplus items, and how to fulfill orders without guesswork.

If you only remember one sentence, remember this: PRISM Commerce turns sales history, festival timing, weather, and platform-wide demand signals into practical actions for vendors.

## Why it exists

- Overstocking ties up cash.
- Stockouts during Eid, Puja, and other peaks lose sales.
- English-only tools exclude many vendors.
- Most small merchants already use phones, WhatsApp, and mobile money, so the system must fit those habits.

## What the platform covers

| Area | What it includes | Why it matters |
| --- | --- | --- |
| Commerce | Multi-vendor catalog, cart, coupons, checkout, payments, reviews, recommendations, wishlist, real-time order tracking | End-to-end shopping experience for buyers |
| Inventory | Variant-level stock, reorder points, low-stock alerts, reports, learned lead times | Prevents overbuying and stockouts |
| Intelligence | Demand forecasting, velocity ranking, coupon optimization, anomaly detection, vendor scoring, scenario planning, weather-aware signals, feedback retraining | Makes stock and pricing decisions data-driven |
| Operations | Admin approval, support handling, delivery assignment, billing, invoices, platform analytics | Keeps the marketplace organized |
| Localization | English + Bangla UI, Bangla WhatsApp templates, localized numbers and currency formatting | Matches the way vendors actually work |
| Platform | PWA shell, offline dashboard, realtime updates, free-tier deployment strategy | Keeps the system usable on low-cost infrastructure |

## Who uses it

| Role | What they do |
| --- | --- |
| Super Admin | Approves vendors, manages users and categories, reviews anomalies, and monitors platform-wide performance. |
| Vendor | Lists products, tracks stock, reads forecasts, receives alerts, plans scenarios, and manages coupons and analytics. |
| Buyer | Browses products, adds items to cart, pays, tracks orders, and leaves reviews. |
| Support & Billing | Handles tickets, invoices, payment records, disputes, and reports. |
| Delivery Partner | Sees assigned deliveries and updates pickup and delivery status from a lightweight mobile view. |

## How it works

1. A vendor lists products and enters initial sales history if the platform is still learning.
2. Buyers place orders and pay through bKash, Nagad, or SSLCommerz.
3. The backend combines sales history, festival timing, weather, and cross-vendor category trends.
4. The ONNX forecasting model predicts demand for 7, 14, and 30 days ahead.
5. The reorder engine turns that forecast into a stock threshold and sends alerts through WhatsApp, web push, or in-app notifications.
6. A weekly feedback loop compares predicted and actual sales and improves the model over time.

In practice, this means a fabric vendor can get a Bangla WhatsApp alert before Eid saying a product will run out in 9 days, along with a reorder suggestion based on real demand patterns instead of a fixed threshold.

## Why the AI matters

PRISM does not rely on one rule. It combines three kinds of learning.

| Layer | What it means | Example |
| --- | --- | --- |
| Individual learning | Each product gets its own forecast from its own history. | A specific fabric SKU gets a 7/14/30-day demand estimate. |
| Collective learning | The platform learns from anonymized category behavior across vendors. | If the whole fabric category heats up before Eid, every fabric vendor benefits. |
| Environmental learning | Festivals and weather change demand, so the model adjusts for them. | Rain gear rises during monsoon; clothing surges before Eid. |

The forecasting model uses 13 engineered features, including recent sales, rolling trends, festival proximity, weather, and platform-wide category velocity. The model runs in-process with ONNX Runtime so inference stays fast and cheap.

### Intelligence modules

| Module | What it does |
| --- | --- |
| Demand forecast | Predicts 7, 14, and 30-day demand per product. |
| Reorder point calculator | Converts the forecast into a practical restock threshold. |
| Sales velocity ranker | Finds products that are gaining or losing momentum. |
| Coupon optimizer | Suggests the smallest discount needed to clear surplus stock. |
| Anomaly detector | Flags suspicious orders for review. |
| Vendor performance score | Measures fulfillment, rating, response speed, delivery time, and disputes. |
| WhatsApp notification engine | Sends alerts in the user's preferred language. |
| Cross-vendor category emergence | Uses aggregate platform activity to improve forecasts without exposing private data. |
| Closed-loop feedback | Retrains the model when forecast error stays high. |
| What-if scenario planner | Lets vendors test changes like festival timing, price shifts, or weather. |
| Weather-aware demand engine | Adjusts forecasts for heat, rain, and monsoon patterns. |

## Bangladesh-first features

- WhatsApp Business Cloud API is used because vendors already communicate there.
- bKash, Nagad, and SSLCommerz support the payment habits of Bangladesh shoppers.
- The festival calendar includes Eid-ul-Fitr, Eid-ul-Adha, Durga Puja, Pohela Boishakh, Victory Day, Independence Day, and Ramadan.
- Bangla localization covers the UI, notifications, onboarding flow, number formatting, and invoice text.
- The PWA design keeps the dashboard useful on low-end phones and unstable connections.
- OpenWeatherMap adds weather context so the system can react to monsoon and heat-driven demand shifts.

## Architecture at a glance

```text
Buyers / Vendors / Delivery Partners
	  |
	  v
  Next.js 14 frontend and PWA
	  |
	  v
  NestJS API and AI modules
	  |
	  +--> Supabase (Postgres, Auth, Realtime, Storage)
	  +--> Upstash Redis (cached forecasts, category velocity, weather data)
	  +--> External services (WhatsApp, bKash, Nagad, SSLCommerz, OpenWeatherMap)
	  |
	  v
  ONNX demand forecast engine
```

### Core stack

| Layer | Main tools |
| --- | --- |
| Frontend | Next.js 14, Tailwind CSS, shadcn/ui, next-intl, Recharts, Nivo, Zustand, next-pwa |
| Backend | NestJS, TypeScript, Prisma, @nestjs/schedule |
| Data | Supabase PostgreSQL, Supabase Auth, Supabase Realtime, Supabase Storage, Upstash Redis |
| AI | scikit-learn, skl2onnx, onnxruntime-node |
| Integrations | WhatsApp Business Cloud API, bKash, Nagad, SSLCommerz, OpenWeatherMap |
| Delivery and ops | Delivery partner workflows, invoices, support tools, platform analytics |
| Tooling | Turborepo, Jest, Playwright, Swagger, Winston, Sentry, GitHub Actions |
| Cost target | BDT 0.00/month on free tiers |

## Security and trust

- Role-based access control limits what each role can see and do.
- JWT access tokens are short-lived and refresh tokens rotate.
- Supabase Row-Level Security isolates vendor data.
- Payment callbacks are verified server-side, not trusted from the client.
- Audit logs are append-only for traceability.
- Rate limiting and strict content security rules protect the platform from abuse.

## Accessibility and inclusivity

- The target is WCAG 2.1 AA.
- Keyboard navigation, screen-reader support, and high-contrast UI are part of the plan.
- Touch targets are designed for mobile users and low-literacy users.
- Bangla onboarding and plain-language tooltips explain forecasts and alerts.
- The goal is to make the system usable by real vendors, not only by technical users.

## Roadmap

- Week 1: foundation, auth, schema, locale routing, and PWA shell.
- Week 2: product catalog, cart, checkout, and WhatsApp templates.
- Week 3: order lifecycle, inventory tracking, and delivery partner flow.
- Week 4: ONNX forecasting, reorder alerts, and velocity ranking.
- Week 5: analytics, weather awareness, coupon optimization, anomaly detection, vendor scoring, and scenario planning.
- Week 6: security hardening, accessibility audit, tests, and deployment.

## Documents in this repo

- [Project plan v2.0](PRISM_Commerce_ProjectPlan_v2.0.0.md) - the full, upgraded specification.
- [Project plan v1.0](PRISM_Commerce_ProjectPlan-v1.0.0.md) - the original plan.
- [Walkthrough](walkthrough.md) - a summary of what changed in v2.0.

## Mini glossary

| Term | Plain English meaning |
| --- | --- |
| GBR | A machine learning model that predicts a number by combining many decision trees. |
| ONNX | A portable model format that lets Python-trained AI run inside JavaScript. |
| ROP | Reorder point - the stock level where the system says "buy more now". |
| PWA | A web app that behaves like an installable phone app and can work offline. |
| RLS | Row-Level Security - database rules that stop users from seeing each other's data. |
| Category velocity | How fast a product category is selling across the whole platform. |
| Data quality score | A 0-1 score showing how much of the forecast comes from real data versus seed data. |
| CRON job | A scheduled background task that runs automatically on a timer. |

## Bottom line

PRISM Commerce is not just a storefront. It is a full commerce system with an embedded intelligence layer that learns from each product, the whole marketplace, and the environment around it. The result is a platform that can explain what is happening now, what is likely to happen next, and what a vendor should do about it.
