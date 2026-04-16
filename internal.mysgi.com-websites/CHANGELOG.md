# Changelog

## v1.0.0 — April 2026

### Added
- Full portal redesign matching SGI brand identity (cyan `#00aeef`, black, white)
- `index.html` — new portal home replacing the original plain-text page
- `SGI-Design-System.html` — living style guide and brand reference document
- `src/css/theme.css` — shared CSS with custom properties for all brand tokens
- `src/js/main.js` — shared scripts placeholder
- Redesigned sub-pages for all 6 tools:
  - PushMail — job number entry form
  - PackSlip — account code selection
  - QASlip — account code selection
  - DataDepot 4 — two-column docs layout with sidebar navigation
  - Amgen Label Change Report — dynamic item entry form
  - Item Linkage Report — client selection with run/download actions
- SGI logo (`sgi_logo.svg`) in header across all pages
- Consistent header, hero banner, and footer shell on every page
- "← Back to Portal" navigation on all sub-pages
- Animated cyan hover effect on portal cards

### Changed
- Replaced original single-file plain HTML portal (`internal-nexus-`) with structured multi-page project
- Hero banner height reduced for better above-the-fold visibility
- Main content wrapper widened to 1400px

### Removed
- Original unstyled `internal-nexus-` portal file
- Development screenshot assets
