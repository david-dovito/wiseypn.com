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
1. Nav (logo + anchor links + Join Now CTA)
2. Hero (logo + tagline + CTA)
3. About (who we are)
4. Events (pro dev + networking/social, "Every Month" badges)
5. Membership (annual pricing cards + founding year promo + drop-in option)
6. Founders (headshots + names)
7. Sponsors (9 logos in grid)
8. Footer (social icons + links + dovito credit)

## Membership Pricing
- **Chamber members**: $75/yr (founding year rate, standard $99)
- **Non-Chamber members**: $125/yr (founding year rate, standard $189)
- **Members**: free event attendance
- **Drop-in (non-member)**: $20/event
- Founding year grandfathered rate is marketed on site

## Notes
- Keep it lean. No build step. Static HTML served directly.
- Vercel Analytics via built-in script (`/_vercel/insights/script.js`), not bundled.
- 9 sponsors active with logo grid.
- Events link to Windsor Chamber system, not custom pages.
- Two events per month: one professional development, one networking/social.
- Footer has "site by dovito(R)" linking to dovito.com with inline white logo.
