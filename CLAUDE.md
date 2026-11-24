# Portfolio rebuild — project notes

Hannah Einarsen's portfolio (heinarsen.com), moving off Webflow to a fresh design hosted on GitHub Pages.

## Status
- [x] Content copied from the old Webflow site into `content/` (10 case studies as Markdown, images, About, resume).
- [x] Location corrected to **Chicago, IL**.
- [ ] Hannah is collecting **new case studies in Figma** (one page per project) plus testimonials — read them via the Figma connector.
- [ ] **Waiting on Hannah for the design vibe/tone.** Do not start visual design until she gives it.
- [ ] Choose the final 4–6 case studies (senior UX portfolio: depth over volume).
- [ ] Build the site (plan: Astro, content from `content/`), deploy with GitHub Pages.
- [ ] Point heinarsen.com DNS to GitHub Pages, verify, then she cancels Webflow.

## Decisions
- Keep the domain heinarsen.com. Host on GitHub Pages (public repo).
- Complete design refresh — nothing from the old look needs to carry over.
- Old work, tentative: keep Whole Foods Supplier Data Catalog (2024); merge the two Wayfair "Add Products" studies; keep Activity Diagramming reframed as leadership; cut or condense the 2020 Ticketmaster set, Spotify Wrapped and OEO UI Kit. Final call after seeing the new work.
- The old Webflow site is still live and untouched; it stays up until the new site is live.

## Case study structure (for writing up new work)
Basics (company, role, team, timeline, scope) → Problem (who, why it mattered) → Process (research, decisions, tradeoffs, collaboration) → Visuals → Impact (metrics first) → NDA notes.

## Repo layout
- `content/projects/*.md` — case studies (frontmatter: order, title, client, year, role, thumb)
- `content/about.md`, `content/images/`, `content/files/` (resume, logo, favicon)
- `webflow-archive/` — raw HTML/CSS of the old site, reference only
