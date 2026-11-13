# RACKETMAN Website — Starter Source Package

A responsive, front-end website starter built from the RACKETMAN website framework and creative-direction brief.

## Included
- `index.html` — full landing page structure and content sections
- `assets/css/styles.css` — responsive styling, brand colours, layout and motion
- `assets/js/main.js` — mobile navigation, interactive 3-step racket diagnostic and booking-form WhatsApp handoff placeholder
- `docs/` — supplied website framework PDF and creative-direction prompt
- `assets/images/` — reserved for approved RACKETMAN logo, mascot and repair photography

## Run locally
Open `index.html` in a browser, or run a local static server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before launch
1. Add approved RACKETMAN logo, mascot, repair before/after and product images into `assets/images/` and update the HTML/CSS references.
2. In `assets/js/main.js`, set `const number` to the official WhatsApp Business number in international format, digits only (no `+` or spaces).
3. Connect the booking form to a real lead/CRM endpoint. The current form is front-end demo behavior only and does not store submissions.
4. Add real repair case studies, prices, service areas, contact details, privacy policy and terms.
5. Configure analytics, consent management, SEO metadata, hosting and performance testing.

## Brand tokens
- Deep Racketman Blue: `#002B5C`
- Neon Ball Yellow: `#DFFF00`
- Near-black Navy: `#06121F`
- White: `#FFFFFF`
- Light Grey: `#F4F6F8`

## Notes
This is a working front-end starter/prototype, not a production-ready backend or a pixel-perfect recreation of a previously deployed site. The supplied project brief and creative direction are included for reference. Original RACKETMAN image files were not embedded because the Library source assets did not expose downloadable raw files in this session; add the approved originals to `assets/images/` before publishing.
