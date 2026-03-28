# Roland TR-808 — Obsidian Theme

An [Obsidian](https://obsidian.md) theme inspired by the iconic **Roland TR-808 Rhythm Composer** drum machine.

![TR-808](https://upload.wikimedia.org/wikipedia/commons/4/40/Roland_TR-808_%28large%29.jpg)

## Color Palette

The theme draws directly from the TR-808's hardware design:

| Color | Hex | Source |
|-------|-----|--------|
| Red | `#E8280C` | Step buttons 1–4 |
| Orange | `#E8630E` | Signature accent lines, step buttons 5–8 |
| Yellow | `#E8D30E` | Step buttons 9–12 |
| Cream | `#E8DFC8` | Front panel face |
| Charcoal | `#1C1C1C` | Machine casing |
| Silver | `#8A8A8A` | Step pads |

## Features

- **Dark mode** — based on the TR-808's charcoal casing with cream text
- **Light mode** — based on the warm cream front panel with dark text
- **Heading gradient** — H1 through H6 follow the red → orange → yellow button sequence
- **808 orange accents** — links, cursors, active elements, blockquote borders, and focus rings
- **Full coverage** — graph view, tags, callouts, code blocks, checkboxes, nav, and more

## Installation

### From Obsidian Community Themes (coming soon)

1. Open **Settings → Appearance**
2. Click **Manage** under Themes
3. Search for "Roland TR-808"
4. Click **Install and use**

### Manual Installation

1. Download `theme.css` and `manifest.json` from the [latest release](../../releases/latest)
2. Create a folder called `Roland TR-808` inside your vault's `.obsidian/themes/` directory
3. Place both files in that folder
4. Open **Settings → Appearance** and select **Roland TR-808**

### From Source (symlink)

```bash
ln -s /path/to/Rlnd808-ObsidianTheme "/path/to/vault/.obsidian/themes/Roland TR-808"
```

## Releasing

This repo includes a GitHub Actions workflow. To create a release:

```bash
git tag 1.0.0
git push origin 1.0.0
```

This creates a draft release on GitHub with `manifest.json` and `theme.css` attached.

## License

MIT
