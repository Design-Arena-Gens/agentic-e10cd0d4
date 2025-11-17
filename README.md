# Agentic Greeting

A minimal Next.js 14 application that renders a warm “hi” with a short welcome message.

## Getting Started

### Prerequisites

- Node.js 18+
- npm 9+

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

App runs at `http://localhost:3000`.

### Production Build

```bash
npm run build
npm start
```

## Deployment

The project is configured for Vercel. Latest deployment: `https://agentic-e10cd0d4.vercel.app`.

## Project Structure

```
├── app/
│   ├── globals.css      # Global styles
│   ├── layout.tsx       # Root layout with metadata
│   └── page.tsx         # Landing page with greeting
├── next.config.mjs      # Next.js configuration
├── package.json         # Scripts and dependencies
├── tsconfig.json        # TypeScript configuration
└── README.md
```
