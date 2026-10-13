# eSports Hub

A community-driven platform helping gamers discover esports events, games, communities, teams, players, and news.

## Product direction
- Primary audiences: players and teams; also supports viewers, organizers, and admins.
- Anchor feature: event discovery.
- MVP: public browsing, accounts for restricted actions, team membership requests, event submissions and admin approval.
- Deferred: chat, calls, rankings, and automated tournament brackets.
- Design: premium, clean, cyan/white/gold, modern sans-serif, responsive desktop and mobile.
- Language: English; geographic scope: global.

## Planned stack
- Next.js App Router, TypeScript, Tailwind CSS
- Supabase/PostgreSQL and Supabase Auth (planned; not part of the first frontend task)
- Vercel deployment (planned)

Do not introduce a different framework, database, authentication provider, or UI library without Cid's approval.

## Current status
The repository was initially empty. Sprint 1 starts with the project foundation and frontend design. Database work is planned for a later work session.

See `AGENTS.md`, `docs/SPRINT_1.md`, and `docs/DECISIONS.md`.

## Requirements
Install current LTS Node.js and Git, then verify:
```bash
node --version
npm --version
git --version
```

## Initialize the app
From the repository root:
```bash
npx create-next-app@latest . --typescript --tailwind --eslint --app --src-dir --import-alias "@/*"
```
If the CLI refuses to run because documentation files already exist, do not delete them. Initialize in a temporary sibling directory and copy the generated app files into this repository, preserving the existing docs and Git history.

Then run:
```bash
npm run dev
```
Open the local URL printed by Next.js (usually `http://localhost:3000`).

## Environment variables
The first UI task uses mock data and needs no credentials. When Supabase integration is approved, copy `.env.example` to `.env.local` and add local values. Never commit `.env.local`, service-role keys, or real credentials.

## Collaboration rules
1. Use feature branches and reviewable pull requests; don't commit directly to `main` unless Cid requests it.
2. Keep the first task frontend-only; use mock data.
3. Build responsive layouts and meaningful empty/loading/error states.
4. Explain changes, list files changed, and report actual lint/build results.
5. Ask before adding dependencies or changing product scope.
6. Never expose secrets in source code.
