# Basori

> An Obsidian theme inspired by **Basori Tiara** — clean lines, cool blues, and a sharp square aesthetic.

![Obsidian](https://img.shields.io/badge/Obsidian-Theme-7C3AED?style=flat-square&logo=obsidian&logoColor=white)
![Mode](https://img.shields.io/badge/Dark%20%26%20Light-Supported-38BDF8?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-22C55E?style=flat-square)

---

## Preview

<!-- Reemplaza estas rutas con tus capturas reales -->
| Dark | Light |
|------|-------|
| ![Dark mode](screenshots/preview-dark.png) | ![Light mode](screenshots/preview-light.png) |

---

## About
The design language is:

- **Square** — no rounded corners; intentional, structured UI
- **Cool blue/cyan palette** — slate and sky tones for focus and clarity
- **Consistent components** — buttons, tabs, modals, callouts, and inputs share the same visual system
- **Readable first** — hierarchy and contrast over decoration

Dark mode uses deep slate blues; light mode uses soft sky backgrounds. Both keep the same geometry and spacing.

---

## Features

- Full **dark** and **light** support
- Styled components:
  - Tabs & tab stacks
  - Buttons, inputs, dropdowns, checkboxes
  - Modals, dialogs, popovers
  - Navigation (File Explorer)
  - Callouts (unique colors per type, no icons)
  - Blockquotes, headings, pills
  - Scrollbars, drag ghost, sliders
- Built with a modular **SCSS** structure for maintainability

---

## Installation

<!-- ### Community Themes

1. Open **Settings → Appearance**
2. Under **Themes**, click **Manage**
3. Search for **Basori**
4. Click **Install**, then **Use** -->

### Manual installation

1. Download `theme.css` and `manifest.json` from the [latest release](https://github.com/linc3e/obsidian-basori/releases)
2. Copy them into:

```
YourVault/.obsidian/themes/Basori/
```

3. In Obsidian: **Settings → Appearance → Themes → Basori**

---

## Development

```bash
npm install
npm run build    # compile SCSS → theme.css
npm run watch    # rebuild on change