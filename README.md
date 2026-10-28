# LLM Observability Platform — Node.js Packages

This monorepo contains the Node.js / TypeScript microservices, libraries, and frontend applications for the LLM Observability & Evaluation Platform.

## Live Demo & Infrastructure Notice

> ⚠️ **Frontend Demo Preview Only**:
> - **Live UI Preview (Firebase CDN)**: [https://llm-obs-web-app-9664.web.app](https://llm-obs-web-app-9664.web.app)
> - **Direct Cloud Run Service**: [https://web-app-prod-4aq3kyjfra-el.a.run.app](https://web-app-prod-4aq3kyjfra-el.a.run.app)
>
> **Notice**: The hosted links provide an interactive frontend preview. A complete production deployment requires provisioning the self-hosted backend infrastructure services (ClickHouse, AlloyDB/PostgreSQL, Redis, Kafka, and Temporal) located in [`llm-obs-infra`](file:///home/btpl-lap-22/live/llm-obs-infra).

## Sub-Packages
- [`web-app/`](file:///home/btpl-lap-22/live/llm-obs-node-packages/web-app) — Next.js 15 App Router Frontend (`@observability/web-app`)
- [`auth/`](file:///home/btpl-lap-22/live/llm-obs-node-packages/auth) — Authentication & Authorization Microservice
- [`shared-infra/`](file:///home/btpl-lap-22/live/llm-obs-node-packages/shared-infra) — Centralized Infrastructure Adapters & Telemetry Clients
- [`design-tokens/`](file:///home/btpl-lap-22/live/llm-obs-node-packages/design-tokens) — Observability Design System Tokens
- [`notification/`](file:///home/btpl-lap-22/live/llm-obs-node-packages/notification) — Notification & Alerting Microservice
- [`payment/`](file:///home/btpl-lap-22/live/llm-obs-node-packages/payment) — Subscription & Usage Billing Microservice
