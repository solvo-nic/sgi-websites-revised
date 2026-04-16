# SGI Nexus — Internal Portal Redesign

A modernized redesign of the `internal.mysgi.com` portal, built to match SGI's brand identity.  
Open `index.html` in any browser — no installation, build tools, or server required.

---

## Project Structure

```
sgi-nexus/
├── index.html                    # Portal home — main entry point
├── SGI-Design-System.html        # Living brand style guide
├── src/
│   ├── css/
│   │   └── theme.css             # Shared styles & CSS variables
│   ├── js/
│   │   └── main.js               # Shared scripts
│   └── images/
│       └── sgi_logo.svg          # SGI logo
└── pages/
    ├── pushmail/index.html       # PushMail — job number entry
    ├── packslip/index.html       # PackSlip — production packing list
    ├── qaslip/index.html         # QASlip — QA slip management
    ├── datadepot/index.html      # DataDepot 4 — docs & navigation
    ├── amgen-label-change/       # Amgen Label Change Report
    │   └── index.html
    └── item-linkage/             # Item Linkage Report
        └── index.html
```

---

## How to Use

**Locally:** Download or unzip the project, then open `index.html` in any modern browser.

**GitHub Pages:** Push to a GitHub repo, go to Settings → Pages → Deploy from `main` branch root. The portal will be live at `https://<username>.github.io/<repo-name>`.

---

## Design System

Open `SGI-Design-System.html` in a browser for the full brand reference including:

- Color palette & CSS variables
- Typography scale
- Component library (header, hero, cards, buttons, dividers)
- Page layout shell diagram
- Usage conventions

This file is intended as a handoff document for any developer continuing work on SGI internal tools.

---

## Brand Colors

| Token | Hex | Usage |
|---|---|---|
| `--cyan` | `#00aeef` | Accent, buttons, highlights |
| `--black` | `#111111` | Hero bg, headings, borders |
| `--white` | `#ffffff` | Page bg, cards, header |
| `--bg` | `#f5f5f5` | Page background |
| `--text` | `#333333` | Body text |
| `--muted` | `#777777` | Captions, descriptions |
| `--border` | `#e0e0e0` | Dividers, subtle borders |

---

## Notes

- All pages share `src/css/theme.css` — style changes propagate everywhere automatically.
- Sub-pages use relative paths (`../../src/`) so the project is fully portable.
- No frameworks, no dependencies, no build step.

---

*Redesign proposal — SGI Intelligent Fulfillment, 2026*
