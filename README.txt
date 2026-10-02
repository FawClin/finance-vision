FINANCE AI — CLEAN PUBLIC PWA

This build contains ZERO personal finance data and is suitable for a public GitHub repository.

FIRST LAUNCH
- 12 empty months beginning with the current browser month.
- Opening balance = 0.
- No assets, loans, credit cards, premiums or budget rows.
- New users enter their own values from zero.

PERSISTENCE
- All data is saved locally in the browser/PWA under financeAI_v2_state.
- After data is entered or imported once, the latest saved values preload on future launches.

BACKUP
- Export creates a complete Finance AI v2 JSON backup containing the entire normalized state.
- Import accepts Finance AI v2 full-state backups.
- The older hard-coded Finance AI backup format must be converted once before import.
  This is intentional so no old personal baseline values are published in the GitHub source.

GITHUB PAGES
1. Upload every file in this folder to the repository root.
2. Settings -> Pages -> Deploy from branch -> main -> /(root).
3. Open the HTTPS site on iPhone Safari.
4. Share -> Add to Home Screen.
5. Import a Finance AI v2 backup, or start from zero.
