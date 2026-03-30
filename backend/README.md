# Backend

This directory contains the backend application.

## Getting Started

### Prerequisites

- Node.js 18+ (or Python 3.11+ depending on the chosen stack)
- npm / yarn / pnpm (for Node.js)
- Docker (optional, for containerized development)

### Installation

```bash
cd backend
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Test

```bash
npm test
```

## Structure

```
backend/
├── src/
│   ├── routes/        # API route handlers
│   ├── controllers/   # Business logic
│   ├── services/      # External service integrations
│   ├── models/        # Data models / database schemas
│   ├── middleware/    # Express/Fastify middleware
│   ├── utils/         # Utility functions
│   └── types/         # TypeScript type definitions
├── tests/             # Test files
└── scripts/           # Utility scripts
```

## Environment Variables

Copy `.env.example` to `.env` and fill in the required values:

```bash
cp .env.example .env
```

## API Documentation

API endpoints follow RESTful conventions. See `docs/api.md` for full documentation.
