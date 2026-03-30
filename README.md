# ADAUX AGENCY — Website

Hip Hop Event Management · India

---

## Files

```
adaux/
├── index.html    — Entry point (loads React via CDN + fonts)
├── styles.css    — All styles, animations, responsive breakpoints
├── app.jsx       — React app: all pages, data, components
└── README.md     — This file
```

## Pages

| Page     | Route (internal) | Description                          |
|----------|-----------------|--------------------------------------|
| Home     | HOME            | Hero, stats, events preview, CTA     |
| Events   | EVENTS          | Filterable events table              |
| Services | SERVICES        | Sticky-scroll services list          |
| About    | ABOUT           | Story, team, stats                   |
| Contact  | CONTACT         | Inquiry form with validation         |

---

## Customisation

- **Events**: Edit the `EVENTS` array at the top of `app.jsx`
- **Services**: Edit `SERVICES` array
- **Team**: Edit `TEAM` array
- **Clients**: Edit `CLIENTS` array
- **Colors**: Change CSS custom properties at the top of `styles.css`
- **Logo**: Replace the `ADAUX` text in the `<header>` with an `<img>` tag

---

## Tech Stack

- React 18 (CDN, no build step)
- Babel Standalone (JSX in browser)
- Google Fonts: Bebas Neue, Barlow, Barlow Condensed
- Pure CSS animations (no external animation library)
- No dependencies to install

---

© 2025 Adaux Agency
