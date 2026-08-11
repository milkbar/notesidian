# Notesidian (marketing + docs site)

Static GitHub Pages site for Notesidian, served from `docs/` (no build step). The app source is the sibling repo `../notesidian-code`.

## Updating for a release
- `docs/changelog.html` mirrors `../notesidian-code/CHANGELOG.md` — newest version section on top, grouped Added / Changed / Fixed. Add a new `release-tag` block (badge `gray` "In development" until it ships).
- `docs/index.html` holds the marketing highlights (the `new-grid` cards); refresh them when a marquee feature lands.
- Plain HTML/CSS, self-contained. `styles.css` is shared across pages.

## Conventions
- Commit straight to `main`. Never add a `Co-Authored-By` line. Don't push unless asked.
- Current state: 1.2.1 is on the App Store. No release currently in development.
