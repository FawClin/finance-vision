FINANCE VISION — FINAL PWA PACKAGE

FILES
- index.html                Main app
- manifest.json             PWA manifest
- service-worker.js         Offline cache/update support
- finance-vision-logo.png   Finance Vision branding
- evisionsoft-logo.png      Evisionsoft splash branding
- icon-192.png              PWA icon
- icon-512.png              PWA icon
- apple-touch-icon.png      iPhone home-screen icon

GITHUB PAGES
1. Create/open your GitHub repository.
2. Upload ALL files in this folder to the repository root. Do not upload only the ZIP.
3. Commit the files.
4. GitHub repository -> Settings -> Pages.
5. Source: Deploy from a branch.
6. Branch: main, Folder: /(root), then Save.
7. Wait for GitHub Pages to publish the HTTPS site.
8. Open the HTTPS address in Safari on iPhone.
9. Share -> Add to Home Screen.

DATA / BACKUPS
- App data is local to the hosted Finance Vision URL.
- Export creates a complete JSON state backup with financeVisionSchema=1.
- On iPhone/PWA, Export first opens the native Share sheet so you can Save to Files.
- Import restores a supported Finance Vision or converted Finance AI full-state backup.
- Before every future app update, export a backup first.
- Future app versions should preserve/migrate financeVisionSchema so old backups continue to import.

UPDATING THE PWA LATER
- Replace the repository files with the new version and commit.
- The service worker uses network-first loading for index.html, so the app can pick up published updates while retaining offline support.
- User finance data is stored separately in localStorage and is not inside index.html.
