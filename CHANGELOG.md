# Change Log

## [1.1.0] - 2026-08-06
### Added
- Anura Light theme
  - Light variant built from the Anura light palette
  - Same token role mapping and UI structure as the dark theme
  - Registers as `uiTheme: vs` so it follows the system light/dark toggle
- Integrated terminal ANSI colors in both themes now match the Anura palettes; terminal background blends with the workbench panels
- Line number gutter now matches the editor background in both themes
- Active line number uses the plain text color; inactive line numbers use the comment color (dark) or a lighter neutral gray (light)

## [1.0.2] - 2025-01-30
- Add icon

## [1.0.1] - 2025-01-23
### Fixed
- Improved function and variable coloring
  - Added language-specific function scopes
  - Enhanced variable scoping in function arguments
  - Added support for generic function scopes across languages

### Changed
- Adjusted Git indicator colors to be more intuitive
  - Modified: Changed to softer yellow (#e2c08d)
  - Added: Changed to softer green (#73c991)
  - Deleted: Changed to clearer red (#f14c4c)

## [1.0.0] - 2025-01-23
### Added
- Set colors for all UI elements

## [0.0.1] - 2025-01-22
- Initial release
- Basic color scheme implementation
