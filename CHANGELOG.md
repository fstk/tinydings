# Changelog

All notable changes to Tinydings are listed here, newest first.

## [Unreleased]

### Added
- This changelog and structured release notes for every version.

## [0.3.0] - 2026-11-10

### Changed
- The app is now signed with a Developer ID and notarized by Apple. macOS no longer blocks it on first launch, it only asks you to confirm opening an app downloaded from the internet.
- Simplified installation instructions (no more "Open Anyway" or `xattr` step).

No functional changes compared to 0.2.3.

## [0.2.3] - 2026-10-21

### Changed
- The zip now contains the readme in English (`README.md`) and German (`README.de.md`).

## [0.2.2] - 2026-10-21

### Changed
- New app identifier `io.github.fstk.tinydings`. You need to enter your API key again once, the settings are reset as well.
- No build paths inside the app anymore.
- The MIT license file is included in the zip.

## [0.2.1] - 2026-10-21

### Changed
- New app icon (pink background, light green symbol).

## [0.2] - 2026-10-21

### Added
- Language switch (System, Deutsch, English) in the settings.

## [0.1.1] - 2026-10-21

### Changed
- The app is now called Tinydings.

### Fixed
- The "no API key" hint disappears right after you enter a key in the settings.

## [0.1] - 2026-10-20

### Added
- First beta: drop images (PNG, JPEG, WebP) onto the window or the Dock icon and compress them with the TinyPNG API.
- Output modes: overwrite the original (optionally moving it to the Trash first) or write to a subfolder (default `tiny`).
- Per-file status with size before/after and savings, 4 images processed in parallel.
- Your own TinyPNG API key, stored in the Keychain.
