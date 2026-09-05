# Obsidian Community Theme Submission

This file contains the entry to add to [`community-css-themes.json`](https://github.com/obsidianmd/obsidian-releases/blob/HEAD/community-css-themes.json) when opening your PR to the `obsidianmd/obsidian-releases` repo.

## Step 1: Open the PR

1. Go to https://github.com/obsidianmd/obsidian-releases
2. Click the `community-css-themes.json` file
3. Click the ✏️ pencil icon to edit
4. Add the entry below (in alphabetical order by `name`, after the existing "I" entries)
5. GitHub will automatically fork the repo and open a PR

## Step 2: The JSON entry

```json
{
  "name": "Ivory Garden",
  "author": "Ward Skaiker",
  "repo": "https://github.com/W-O-Debian/ivory-garden",
  "screenshot": "screenshots/reading-light.png",
  "modes": ["light", "dark"],
  "branch": "main",
  "minAppVersion": "1.13.0"
}
```

## Step 3: PR title and description

**Title:**
```
Add Ivory Garden theme
```

**Description:**
```markdown
## Ivory Garden

A warm, paper-light theme for Obsidian — a recolour of Minimal v9.0.2 by @kepano. Designed for long reading sessions with reduced eye strain: ivory paper backgrounds instead of pure white, deep cocoa text instead of pure black, a single cobalt blue accent, and a signature muted gold glow for highlights.

- **Light mode:** Ivory Garden — warm ivory and cream surfaces with deep cocoa text
- **Dark mode:** Midnight Garden — espresso-black backgrounds with warm ivory text, lightened cobalt accent, and a brighter gold glow

The theme inherits Minimal's full feature set (focus mode, cards, image grid, table helpers, tab styles, callouts, plugin compatibility, Style Settings surface). Only color values have changed.

### Credits

- Original Minimal theme: [@kepano](https://github.com/kepano/obsidian-minimal)
- Ivory Garden recolour: [Ward Skaiker](https://github.com/W-O-Debian)

### License

MIT — same as Minimal.

### Checklist

- [x] Theme has both light and dark modes
- [x] `manifest.json` has correct `name`, `version`, `minAppVersion`, `author`
- [x] Folder name matches `name` field in `manifest.json`
- [x] Screenshot referenced in this entry exists in the repo
- [x] No external assets or copyrighted material included
- [x] README explains what the theme is and how to install it
- [x] LICENSE file included (MIT, dual credit)
```

## Step 4: After the PR

- Reviewers typically respond within 1–7 days
- If they request changes, address them and push to your fork — the PR auto-updates
- Once merged, the theme appears in **Settings → Appearance → Themes → Manage** in Obsidian within a few days
- Post an announcement in the [Obsidian forum #themes channel](https://forum.obsidian.md/c/themes/33) using the draft in `forum-announcement.md`
