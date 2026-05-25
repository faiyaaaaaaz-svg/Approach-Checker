# AI Quality Review Platform Demo

This is a sanitized portfolio demo of an AI-powered support QA and audit insights platform.

## What this demo shows

- Audit dashboard with review approach, client sentiment, and resolution status tracking
- Run Audit workflow with mock conversation fetching and mock AI output
- Results table with preview, dispute, and verdict editing flows
- Admin control center with prompt management, role permissions, disputes, calibration snippets, mappings, teams, activity logs, and API vault UI
- Calibration snippet concept: approved learnings can be appended separately to future audit instructions without modifying the original prompt

## Privacy and data safety

This repository is intentionally sanitized for portfolio review.

- No real company data
- No real client conversations
- No real employee emails
- No production Supabase project
- No API keys
- No environment variables required
- No live Support Inbox, AI model, or database calls

All data is fictional and generated from local mock data in `lib/demoData.js`.

## Demo mode

The app uses a local mock Supabase client in `lib/supabase.js` and mock API routes under `app/api/**`.
This lets the UI run without connecting to a private database or external tools.

## Run locally

```bash
npm install
npm run dev
```

Then open:

```text
http://localhost:3000
```

## Deploying to Vercel

This demo version does not require environment variables. You can deploy it directly from a personal GitHub repository.

## Important note

This demo is a public-safe representation of a support QA platform concept. It is not connected to any production company system.
