# Project Sync for Acode

**Two-way local folder synchronization for Acode Editor on Android.**

Sync projects between Terminal Public and any second folder you authorize in Acode, including supported internal-storage and removable SD-card locations.

## Highlights

- Two-way syncing of files and nested project folders.
- Manual preview, Sync Now, and automatic periodic scanning (including 1- and 3-second interval options).
- Supports HTML, CSS, JavaScript, React and Next.js source projects; excludes common generated folders.
- Detects conflicts rather than blindly overwriting independently edited files.
- Optional removal mirroring with safeguards and private recovery history.
- Source/destination picker, activity diagnostics, and Acode sidebar refresh.

**Important:** Auto syncing requires Acode to remain active. File deletions are optional, and private recovery data may disappear if Acode's application data is cleared. Keep an independent backup. This is not cloud or GitHub synchronization.

**Developer:** Mohsin Ali — MERN Stack Developer & JavaScript Specialist  
**Source:** https://github.com/HowdyMohsin/acode-project-sync  
**Portfolio:** https://mohsin-ali--portfolio.vercel.app/

## Hidden files and folders

By default the scanner skips files and folders beginning with `.` anywhere under the selected roots (for example `.acode-snippets`, `.local`, `.npm`, `.bashrc`). Settings → Advanced exclusions has an opt-out checkbox. Some safety exclusions such as `.git` and `.env` always remain active. Excluded files already present on storage are not deleted.

## v4.4.4 — Remember selected folders

Project Sync now stores selected folder paths and sync history in its private IndexedDB, with a localStorage fallback, so reopening Acode can restore the previous configuration. If Android revokes a storage permission, use the access test and reselect the affected folder.
