# Werkplaats17 Rotterdam

Marketing website for a professional workspace in Rotterdam. Static HTML site deployed via GitHub Pages.

## Stack

- Plain HTML, CSS, JavaScript (no framework, no build step)
- GitHub Pages deployment (gh-pages branch = production)

## Key Commands

```bash
# No build step needed -- edit files directly
# Deploy: commit + push to trigger GitHub Pages
git add -A && git commit -m "update" && git push
```

## Architecture

- `index.html`: Main landing page
- `admin.html`: Admin panel (single floor — BG only)
- `content.js`: All site text, prices, contact info -- single source of truth for content
- `photos.js`: Photo gallery data
- `placed-objects.js`: Interactive floor plan object placement

## Location

- **Address:** Van Maasdijkweg 29, 3088 EC Rotterdam (Waalhaven-Zuid)
- **Area:** 785 m² (750 m² bedrijfshal + 35 m² kantoor)
- **Floors:** 1 (begane grond only)
- **Rent:** €5.500/mnd + €950 servicekosten (excl. BTW)

## Conventions

- Content changes go in `content.js` (structured as `CONTENT` object)
- Dutch language site
- Auto-deploy: any push triggers GitHub Pages update
- Git remote: `https://github.com/midirectiekade14-debug/werkplaats17-rotterdam.git`
