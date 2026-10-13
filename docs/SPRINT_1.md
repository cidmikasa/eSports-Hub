# Sprint 1 — Project Foundation and Frontend Design

**Status:** Ready to start  
**Owner:** Cid  
**Goal:** Establish a clean Next.js foundation and approve the first visual direction before database work begins.

## A — Cid: repository foundation
- [ ] Open repository in VS Code and verify Git remote.
- [ ] Initialize Next.js with TypeScript, Tailwind, ESLint, App Router, `src/`, and `@/*`.
- [ ] Preserve this documentation and Git history.
- [ ] Confirm app runs locally.
- [ ] Review Jasmine's changes before merge.

**Acceptance:** a fresh clone can be set up from README and the app starts locally.

## B — Jasmine: frontend design
Implement with mock data only:
1. Design tokens and base styles: cyan/white/gold palette, typography, spacing, borders, focus styles and containers.
2. Shared shell: responsive navigation, brand/wordmark placeholder (do not invent a final logo), footer.
3. Homepage: clear value proposition, primary CTA, upcoming/featured events, browse-by-game/community entry points.
4. Events directory: event cards, sensible search/filter UI, game, format, date, online/offline status, empty/no-results state.
5. Event Details: summary, organizer, schedule, format, location/online status, registration deadline, CTA and clear status states.
6. Responsive/accessibility pass: mobile/tablet/desktop, semantic headings, keyboard focus and labels.

### Acceptance criteria
- [ ] Consistent reusable visual system across pages.
- [ ] Homepage, Events directory, and Event Details are navigable.
- [ ] Responsive at mobile, tablet, and desktop widths.
- [ ] Mock data is isolated from components.
- [ ] No dead controls that falsely claim to work.
- [ ] No database or authentication code.
- [ ] File-change summary and real lint/build results provided.

## C — Alicia (ChatGPT): project management
- [ ] Track scope and decisions.
- [ ] Review design/handoff against acceptance criteria.
- [ ] Coordinate later frontend/database contracts.
- [ ] Keep unresolved product questions in `DECISIONS.md`.

## D — Alicia the 2nd (DeepSeek): database
Database design begins in a later work session. Do not create migrations or configure Supabase as part of the initial frontend task.

## Review gate
Cid reviews design direction and repository structure before expanding to Games, Communities, Teams, Players, and News.
