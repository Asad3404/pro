# Syed Mustafa Hassan — Portfolio

A single-file, dependency-free portfolio site (`index.html`).

- **Edit content:** everything (experience, projects, certifications, awards, events, articles, contact) lives in the `D` object inside the `<script>` at the bottom of `index.html`.
- **Run locally:** open `index.html` in a browser.
- **Deploy:** drag the folder into Netlify (or GitHub Pages / Vercel). No build step.

## Adding photos
- **Profile photo:** replace `assets/profile.jpg` (square, at least 600×600 works best).
- **Event photos:** save each one as `assets/events/<date>.jpg` using the event date, e.g. `assets/events/2024-01-16.jpg` for the Cisco conference. The photo then replaces that event's designed cover.

Features: light/dark theme, animated network-topology hero, traceroute career timeline, scroll-driven reveals, count-up stats, filterable certifications, cursor spotlight cards, and full `prefers-reduced-motion` support.
