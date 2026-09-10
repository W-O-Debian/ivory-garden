# Changelog

All notable changes to Ivory Garden will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] — 2026-09-10

### Added

- **Warm Toggle** — a 50% color temperature shift toward 3300K, reducing blue light for nighttime reading. Toggle via Style Settings → Advanced → "Warm shift (eye comfort)", or per-note using the `warm-shift` cssclass. Preserves palette identity while easing eye strain.
- **True Focus Mode** — hides everything except the note workspace (ribbon, sidebars, tabs, status bar, view header). More aggressive than Minimal's built-in focus mode. Toggle via Style Settings → Advanced → "True focus mode", or per-note using the `true-focus-mode` cssclass. A subtle "Esc to exit focus mode" hint appears in the bottom-right corner.
- **PDF Export styling** — `@media print` rules that force background colors to print, hide UI chrome, set proper page margins (2cm), prevent orphaned headings, and preserve callouts, code blocks, highlights, and tables. Obsidian's "Export to PDF" now produces beautiful theme-colored PDFs.
- **Custom syntax highlighting** — palette-tuned code colors: keywords in cobalt blue, strings in dusty teal, comments in walnut, numbers/functions in muted gold, tags in muted brick.
- **Graph view color preset** — graph nodes, lines, tags, attachments, and unresolved links now match the Ivory Garden palette instead of Obsidian's defaults.

### Changed

- Updated header comment to document the new v1.1.0 features.

## [1.0.0] — 2026-09-05

### Added

- Initial release of Ivory Garden — a recolour of Minimal v9.0.2 for Obsidian.
- Warm ivory paper backgrounds (`#FAF5F0`, `#FDFBF8`, `#EEE6DD`) for light mode.
- Deep cocoa text (`#3E2723`) for reduced eye strain vs. pure black-on-white.
- Cobalt blue accent (`#0B68DA`) for links and interactive elements.
- Signature muted gold glow (`#C49A3C`) for text highlights — the palette's namesake.
- **Midnight Garden** dark variant — espresso-black backgrounds with warm ivory text, lightened cobalt accent, and a brighter gold glow.
- Extended palette harmonised with the garden aesthetic (muted brick red, sage green, dusty rose, etc.).
- Explicit scheme classes `.minimal-ivory-garden-light` and `.minimal-ivory-garden-dark` for parity with Minimal's other named schemes.
- Demo vault showcasing headings, callouts, tables, code blocks, task lists, and Dataview examples.
- Real Obsidian screenshots for light/dark editor and reading modes.

### Inherited from Minimal v9.0.2

- Full feature set: focus mode, cards, image grid, table helpers, tab styles, callouts, embeds, heading dividers, tag styles.
- Plugin compatibility: Calendar, Charts, Dataview, Git, Kanban, Style Settings, Zoom, and more.
- Complete Style Settings YAML surface for granular customization.
- 14 preset color schemes (Dracula, Gruvbox, Nord, Solarized, Catppuccin, etc.) remain selectable.

### Credits

- Original Minimal theme by [@kepano](https://twitter.com/kepano) — [github.com/kepano/obsidian-minimal](https://github.com/kepano/obsidian-minimal)
- Ivory Garden palette and recolour by [Ward Skaiker](https://github.com/W-O-Debian)
