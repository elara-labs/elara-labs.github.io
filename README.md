# Elara — Intelligent Systems

Landing page for [Elara](https://elara-labs.github.io), an AI systems consultancy.

## Stack

Static HTML, CSS, and vanilla JavaScript. No build tools or frameworks. Hosted on GitHub Pages.

- **Fonts:** Cormorant Garamond (display), DM Sans (body), Space Mono (mono), loaded via Google Fonts
- **Background:** Canvas-based animated starfield
- **Animations:** CSS keyframes + Intersection Observer for scroll reveals

## Structure

Single `index.html` with embedded styles and scripts. Sections:

1. **Hero** with animated headline and CTAs
2. **Capabilities** covering AI automation, custom apps, and scalable systems
3. **Process** (Discovery, Prototype, Build, Evolve) outlining the engagement workflow
4. **About** with a brief description of the team
5. **Contact** CTA linking to email

## Development

Open `index.html` in a browser. No build step required.

```bash
# Local dev server (optional)
python3 -m http.server 8000
```

## Deployment

Pushes to `main` are published automatically via GitHub Pages.
