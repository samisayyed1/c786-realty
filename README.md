# C 786 Realty — Landing Page

A premium single-page landing site for **C 786 Realty Co. L.L.C**, a Dubai boutique real estate firm.

## Stack
- One file: `index.html` (HTML + CSS + vanilla JS, no build step)
- Hosted on GitHub Pages
- Fonts: Fraunces (display) + Inter (body) via Google Fonts
- Imagery: Unsplash CDN

## What it does
- Sticky responsive nav + mobile drawer
- Cinematic hero with Dubai skyline
- Services, neighborhoods, why-us, process, testimonial, FAQ
- **Book-a-call form** that composes a pre-filled WhatsApp message to `+971 58 593 0850`
- Floating WhatsApp button on every screen

## Customizing
- **Phone number** — search `971585930850` and replace
- **Email** — search `hello@c786realty.com` and replace
- **Colors / typography** — edit the `:root` design tokens at the top of `index.html`
- **Calendly** — to swap the WhatsApp form for Calendly, replace the form `<script>` `wa.me` URL with your Calendly link, or embed an inline Calendly widget in `#book`.

## Local preview
```bash
open index.html        # macOS
# or
python3 -m http.server # then visit http://localhost:8000
```

## Deploy
Pushed to GitHub Pages on the `main` branch.
