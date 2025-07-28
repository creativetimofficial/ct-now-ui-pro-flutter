## [1.2.0] 2025-07-28

### Maintenance & Modernization
- Updated all direct and transitive dependencies to latest compatible versions.
- Migrated all deprecated Flutter and Dart APIs to their modern equivalents:
  - Replaced all deprecated `.withOpacity()` with `.withValues()`.
  - Replaced deprecated `window` usage with `View.of(context)`.
  - Updated deprecated `MaterialStateProperty` to `WidgetStateProperty`.
  - Updated deprecated `canLaunch`/`launch` to `canLaunchUrl`/`launchUrl`.
  - Updated deprecated FontAwesome icons (`home` → `house`, `cog` → `gear`).
- Removed unnecessary null checks and dead code.
- Fixed all warnings and info messages from static analysis.
- Improved widget layouts to prevent RenderFlex overflows.

## [1.1.0] 2023-12-19
- Flutter version upgrade
- Deprecated components replaced with new components
- Component Props issues fixed
- Android build issues fixed

## [1.0.0] 2021-01-04

### Initial Release
