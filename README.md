# Vanessa Tirado for 22nd Ward (exploratory)

An internal brainstorm site that visualizes what a 2027 campaign for Chicago's 22nd Ward
(Little Village) alderperson could look like for Vanessa Tirado, co-founder and director of the
Latina Sweat Project. Nothing here is a declaration of candidacy. The site ships with
`<meta name="robots" content="noindex, nofollow">`.

Live: https://awaisqazi.github.io/vanessa-22nd-ward/

## Stack

Astro 6, vanilla CSS, a tiny client-side EN/ES toggle (`src/i18n/`), one motion script
(`src/scripts/motion.js`). Deploys to GitHub Pages from `main` via `.github/workflows/deploy.yml`.

```bash
npm install
npm run dev      # http://localhost:4321/vanessa-22nd-ward/
npm run build
```

## Pages

| Route | What it is |
|---|---|
| `/` | Hero, "what we already built", bio teaser, seven planks, the choice-not-handoff banner, key dates |
| `/meet/` | Biography and receipts |
| `/platform/` | Seven planks with mechanisms, contrasts, first 100 days, slogans |
| `/race/` | Internal analysis: field, precinct zones, path to a runoff, issue landscape |
| `/plan/` | Calendar to April 6, field math, budget, endorsement map, guardrails |
| `/join/` | Petition sprint, roles, prototype signup form |

## Research

The site is built from five memos in `docs/research/` (kept out of the public repo; see
`.gitignore`): race dynamics, platform, lessons from the BSL for Congress site, Latina Sweat
Project assets, and the candidate profile plus operational playbook.

## Before anything goes public

- Confirm Vanessa's title with the LSP board (the LSP site says both "Director" and "Co-Founder & Director").
- Confirm her address is inside the post-2022 22nd Ward boundary since at least Feb 23, 2026.
- LSP is a 501(c)(3). Photos in `public/images/lsp/` are used here as biography only; replace with
  campaign-owned photography and get written permission or remove before any public launch.
- Verify every number against the source list in the research memos.
- Add "Paid for by" and ISBE disclosure lines once a committee exists.
