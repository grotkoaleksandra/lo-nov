# GROTKA — Artist Portfolio

## Project Overview
Single-page artist portfolio website for **Grotka** (Alexandra Grotko). Sells paintings, prints, and stickers. Hosted on GitHub Pages.

## Live URL
https://grotkoaleksandra.github.io/lo-nov/

## GitHub Repo
https://github.com/grotkoaleksandra/lo-nov

## Tech Stack
- Single HTML file (`index.html`) — all CSS and JS inline
- GitHub Pages for hosting (deploys from `main` branch root)
- No build step, no frameworks, no dependencies

## Design Direction
- **Aesthetic:** Apothecary / heritage brand — expensive but whimsical, minimalist
- **Fonts:** Cormorant Garamond (serif, headings) + Outfit (sans, body) via Google Fonts
- **Palette:** Warm parchment tones — `#FAF8F5` bg, `#F3EEE8` alt bg, `#8B6F4E` accent (antique gold), `#1a1715` text
- **Gallery:** 12-column CSS Grid collage, edge-to-edge, 3px gaps, mostly square/vertical shapes
- **Reference site:** agatanowicka.com (minimal, high contrast, monospace — but we went warmer/serif)
- **"Shop" is called "Collected Works"** — no tacky commerce language
- **Buttons say "Inquire"** — open pre-filled mailto to hello@grotka.art

## Sections
1. **Hero** — large serif "Grotka" with gold divider line, italic tagline
2. **Gallery** — 12-item asymmetric collage (currently picsum.photos placeholders — user will provide real images)
3. **Collected Works** — 6 product cards (3 prints, 2 stickers, 1 sticker pack) with Inquire mailto buttons
4. **About** — artist photo + bio text, two-column layout
5. **Contact** — email link + social links (Instagram, Behance, Etsy)
6. **Footer** — copyright

## Pending / Future Work
- Replace all picsum.photos placeholder images with real artwork (user will provide files + names)
- Replace placeholder product names with real artwork titles
- Update email from hello@grotka.art to real email
- Update social links to real profiles
- E-commerce integration later using LINK.ai + Resend email (see `.claude/skills/setup-alpacapps-infra/SKILL.md`)
- Infrastructure setup wizard available in `.claude/skills/` for when e-commerce is needed

## Key Decisions Made
- Name changed from "Lo Nov" to "GROTKA" (user request)
- "Shop" renamed to "Collected Works" (user found "Shop" tacky)
- "Add to Cart" buttons replaced with "Inquire" mailto links
- Gallery uses square-ish proportions (mostly span 4 rows) instead of extreme aspect ratios
- Gallery runs edge-to-edge (no side padding) for seamless collage wall
- Mobile menu uses italic serif lowercase text

## Git Workflow
- Push immediately after changes — GitHub Pages auto-deploys from main
- Single HTML file means every change is one file commit
