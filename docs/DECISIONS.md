# Product Decisions and Open Questions

Change a status only when Cid confirms the decision.

## Confirmed
- Product name: eSports Hub.
- Players and teams are the primary audiences; viewers, organizers, and admins are also supported.
- Event discovery is the anchor feature.
- English; global scope.
- Premium, clean cyan/white/gold design, modern sans-serif, responsive desktop/mobile.
- Planned stack: Next.js, TypeScript, Tailwind CSS, Supabase/PostgreSQL, Supabase Auth, Vercel.
- Visitors can browse events, games, communities, teams, players, and news.
- Accounts are required for restricted actions.
- Organizers submit events; admins approve before public listing.
- Captains can create teams; players can request membership; captains manage requests.
- Game suggestions require moderation before appearing in the public catalog.
- MVP community scope is discovery; internal posts/comments/chat are deferred.
- Calls are out of scope. Rankings, automated brackets, and chat are deferred.
- Initial frontend task uses mock data; database is a separate workstream.

## Open — Cid to decide
1. Must teams be admin-approved before public listing?
2. Are event registrations automatic, organizer-approved, or configurable per event?
3. Is match-score reporting MVP or deferred with brackets?
4. Which event formats and registration limits are required at launch?
5. Which player profile fields are public by default?
6. Which actions need admin review beyond event approval and game moderation?
7. What happens to registrations/memberships if a team, event, or user is suspended/deleted?

Do not silently turn an open question into a permanent requirement. Document temporary assumptions and flag them for review.
