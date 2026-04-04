# PRISM Commerce V4 Diagram Index

Source policy: V4-only factual authority.
Gap policy: if a required detail is missing, document it first in V4 docs, then generate diagram.

## Batch A Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 01 | PRISM V4 - High-Level System Architecture Overview | 01-prism-v4-high-level-system-architecture-overview.mmd | V4 Section 8, 13, 31.2 | Complete |
| 02 | Turborepo Monorepo Workspace Structure | 02-turborepo-monorepo-workspace-structure.mmd | V4 Section 13, 21, 31.3 | Complete |
| 03 | NestJS Modular Monolith - Module Dependency Map | 03-nestjs-modular-monolith-module-dependency-map.mmd | V4 Section 8, 13, 31.4 | Complete |
| 04 | Docker Compose Service Topology | 04-docker-compose-service-topology.mmd | V4 Section 13, 18, 31.5 | Complete |
| 05 | Production Deployment Architecture (Hetzner VPS + Cloudflare CDN + External Services) | 05-production-deployment-architecture-hetzner-cloudflare-external-services.mmd | V4 Section 13, 18, 19, 31.6 | Complete |
| 06 | Service Communication Map (Protocol and Purpose per Connection) | 06-service-communication-map-protocol-purpose-per-connection.mmd | V4 Section 8.4, 12, 15, 31.7 | Complete |
| 06A | System Resilience and Scale Trigger Map | 06a-system-resilience-and-scale-trigger-map.mmd | V4 Section 13, 18, 22, 31.6-31.7 | Complete |
| 07 | CQRS Write Path - Command Handler to Event Store Flow | 07-cqrs-write-path-command-handler-to-event-store-flow.mmd | V4 Section 8.2, 14, 31.8 | Complete |
| 08 | CQRS Read Path - Query Handler to Materialized Views Flow | 08-cqrs-read-path-query-handler-to-materialized-views-flow.mmd | V4 Section 8.2, 14, 31.9 | Complete |
| 09 | Event Store - Aggregate Types and Event Projection Flow | 09-event-store-aggregate-types-and-event-projection-flow.mmd | V4 Section 8.2, 14, 31.10 | Complete |
| 10 | Order Saga - Distributed Transaction Steps (5 Steps + Compensating Actions) | 10-order-saga-distributed-transaction-steps-and-compensating-actions.mmd | V4 Section 8.2, 9.1, 31.11 | Complete |
| 11 | Saga Failure Recovery - Compensating Actions Flowchart | 11-saga-failure-recovery-compensating-actions-flowchart.mmd | V4 Section 8.2, 17, 31.12 | Complete |
| 11A | CQRS Event Replay and Read-Model Rebuild Workflow | 11a-cqrs-event-replay-and-read-model-rebuild-workflow.mmd | V4 Section 8.2, 14, 31.10-31.12 | Complete |

## Batch B Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 12 | Core Commerce ERD (users, vendors, products, product_variants, categories, orders, order_items, coupons, reviews, wishlists) | 12-core-commerce-erd.mmd | V4 Section 14, 32.2 | Complete |
| 13 | AI and Intelligence Tables ERD (ai_forecasts, forecast_accuracy, festival_calendar, category_velocity, weather_cache, synthetic_sales_seed, opportunity_alerts, bundle_suggestions, sahayak_conversations) | 13-ai-intelligence-erd.mmd | V4 Section 10, 14, 32.3 | Complete |
| 14 | Trust and Compliance Tables ERD (escrow_transactions, verification_levels, compliance_documents, buyer_protection_claims, brand_authorizations, counterfeit_reports, bangla_qr_codes, vat_records) | 14-trust-compliance-erd.mmd | V4 Section 11, 14, 19, 32.4 | Complete |
| 15 | Financial Tables ERD (wallets, wallet_transactions, vendor_disbursements, subscription_billing, commission_records, flash_sale_slots) | 15-financial-erd.mmd | V4 Section 6, 11, 14, 32.5 | Complete |
| 16 | Engagement Tables ERD (live_streams, short_form_videos, chat_messages, notifications, affiliate_tracking, referral_codes, academy_progress, pos_transactions) | 16-engagement-erd.mmd | V4 Section 9, 11, 14, 32.6 | Complete |
| 17 | System Tables ERD (audit_logs, event_store, api_keys, content_moderation_queue) | 17-system-erd.mmd | V4 Section 14, 17, 32.7 | Complete |
| 18 | Full Cross-Domain Database Relationship Map (all documented Section 14 tables) | 18-full-cross-domain-database-relationship-map.mmd | V4 Section 14, 32.8 | Complete |
| 18A | Business-Friendly Cross-Domain Data Map | 18a-business-friendly-cross-domain-data-map.mmd | V4 Section 14, 32.8 | Complete |
| 19 | Payment Gateway Integration Flow (bKash, Nagad, SSLCommerz, Bangla QR, Rocket) | 19-payment-gateway-integration-flow.mmd | V4 Section 12.2, 15, 32.9 | Complete |
| 20 | Escrow System - Double-Entry Ledger and Lifecycle Flow | 20-escrow-double-entry-ledger-lifecycle-flow.mmd | V4 Section 11, 12, 14, 32.10 | Complete |
| 21 | Vendor Disbursement Pipeline (Post-Escrow Release to bKash/Nagad Payout) | 21-vendor-disbursement-pipeline-flow.mmd | V4 Section 11, 14, 20, 32.11 | Complete |
| 22 | Bangla QR Payment Flow (In-Store POS and Online Checkout) | 22-bangla-qr-payment-flow-pos-online.mmd | V4 Section 12.2, 14, 32.12 | Complete |
| 22A | Payment and Escrow Business-Friendly Journey | 22a-payment-and-escrow-business-friendly-journey.mmd | V4 Section 11, 12.2, 32.9-32.12 | Complete |

## Batch C Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 23 | GBR ONNX Forecast Inference Dataflow | 23-gbr-onnx-forecast-inference-dataflow.mmd | V4 Section 10 Module 01, 14, 33.2 | Complete |
| 24 | AI Cold-Start Bootstrap and Data Quality Lifecycle | 24-ai-cold-start-bootstrap-data-quality-lifecycle.mmd | V4 Section 10 Cold-Start, 14, 33.3 | Complete |
| 25 | Smart Reorder Point Calculation and Alert Routing | 25-smart-reorder-point-calculation-and-alert-routing.mmd | V4 Section 10 Module 02, 9.2, 33.4 | Complete |
| 26 | Sales Velocity Ranking and Trend Classification Flow | 26-sales-velocity-ranking-and-trend-classification-flow.mmd | V4 Section 10 Module 03, 9.2, 33.5 | Complete |
| 27 | Coupon Optimization Advisor Decision Flow | 27-coupon-optimization-advisor-decision-flow.mmd | V4 Section 10 Module 04, 33.6 | Complete |
| 28 | Order Anomaly Detection Async Risk and Admin Triage Flow | 28-order-anomaly-detection-async-risk-triage-flow.mmd | V4 Section 10 Module 05, 9.4, 33.7 | Complete |
| 29 | Vendor Performance Score Computation and Tiering Flow | 29-vendor-performance-score-computation-and-tiering-flow.mmd | V4 Section 10 Module 06, 9.4, 33.8 | Complete |
| 30 | Cross-Vendor Category Emergence Hourly Pipeline | 30-cross-vendor-category-emergence-hourly-pipeline.mmd | V4 Section 10 Module 08, 17, 33.9 | Complete |
| 31 | Closed-Loop Forecast Feedback and Retraining Trigger Flow | 31-closed-loop-forecast-feedback-and-retraining-trigger-flow.mmd | V4 Section 10 Module 09, 33.10 | Complete |
| 32 | Weather-Aware Demand Signal Pipeline and Feature Injection | 32-weather-aware-demand-signal-pipeline-and-feature-injection.mmd | V4 Section 10 Module 10, 12.1, 33.11 | Complete |
| 33 | Agentic Sahayak V2 Tool-Calling Sequence | 33-agentic-sahayak-v2-tool-calling-sequence.mmd | V4 Section 8 Journey B, 10 Module 12, 33.12 | Complete |
| 34 | RAG Semantic Search, Opportunity, and Bundle Intelligence Flow | 34-rag-semantic-search-opportunity-and-bundle-intelligence-flow.mmd | V4 Section 10 Modules 13-15, 15, 33.13 | Complete |
| 34A | AI Intelligence Business-Friendly Cycle | 34a-ai-intelligence-business-friendly-cycle.mmd | V4 Section 10, 33.2-33.13 | Complete |

## Batch D Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 35 | RBAC Authorization Matrix and Access Control Flow | 35-rbac-authorization-matrix-and-access-control-flow.mmd | V4 Section 7, 17, 34 | Complete |
| 36 | JWT, Refresh Token, and MFA Lifecycle Sequence | 36-jwt-refresh-token-and-mfa-lifecycle-sequence.mmd | V4 Section 7, 15, 34 | Complete |
| 37 | Request Security Defense-in-Depth Pipeline | 37-request-security-defense-in-depth-pipeline.mmd | V4 Section 17, 15, 34 | Complete |
| 38 | PostgreSQL RLS Isolation and Cross-Vendor Privacy Flow | 38-postgresql-rls-isolation-and-cross-vendor-privacy-flow.mmd | V4 Section 7, 14, 34 | Complete |
| 39 | Payment Webhook Verification and Idempotent Processing Flow | 39-payment-webhook-verification-and-idempotent-processing-flow.mmd | V4 Section 12.2, 15, 34 | Complete |
| 40 | Escrow Authorization and Release Controls Flow | 40-escrow-authorization-and-release-controls-flow.mmd | V4 Section 11, 20, 34 | Complete |
| 40A | Security Controls Business-Friendly Journey | 40a-security-controls-business-friendly-journey.mmd | V4 Section 7, 11, 15, 34 | Complete |
| 41 | Order Lifecycle State Machine | 41-order-lifecycle-state-machine.mmd | V4 Section 9.1, 11, 34 | Complete |
| 42 | Order Creation to Confirmation Saga Sequence | 42-order-creation-to-confirmation-saga-sequence.mmd | V4 Section 8.2, 9.1, 34 | Complete |
| 43 | Delivery and COD Intelligence Decision Flow | 43-delivery-and-cod-intelligence-decision-flow.mmd | V4 Section 9.1, 10 Module 05, 34 | Complete |
| 44 | Vendor Fulfillment Workflow and Operational Updates | 44-vendor-fulfillment-workflow-and-operational-updates.mmd | V4 Section 9.2, 10 Modules 02 and 04, 34 | Complete |
| 45 | Order History and Analytics Query Flow | 45-order-history-and-analytics-query-flow.mmd | V4 Section 8.2, 9.1, 14, 34 | Complete |
| 45A | Order Journey Business-Friendly View | 45a-order-journey-business-friendly-view.mmd | V4 Section 9.1, 11, 34 | Complete |

## Batch E Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 46 | Next.js Routing and Localization Architecture | 46-nextjs-routing-and-localization-architecture.mmd | V4 Section 8.4, 16, 35 | Complete |
| 47 | Buyer Frontend Experience Composition Flow | 47-buyer-frontend-experience-composition-flow.mmd | V4 Section 8 Journey A, 16, 35 | Complete |
| 48 | Vendor Dashboard Frontend Architecture Flow | 48-vendor-dashboard-frontend-architecture-flow.mmd | V4 Section 8 Journey B, 9.2, 16, 35 | Complete |
| 49 | Admin Console Frontend Architecture Flow | 49-admin-console-frontend-architecture-flow.mmd | V4 Section 8 Journey C, 9.4, 16, 35 | Complete |
| 50 | Client State and Data Sync Architecture | 50-client-state-and-data-sync-architecture.mmd | V4 Section 8.4, 16, 35 | Complete |
| 51 | PWA, Mobile, and POS Experience Topology | 51-pwa-mobile-and-pos-experience-topology.mmd | V4 Section 8.4, 16, 35 | Complete |
| 51A | Frontend Experience Business-Friendly Map | 51a-frontend-experience-business-friendly-map.mmd | V4 Section 8.4, 16, 35 | Complete |
| 52 | WebSocket Event Architecture and Reconnect Flow | 52-websocket-event-architecture-and-reconnect-flow.mmd | V4 Section 8.4, 16, 35 | Complete |
| 53 | WhatsApp Dispatch Pipeline with Locale Fallback | 53-whatsapp-dispatch-pipeline-with-locale-fallback.mmd | V4 Section 8.4, 9.3, 16, 35 | Complete |
| 54 | Live Commerce Realtime Interaction Flow | 54-live-commerce-realtime-interaction-flow.mmd | V4 Section 9.3, 16, 35 | Complete |
| 55 | Short-Form Video Feed Ranking and Commerce Actions Flow | 55-short-form-video-feed-ranking-and-commerce-actions-flow.mmd | V4 Section 9.3, 10 Module 11, 35 | Complete |
| 56 | Unified Notification Center Orchestration Flow | 56-unified-notification-center-orchestration-flow.mmd | V4 Section 8.4, 16, 35 | Complete |
| 56A | Realtime and Notifications Business-Friendly Journey | 56a-realtime-and-notifications-business-friendly-journey.mmd | V4 Section 8.4, 9.3, 16, 35 | Complete |

## Batch F Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 57 | Vendor Onboarding and KYC Verification Workflow | 57-vendor-onboarding-and-kyc-verification-workflow.mmd | V4 Section 9.4, 15, 19, 36 | Complete |
| 58 | Vendor Subscription Billing and Tier Change Flow | 58-vendor-subscription-billing-and-tier-change-flow.mmd | V4 Section 6, 14, 36 | Complete |
| 59 | Vendor Catalog Publish and Moderation Pipeline | 59-vendor-catalog-publish-and-moderation-pipeline.mmd | V4 Section 9.1, 9.4, 14, 36 | Complete |
| 60 | Vendor Campaign Orchestration (Coupon and Flash Sale) | 60-vendor-campaign-orchestration-coupon-and-flash-sale-flow.mmd | V4 Section 9.1, 10 Module 04, 36 | Complete |
| 61 | Vendor Inventory Replenishment and Lead-Time Learning Flow | 61-vendor-inventory-replenishment-and-lead-time-learning-flow.mmd | V4 Section 9.2, 10 Module 02, 36 | Complete |
| 62 | Vendor Finance Reconciliation and Disbursement Control Flow | 62-vendor-finance-reconciliation-and-disbursement-control-flow.mmd | V4 Section 11, 14, 20, 36 | Complete |
| 63 | PRISM Academy Learning and Certification Progress Flow | 63-prism-academy-learning-and-certification-progress-flow.mmd | V4 Section 9.4, 14, 29, 36 | Complete |
| 63A | Vendor Operations Business-Friendly Journey | 63a-vendor-operations-business-friendly-journey.mmd | V4 Section 9.1, 9.2, 9.4, 36 | Complete |
| 64 | Facebook Shops Sync and Attribution Flow | 64-facebook-shops-sync-and-attribution-flow.mmd | V4 Section 11 Module C, 15, 36 | Complete |
| 65 | TikTok Shop Sync and Order Reconciliation Flow | 65-tiktok-shop-sync-and-order-reconciliation-flow.mmd | V4 Section 11 Module C, 15, 36 | Complete |
| 66 | YouTube Shopping and Live Product Overlay Integration Flow | 66-youtube-shopping-live-product-overlay-integration-flow.mmd | V4 Section 11 Modules A-C, 16, 36 | Complete |
| 67 | Influencer Affiliate and Referral Attribution Lifecycle | 67-influencer-affiliate-and-referral-attribution-lifecycle.mmd | V4 Section 9.4, 14, 29, 36 | Complete |
| 67A | Social Commerce Business-Friendly Attribution Map | 67a-social-commerce-business-friendly-attribution-map.mmd | V4 Section 9.3, 9.4, 11, 36 | Complete |

## Batch G Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 68 | CI/CD Build-Test-Deploy Pipeline Flow | 68-cicd-build-test-deploy-pipeline-flow.mmd | V4 Section 13, 24, 37 | Complete |
| 69 | Observability Signal Topology (Metrics, Logs, Traces, Errors) | 69-observability-signal-topology-metrics-logs-traces-errors.mmd | V4 Section 18, 13, 37 | Complete |
| 70 | Incident Detection, Alerting, and On-Call Response Workflow | 70-incident-detection-alerting-and-oncall-response-workflow.mmd | V4 Section 18, 22, 37 | Complete |
| 71 | Backup, Restore, and Disaster Recovery Flow | 71-backup-restore-and-disaster-recovery-flow.mmd | V4 Section 13, 18, 22, 37 | Complete |
| 71A | Reliability and Recovery Business-Friendly Journey | 71a-reliability-and-recovery-business-friendly-journey.mmd | V4 Section 18, 22, 37 | Complete |
| 72 | API Gateway Request Lifecycle and Version Governance Flow | 72-api-gateway-request-lifecycle-and-version-governance-flow.mmd | V4 Section 15, 17, 37 | Complete |
| 73 | Vendor Write API Idempotency and Consistency Flow | 73-vendor-write-api-idempotency-and-consistency-flow.mmd | V4 Section 8.2, 15, 17, 37 | Complete |
| 74 | Webhook Ingestion Reliability Pattern Flow | 74-webhook-ingestion-reliability-pattern-flow.mmd | V4 Section 12.2, 15, 17, 37 | Complete |
| 75 | API Key Lifecycle and Partner Access Control Flow | 75-api-key-lifecycle-and-partner-access-control-flow.mmd | V4 Section 14, 17, 37 | Complete |
| 75A | Partner API Trust and Access Business-Friendly Map | 75a-partner-api-trust-and-access-business-friendly-map.mmd | V4 Section 15, 17, 37 | Complete |

## Batch H Status (Implemented)

| ID | Title | File | Source Anchors | Status |
|---|---|---|---|---|
| 76 | Five-Tier Subscription Entitlement Decision Flow | 76-five-tier-subscription-entitlement-decision-flow.mmd | V4 Section 6, 28, 38 | Complete |
| 77 | Revenue Waterfall and Reserve Allocation Flow | 77-revenue-waterfall-and-reserve-allocation-flow.mmd | V4 Section 6, 26, 38 | Complete |
| 78 | Unit Economics and Break-Even Trajectory Model Flow | 78-unit-economics-and-break-even-trajectory-model-flow.mmd | V4 Section 26, 27, 28, 38 | Complete |
| 79 | Vendor Acquisition Funnel and Conversion Flywheel | 79-vendor-acquisition-funnel-and-conversion-flywheel.mmd | V4 Section 29.1, 38 | Complete |
| 80 | Buyer Acquisition and Retention Loop Flow | 80-buyer-acquisition-and-retention-loop-flow.mmd | V4 Section 29.2, 29.3, 38 | Complete |
| 81 | Geographic Expansion Rollout Strategy Flow | 81-geographic-expansion-rollout-strategy-flow.mmd | V4 Section 20, 29, 38 | Complete |
| 82 | Self-Funding Gates and External Funding Decision Tree | 82-self-funding-gates-and-external-funding-decision-tree.mmd | V4 Section 28.2, 27, 38 | Complete |
| 83 | Risk Register Monitoring and Mitigation Escalation Workflow | 83-risk-register-monitoring-and-mitigation-escalation-workflow.mmd | V4 Section 22, 38 | Complete |
| 84 | 15-Month Roadmap Dependency and Milestone Timeline | 84-fifteen-month-roadmap-dependency-and-milestone-timeline.mmd | V4 Section 20, 38 | Complete |
| 84A | Growth Roadmap Business-Friendly Journey | 84a-growth-roadmap-business-friendly-journey.mmd | V4 Section 20, 38 | Complete |

## Remaining Diagram Backlog

### Authentication and Security (35-40)
- Implemented (Batch D)

### Order Lifecycle (41-45)
- Implemented (Batch D)

### Frontend Architecture (46-51)
- Implemented (Batch E)

### Real-Time and Messaging (52-56)
- Implemented (Batch E)

### Vendor Flows (57-63)
- Implemented (Batch F)

### Social and Live Commerce (64-67)
- Implemented (Batch F)

### DevOps and Observability (68-71)
- Implemented (Batch G)

### API Design (72-75)
- Implemented (Batch G)

### Business and Growth (76-84)
- Implemented (Batch H)
