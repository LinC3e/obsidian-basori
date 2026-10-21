# Basori 1.2.2

## Added

- Added Style Settings font selectors for note and interface text, with system-font fallbacks.
- Added an optional agenda-style layout for the Calendar community plugin, including clearer month, today, and selected-date states.
- Added optional Lucide-style file and folder icons, including distinct open and closed folder icons.
- Added folder icon color modes: varied colors from the Basori palette or one selected accent color.
- Added responsive reading and editing widths that stay centered across screen sizes, with a wider maximum for fullscreen layouts.

## Fixed and improved

- Fixed Style Settings font selectors so they update the theme's actual font variables.
- Fixed folder coloring so only the folder icon is colored and the folder name remains readable.
- Fixed the file explorer background image so it stays anchored behind the navigation while scrolling, without blocking explorer scrolling.
- Fixed the sidebar image opacity control so its percentage value updates live without requiring an Obsidian restart.
- Centered the reading and editing content consistently and reduced uneven side spacing on wide screens.
- Improved component sizing, focus states, callout spacing, and calendar interactions.
- Preserved the existing light and dark palettes.

## Notes

- Style Settings is required for the theme options described above.
- Fonts are not bundled with Basori. If a selected font is unavailable on the system, the browser uses its fallback.
- The Calendar layout requires the Calendar community plugin and is disabled by default.
- File and folder icons and folder coloring are optional and disabled by default.
- The sidebar background image is optional; its opacity can be adjusted in Style Settings while the theme is active.
