## 4.4.4 — Folder selection persistence

- Store Folder A and Folder B selections in private plugin storage, instead of unknown Acode settings keys.
- Restore selections and sync ledgers before initializing the sidebar after app restart.
- Keep a second persistent copy when browser local storage is available.
- Surface storage failures rather than silently saying paths are saved.
- Preserve existing UI and synchronization behavior.

# Changelog

## 4.4.3 — Dot-file exclusions and input contrast

- Skip all files and folders whose names start with `.` by default, at every directory level.
- Added a Settings → Advanced exclusions toggle to opt into scanning other dot-prefixed names; built-in protected exclusions still apply.
- Existing copies of excluded files are **not** removed by the exclusion change.
- Force readable light input text, placeholders, caret, and focused fields across Acode themes and Android WebViews.
- Fix text-field edits redrawing the panel on blur, which could interrupt a Save tap.
- Kept the existing plugin ID, configuration storage, recovery database, and two-way sync behavior.

# Changelog

## 4.4.2 — Public repository preparation

- Updated public-facing plugin name to **Project Sync for Acode** for easier discovery.
- Added GitHub repository metadata and searchable plugin keywords.
- Added expanded installation, safety and contribution documentation.
- Optimized the blue double-arrow icon to fit Acode's documented size limit.
- Preserved the existing plugin ID and synchronization behavior; no sync engine redesign in this release.

## 4.4.1 — Blue circular arrows icon

- Updated Project Sync branding with a blue double-arrow icon.
- Retained two-way local sync, private recovery, and the existing settings.

## Earlier releases

See repository history for previous development iterations. This changelog does not imply that every device or storage provider is fully tested.
