# Syed Mustafa Hassan — Portfolio

A single-file, dependency-free portfolio site (`index.html`).

- **Edit content:** everything (experience, projects, certifications, awards, events, articles, contact) lives in the `D` object inside the `<script>` at the bottom of `index.html`.
- **Run locally:** open `index.html` in a browser.
- **Deploy:** drag the folder into Netlify (or GitHub Pages / Vercel). No build step.

## Adding photos
- **Profile photo:** replace `assets/profile.jpg` (square, at least 600×600 works best).
- **Event photos:** save each one as `assets/events/<date>.jpg` using the event date, e.g. `assets/events/2024-01-16.jpg` for the Cisco conference. The photo then replaces that event's designed cover.

Features: light/dark theme, animated network-topology hero, traceroute career timeline, scroll-driven reveals, count-up stats, filterable certifications, cursor spotlight cards, and full `prefers-reduced-motion` support.

## Logos
Brand and technology logos are the official marks from the Iconify `logos`, `devicon` and `simple-icons` collections, embedded in `index.html`.
Organizations without a public logo package show a monogram until you add their logo as `assets/logos/<key>.png`.
Keys: wateen, nanotechx, maju, bytewise, xpert (360XpertSolutions), swoc, gssoc, wob (Winter of Blockchain), mckinsey, stanford, mit,
neuromatch, deeplearning, openclassrooms, hec, icpc, pug, maventech, itcn, oneguide, jinnah, hacktoberfest, mlsc.

## Go live (Netlify, free)
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page. It goes live in seconds on a `*.netlify.app` address.
3. Optional: Site settings → Domain management → add a custom domain (e.g. syedmustafahassan.com).

Or connect the GitHub repo in Netlify ("Add new site → Import from Git"), pick this branch, leave the build command empty and the publish directory as `.`. Every push then updates the site automatically.

After it's live, send the address so the link-preview image and search tags can use the full URL.
