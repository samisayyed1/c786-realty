# C 786 Realty — Landing Page

A premium single-page landing site for **C 786 Realty Co. L.L.C**, a Dubai boutique real estate firm.

## Stack
- One file: `index.html` (HTML + CSS + vanilla JS, no build step)
- `assets/` — optimised WebP renders of the featured Danube launches
- Hosted on GitHub Pages
- Fonts: Fraunces (display) + Inter (body) via Google Fonts

## What it does
- Sticky responsive nav + mobile drawer
- Cinematic hero carousel of real Danube launches (Shahrukhz, Breez, Fashionz, Sportz, Greenz)
- **Qualification flow** — a 7-step modal lead-qualifier (goal → launch → budget → funding → deposit → timeline → contact) that returns a personalised result (Golden Visa eligibility, matched launches, 1%-plan monthly estimate) and hands off to WhatsApp
- Signature-launches grid with real projects, prices, payment-plan facts
- Services, areas, why-us, process, testimonial, FAQ
- **Book-a-call form** that composes a pre-filled WhatsApp message to `+971 58 593 0850`
- Floating WhatsApp button + scroll-triggered sticky CTA on every screen
- **Event tracking** — every CTA and qualifier step pushes to `window.dataLayer` and bridges to `gtag` if present (wire up GA4/GTM to capture it)

## Languages
Client-facing copy advertises **English · Arabic · Hindi · Tamil**.

## Customizing
- **Phone number** — search `971585930850` and replace
- **Email** — search `hello@c786realty.com` and replace
- **Colors / typography** — edit the `:root` design tokens at the top of `index.html`
- **Featured launches** — edit the `.residences` cards in the markup, and the `PROJECTS` array in the qualifier script (name / from-price / location) that powers the result-screen matching
- **Analytics** — the page already pushes events to `window.dataLayer`; add a GA4/GTM or `gtag` snippet to start collecting them
- **Calendly** — to swap the WhatsApp form for Calendly, replace the form `<script>` `wa.me` URL with your Calendly link, or embed an inline Calendly widget in `#book`.

## Local preview
```bash
open index.html        # macOS
# or
python3 -m http.server # then visit http://localhost:8000
```

## Deploy
Pushed to GitHub Pages on the `main` branch.
