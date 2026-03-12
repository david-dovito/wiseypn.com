# wiseypn.com

## Context
- **Client**: WISE Professionals YPN (3-WYPN)
- **Drive**: `DOVITO MASTER/DEPARTMENTS/CLIENTS/3-WYPN-WISE YPN/`
- **Brand Kit**: See `brand-kit.md` in the Drive folder

## Stack
- Static HTML/CSS/JS (no framework)
- Hosted on Vercel (wiseypn.com)
- Google Fonts: Montserrat + Inter

## Structure
- `index.html` - Single page landing site
- `styles.css` - All styles
- `images/` - Logo, event photos, founder headshots
- `images/sponsors/` - 9 sponsor logos
- `images/dovito-white.png` - White Dovito logo for footer credit
- `.gitignore` / `package.json` - Vercel analytics dependency

## Sections
1. Nav (logo + Join Now + anchor links)
2. Hero (logo + tagline + CTA)
3. About (who we are)
4. Events (pro dev + networking/social)
5. Founders (headshots + names)
6. Sponsors (placeholder - coming soon)
7. Footer (social icons + links)

## Notes
- Keep it lean. No build step. Static HTML served directly.
- Vercel Analytics via built-in script (`/_vercel/insights/script.js`), not bundled.
- 9 sponsors active with logo grid.
- Events link to Windsor Chamber system, not custom pages.
- Footer has "site by dovito(R)" linking to dovito.com with inline white logo.
