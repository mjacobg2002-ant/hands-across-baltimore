# Hands Across Baltimore — Homepage

A modern, accessible, conversion-ready homepage for **Hands Across Baltimore**, an outpatient
mental-health center in Baltimore, MD. Redesigned from the existing site content into a warm,
clinically credible, community-rooted single-page site.

## Stack
- Single static `index.html` — semantic HTML, self-contained CSS, and a small amount of vanilla
  JavaScript (dropdown + accessible mobile drawer). No build step, no external dependencies.
- Local, optimized images in `/images` (sourced from Pexels, downloaded — not hotlinked).

## Run locally
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Content source
Factual content (services, PRP, contact, hours, tagline) was taken from
<https://www.handsacrossbaltimore.com/>. No services, staff, credentials, accreditations,
statistics, or testimonials were invented.

## Needs client confirmation before publishing
See the "flag" list in the delivery notes. Key items:
- Replace the placeholder brand mark (inline SVG in the header/footer) with the official logo.
- Confirm exact referral-form URL(s) — currently the "Referrals / Refer a Client" links point to
  the on-page Contact section.
- Confirm "board-certified psychiatric providers" wording (carried from the source site).
- Confirm which services are offered in-home / community / virtually before stating so publicly.
- Provide real staff, photography, and Privacy/Accessibility page content (links are anchors).

## Images
| File | Section | Pexels source |
|------|---------|---------------|
| hero.jpg | Hero | pexels.com/photo/7579315 |
| therapy.jpg | Therapy feature | pexels.com/photo/5699449 |
| community.jpg | Substance-use feature | pexels.com/photo/7983216 |
| families.jpg | Medication management | pexels.com/photo/8524978 |
