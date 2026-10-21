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
| ![Dark mode](assets/basori-dark.png) | ![Light mode](assets/basori-ligth.png) |

Navigation Tree Preview with All Styles Settings actives (opacity 0-100)

![Navigation-Tree](assets/navigation-tree-preview.png)

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
- **Style Settings** controls for note and interface fonts
- Optional **Calendar agenda style** with a highlighted month header, square date tiles, and distinct today/selected states
- Optional **Lucide-style file explorer icons** for notes and folders, including open and closed folder states
- Folder icons can use varied Basori palette colors or one selected accent color
- Styled components:
  - Tabs & tab stacks
  - Buttons, inputs, dropdowns, checkboxes
  - Modals, dialogs, popovers
  - Callouts (unique colors per type)
  - Blockquotes, headings, pills
  - Scrollbars, drag ghost, sliders
- Built with a modular **SCSS** structure for maintainability

---

## Plugins Support

- [Style Settings](https://github.com/community-archive/obsidian-style-settings) — choose fonts, enable the Calendar layout, and configure file explorer icons and folder colors.
- [Calendar](https://github.com/liamcain/obsidian-calendar-plugin) — optional agenda-style layout.
- [Checklist](https://github.com/delashum/obsidian-checklist-plugin)

### Style Settings

Install and enable the Style Settings community plugin, then open **Settings → Style Settings → Basori**.

- **Note font** and **Interface font** let you choose between Inter, Arial, Helvetica, Georgia, Times New Roman, and Courier New. The selected font must be available on your system; otherwise the listed fallback font is used.
- **Calendar agenda style** enables the alternate layout for the Calendar plugin.
- **Folder and note icons** adds Lucide-style icons to the file explorer.
- **Folder icon colors** chooses varied colors or one color for folder icons. Varied colors repeat in a stable sequence; in single-color mode, choose an accent under **Folder color**.

Enable **Folder and note icons** to show folder colors. Folder colors affect icons only; folder names retain the normal explorer text color.

### Checklist
![checkbox](assets/checkbox-styles.png)

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

## Try the preview

Open & Copy [`docs/theme-preview.md`](docs/theme-preview.md) in Obsidian to test headings, callouts, tables, and more.

---

## License

MIT — see [LICENSE](LICENSE)
