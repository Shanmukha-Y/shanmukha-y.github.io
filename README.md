# shanmukha-y.github.io

Personal site + writing log. Static HTML/CSS: no build step, no framework, no tracking. Served by GitHub Pages at [shanmukha-y.github.io](https://shanmukha-y.github.io).

Entries are append-only: numbered, dated, and stamped with the short hash of the log state they were appended to. Published prose is immutable; corrections are appended, never edited in.

## Verification checklist (after every push)

1. **Site serves.** https://shanmukha-y.github.io returns the homepage (allow a minute for Pages to rebuild).
2. **New entry loads.** Click the ledger row; the entry page renders with fonts, code blocks, and the pager.
3. **Both themes.** Check light and dark (`prefers-color-scheme`); the amber accent and AA contrast hold in both.
4. **Metadata.** View source on the entry: `<title>`, meta description, canonical URL, and `og:url` all match the real filename.
5. **X card preview.** Paste the entry URL into an X compose box (or [socialsharepreview.com](https://socialsharepreview.com)) and confirm the `summary_large_image` card shows title, description, and `assets/og.png`.
6. **Share link.** The entry's "share on x" intent link opens prefilled with the title and canonical URL.
7. **Ledger consistency.** Entry number, date, and `#hash` match between index.html and the entry file; numbering is strictly increasing.
8. **No template leftovers.** Grep the entry file for the previous entry's slug and title fragments; must return nothing.
