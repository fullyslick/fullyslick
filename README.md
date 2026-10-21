# Aleksandar Rashkov

I’m a Senior Full Stack Engineer with 10+ years of web development, mostly in React, TypeScript and Node.js. I work across the whole stack, from the Postgres schema to the UI.

I spent five years on e-commerce. I shipped storefronts on 8+ projects for brands like British American Tobacco, Luxottica, Schleich and Hunter Boots. Later I led a custom Salesforce PWA Kit storefront.

I have also built products. I designed a service wizard for a B2B device management SaaS. I took an AI readiness audit platform from a 4-day proof of concept to a client pilot. And I built bullionpricetracker.com alone, live in two weeks.

I build with Claude Code every day. I write the specs, the guardrails, and my own skills. Claude writes code fast. I make the decisions.

## Stack: 
React, Next.js, React Router 7, Node.js, PostgreSQL, Supabase. Deployed on Vercel, Cloudflare Workers and Fly.io.

AI-assisted development: Claude Code, custom Skills, Hooks, MCP integrations

## A few things I've built

**[Bullion Price Tracker](https://bullionpricetracker.com)** A full-stack site that charts the buy and sell price history of investment gold and silver coins against spot, so you can see the premium paid and the discount taken over time. A scheduled n8n workflow (self-hosted on Fly.io) fetches spot prices, calculates premiums and writes idempotently to Supabase Postgres. A React Router 7 SSR app on Cloudflare Workers serves the charts. Dealer prices are calibrated synthetic data, clearly labelled on the site.

**[React Anti-Patterns Review](https://github.com/fullyslick/react-antipatterns-review)**
A custom Claude Code skill that reviews React/JSX/TSX code for anti-patterns (Effects, state, hooks, memo, keys, mutation) and outputs a prioritized fix plan without touching the code.

**[AWS S3 File Manager](https://github.com/fullyslick/aws-file-manager)** ([live demo](https://aws-s3-bucket-viewer.web.app/))
React/TypeScript app for browsing, creating, and deleting files in an AWS S3 bucket through a filesystem-style UI.

**[Expensely](https://github.com/fullyslick/expense-requests)** A full-stack expense-request app with a manager and finance approval workflow, built so every rule holds against a direct API call, not just the UI. The server validates conditional form fields with a shared Zod schema, picks the approver, enforces owner and approver checks, and reads request bodies through an allowlist to block mass assignment. Status is derived from an event log, never stored. Express and React/TypeScript in an npm workspaces monorepo, covered by 209 tests.

**[Node Migration & Seeding CLI](https://github.com/fullyslick/node-migrate-scripts)**
A Node.js CLI tool for versioned schema migrations and seeding, supporting migrate up, migrate down, and seed commands.

## Get in touch

[LinkedIn](https://www.linkedin.com/in/aleksandar-rashkov/)
