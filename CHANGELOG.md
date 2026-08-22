# Change Log

All notable changes to the "weyland-viridian-storm" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [1.3.0] - 2026-08-22

### Fixed

- Activity Bar no longer loses its hot-pink accents after the VS Code update:
  - `activityBar.activeBackground` was fully transparent (`#ff247f00`) — made visible (`#ff247f26`)
  - `activityBar.activeBorder` now glows hot pink (`#ff247f`) instead of blending into the background
  - `activityBar.activeFocusBorder` is now visible (`#ff247f66`)
- Added the new `activityBarTop.*` color set so the theme also works when the
  Activity Bar is placed on the **top / bottom** (new VS Code layout support)
- `tab.activeBorderTop` now shows the hot pink tab indicator (`#ff247f`)
- `panelSectionHeader.border` no longer uses a debug-red `#ff0000`

## [1.2.0] - 2026-08-14

### Added

- Full panel color theming (panelSection*, panelInput.border, panel.dropBorder)
- Brighter foreground for the active panel tab

### Changed

- Version bumped to 1.2.0
- Fixed repository URL to https://github.com/Yurii-Weyland/Viridian-Storm
- Author metadata set to Weyland Yurii

## [1.1.0] - 2026-08-14

### Changed

- Repository and publisher metadata alignment

## [1.0.0] - 2026-08-03

### Changed

- Renamed theme to **Weyland Viridian Storm** 🗲
- Full release version 1.0.0

## [0.0.3] - 2026-06-15

### Added

- .dotenv file syntax highlighting support 🗲 (separate scope from .env)

## [0.0.2] - 2026-06-15

### Added

- .env file syntax highlighting support 🗲
- Custom colors for: variables, strings, comments, numbers, booleans, null, escape chars, export keyword

## [0.0.1] - 2026-06-15

### Added

- Initial release of Viridian Storm 🌩️
- Dark teal editor background with neon accent colors
- Syntax highlighting for TypeScript, React, Python
- Color palette inspired by Tokyo Night Storm & Dracula
- Custom bracket colors (Orange / Cyan / Green)
- Hot pink active line numbers
- MIT License
- Icon and 6 screenshots
