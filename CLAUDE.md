# justin-dass-site

Personal website for Justin Dass. Live at https://www.justindass.com (justindass.com redirects to www). Also served at https://justin-dass-site.vercel.app.

## How it works

1. Single static page: `index.html` (HTML, CSS and vanilla JS inline). No build step, no framework, no package.json.
2. Hosting: Vercel project `justin-dass-site` (team "Justin D Dass Global Revenue Leader", Hobby plan), connected to this GitHub repo. Every push to `main` deploys to production in about 30 seconds.
3. Domain: justindass.com, bought on Vercel Nov 18, 2026, auto-renews yearly.
4. `.vercelignore` keeps `CLAUDE.md` and `README.md` off the public site.

## Design

Dark editorial look modeled on lamalama.com's style (look and motion only, no copied text, images or logos):

1. Colors: background #1a1c1c, text #f9f4eb, hairlines rgba(249,244,235,0.2), chips #0b0c0c, soft pill #b8b5ae.
2. Fonts (Google Fonts): Inter Tight for headlines and body, Sometype Mono for small uppercase labels.
3. Motion: headline slide-up on load, text-scramble on mono labels, nav pill label follows the section in view, About statement brightens word by word on scroll, halftone dot canvas in the hero, live San Diego clock. Respects prefers-reduced-motion.
4. The "JD" text monogram in the nav is Justin's own. Do not reintroduce a pixel-style mark (too close to lamalama's logo).

## Content rules

1. Facts come from Justin's LinkedIn. Never invent roles, dates, numbers or claims.
2. Focus: revenue, AI, enterprise software.
3. Email CTA: Justin.Dass.2027@gmail.com. LinkedIn: https://www.linkedin.com/in/justin-dass-cro-global-sales-leader/
4. Voice: concise, plain business language. No em dashes or en dashes. No buzzwords (leverage, synergy, scalable, seamless, etc.). "ASTERRA" always all caps.
5. PartnerOne acquisitions line approved by Justin (Nov 18, 2026): "I led revenue strategy across 5 acquisitions of $100M+ each." Lives in the About "( Before )" paragraph.
6. No company logos on the site. The Experience list stays text only.
7. Headline positioning: "Global Revenue Leader" (kicker, page title, OG tags). Approved Nov 18, 2026.
8. Numbers strip in About uses pre-ASTERRA facts only (3 exits, 5 acquisitions, 20 PE companies). Justin wants no ASTERRA metrics there to avoid conflict of interest.
9. Experience rows open on click ( + ) to show LinkedIn detail, promotions (Autodesk, Epicor) and links (Dass Strategic Group site, 2 SupplyPro press release PDFs on supplypro.com).
10. Link preview image is `og.png` (1200x630) at the repo root. Regenerate it if the title or headline changes.
11. Open question: hero bar says "20+ years" while LinkedIn About says "15+ years". Pick one with Justin.

## Requests in the queue (not started)

Build these only if the site actually needs them and they will go live. Do not start any of them speculatively.

1. Rebuild buttons and forms with shadcn/ui. This needs a move to Next.js plus Tailwind; Justin has not approved that yet. Ask first.
2. Contact form that emails Justin through Resend on each submission. Needs a Resend account and API key from Justin, stored as a Vercel environment variable.
3. PostHog analytics to see who visits. Needs Justin's PostHog project key.
4. Apify: find yoga studios in Austin and save them to "my database". Unrelated to this site; confirm which database and purpose with Justin before running anything.
5. Neon: `neon init` was run in a scratch copy for project flat-firefly-59639622 (branch production) but never signed in or deployed. Not needed for the current static site.

## Working with Justin

1. Ask clarifying questions one at a time.
2. Never send messages, make purchases or connect accounts without his explicit OK.
3. After any change, push to `main`, then open the live site and confirm it loads.
