# Troophunter - Dev8X

This repository implements a Monorepo and Turborepo architecture containing the **Dev8X** frontend application and shared component library.

## Project Structure

```
├── cdns/
│   └── dev8x/             # Cloudflare Workers & R2 CDN deployment
├── content/
│   └── dev8x/             # Platform data and content configurations
├── microfrontend/
│   └── dev8x/             # Next.js 14 Web Application
└── packages/
    └── components/        # Shared UI Component Library (@repo/components)
```

## Getting Started

### Prerequisites

- Node.js >= 18.0.0
- npm >= 10.0.0

### Installation

```bash
npm install
```

### Development

Run the Dev8X application locally:

```bash
npm run dev
# or
npm run dev:dev8x
```

### Build

```bash
npm run build
# or
npm run build:dev8x
```
