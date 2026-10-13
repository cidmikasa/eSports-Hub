# Instructions for AI Coding Assistants and Contributors

## Authority
Cid is project owner and final technical authority. Follow `README.md`, `docs/SPRINT_1.md`, and `docs/DECISIONS.md`. If requirements conflict or are ambiguous, ask instead of inventing product behavior.

## Current assignment: frontend foundation
Implement the design system, responsive shared shell, homepage, Events directory, and Event Details page using mock data.

### Design direction
- Premium, clean esports community platform.
- Cyan, white, and gold palette; modern sans-serif typography.
- Strong hierarchy, restrained effects, readable contrast.
- Desktop and mobile are equally important.
- Prefer reusable components over one-off styling.

### Boundaries
- Next.js App Router, TypeScript, Tailwind CSS.
- Use mock data only for this task.
- Do not configure Supabase, write SQL migrations, implement authentication, or add database access yet.
- Do not add chat, calls, brackets, rankings, or other deferred features.
- Ask Cid before adding UI libraries, animation dependencies, or changing scope.
- Do not overwrite documentation or unrelated files.

### Handoff checklist
1. Summarize implementation and user experience.
2. List files created/changed.
3. Explain dependencies added and why.
4. Report exact lint/build commands run and actual results.
5. List assumptions, limitations, and decisions needed from Cid.
6. Keep work on a feature branch or provide a reviewable diff; do not silently merge to `main`.

### Quality bar
- Use meaningful TypeScript; avoid `any` unless justified.
- Use semantic HTML, keyboard focus states, accessible labels, and sufficient contrast.
- Do not make unfinished controls pretend to work.
- Separate mock data from components for later integration.
- Never claim tests passed unless they were actually run.
