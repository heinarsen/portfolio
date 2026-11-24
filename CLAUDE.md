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

## Private notes
Confidential source material, ownership details and case-study notes live in the PRIVATE repo `heinarsen/portfolio-notes`. Read its CLAUDE.md before writing case studies. Never copy confidential content into this public repo.

## New work (Figma file "Portfolio 2026", in Hannah's Drafts, Free plan)
Pages: Resume & Testimonials · Task Management (Authoring & Template Building, Daily Work List, Detail Page Standardization, Feedback / UXR Contributions & Stats, Notifications & Escalations, Photo Capture, Store Desktop / Store Walks / UXR) · Supplier Portal · Location Management · Misc (AI in Handheld Tools, GEM Design Library Contributions, SCO at Whole Foods Market).
As of Nov 24, 2026, every project page is EMPTY (titles only). The "Resume & Testimonials" page holds one resume, positioned as "Wellness Operations Specialist"; there are no testimonials yet. Older resumes on the trash page list "Senior UX Designer, WFM + Amazon".
Only the Figma work is WFM/Amazon. The old-site work is Wayfair/Ticketmaster etc.
Projects named on her resumes but missing from the outline: Quality Standards labeling/search (300+ ingredient ban list, app + web), and the assortment planning tool / product data management tool.
Free plan means a low monthly Figma connector limit (about 20 calls). Prefer PDF/PNG exports dragged into chat, and use the connector sparingly.

Proposed portfolio structure (pending Hannah's review):
1. Flagship: **Task Management** as ONE deep case study (platform story). Go deep on 2–3 initiatives; the rest become a scope overview. UXR/store walks feed the research section, and stats feed impact.
2. **Supplier Portal**, merged with the existing Supplier Data Catalog (2024) study.
3. **Location Management**.
4. **SCO at Whole Foods** or **AI in Handheld Tools**, whichever has the stronger story and impact.
- "Leadership & craft" section: GEM Design Library, Activity Diagramming (Wayfair), UXR contributions.
- "Earlier work": one merged Wayfair card. Cut the Ticketmaster set, Spotify Wrapped and OEO.

## Case study structure (for writing up new work)
Basics (company, role, team, timeline, scope) → Problem (who, why it mattered) → Process (research, decisions, tradeoffs, collaboration) → Visuals → Impact (metrics first) → NDA notes.

## Repo layout
- `content/projects/*.md` — case studies (frontmatter: order, title, client, year, role, thumb)
- `content/about.md`, `content/images/`, `content/files/` (resume, logo, favicon)
- `webflow-archive/` — raw HTML/CSS of the old site, reference only
