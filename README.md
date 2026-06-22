# MedXpreneur SaaS Platform

> Core Business Management System | Built with Claude Code | Deployed to GitHub

---

## Project Overview

MedXpreneur SaaS is the core business management platform for healthcare entrepreneurs. This is the main umbrella platform connecting all MedXpreneur products and services.

---

## Repository Structure

```
medxpreneur-saas/
|-- src/
|   |-- api/
|   |   |-- v1/
|   |   `-- v2/
|   |-- components/
|   |   |-- common/
|   |   |-- dashboard/
|   |   |-- auth/
|   |   `-- layout/
|   |-- pages/
|   |   |-- auth/
|   |   |-- dashboard/
|   |   |-- admin/
|   |   `-- settings/
|   |-- services/
|   |   |-- auth/
|   |   |-- user/
|   |   |-- billing/
|   |   `-- notifications/
|   |-- models/
|   |-- middleware/
|   |-- utils/
|   |-- hooks/
|   |-- context/
|   |-- store/
|   |   |-- slices/
|   |   `-- actions/
|   |-- styles/
|   |   |-- themes/
|   |   `-- globals/
|   `-- types/
|
|-- backend/
|   |-- controllers/
|   |-- routes/
|   |-- models/
|   |-- services/
|   |-- middleware/
|   `-- config/
|
|-- database/
|   |-- migrations/
|   |-- seeds/
|   `-- schemas/
|
|-- tests/
|   |-- unit/
|   |-- integration/
|   |-- e2e/
|   `-- fixtures/
|
|-- docs/
|   |-- api/
|   |-- architecture/
|   |-- guides/
|   `-- deployment/
|
|-- config/
|   |-- environments/
|   |-- deployment/
|   `-- security/
|
|-- scripts/
|   |-- build/
|   |-- deploy/
|   `-- setup/
|
|-- public/
|   |-- images/
|   |-- icons/
|   `-- fonts/
|
|-- assets/
|   |-- logos/
|   |-- mockups/
|   `-- branding/
|
|-- .github/
|   |-- workflows/
|   |-- ISSUE_TEMPLATE/
|   `-- PULL_REQUEST_TEMPLATE/
|
|-- .env.example
|-- .gitignore
|-- .eslintrc.js
|-- .prettierrc
|-- package.json
|-- tsconfig.json
|-- docker-compose.yml
|-- Dockerfile
`-- README.md
```

---

## Architecture

This project follows a clean architecture pattern:

- Frontend: React and Next.js with TypeScript
- Backend: Node.js and Express or Python FastAPI
- Database: PostgreSQL (primary) and Redis (cache)
- Auth: JWT and OAuth2
- Deployment: Docker and CI/CD via GitHub Actions

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- PostgreSQL or MongoDB
- Docker (optional)

### Installation

```bash
git clone https://github.com/medxpreneur-netizen/medxpreneur-saas.git
cd medxpreneur-saas
npm install
cp .env.example .env
npm run dev
```

---

## Related Repositories

| Repository | Description |
|-----------|-------------|
| [medxpreneur-booking-saas](https://github.com/medxpreneur-netizen/medxpreneur-booking-saas) | Booking and Scheduling SaaS |
| [medxpreneur-emr-saas](https://github.com/medxpreneur-netizen/medxpreneur-emr-saas) | EMR and EHR SaaS Platform |
| [medxpreneur-plugins](https://github.com/medxpreneur-netizen/medxpreneur-plugins) | Plugins and Extensions |
| [medxpreneur-mobile](https://github.com/medxpreneur-netizen/medxpreneur-mobile) | Mobile Application |

---

MedXpreneur Team | Built with Claude Code on GitHub
