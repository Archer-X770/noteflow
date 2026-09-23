# Noteflow

An iPad-oriented notebook website with Apple Pencil input, pressure-sensitive pen strokes, highlighting, undo/redo, searchable tags, colored folders and subfolders, favorites, paper templates, text formatting, and backups.

## Publish with GitHub Pages

1. Create an empty repository named `noteflow` on GitHub. A public repository works with GitHub Free.
2. Put the files in this folder directly at the repository root (especially `index.html`). Do not upload the ZIP itself as the website.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select **main** and **/(root)**, and save.
4. Wait for GitHub to show the published website address, then open that address in Safari on iPad.
5. Optionally use Safari’s Share menu → **Add to Home Screen**.

Official publishing instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Apple Pencil

Open a note and tap **Apple Pencil**. Draw with the Pencil; drag a finger to scroll. Pressure is used when reported by the device/browser. The app does not implement native Pencil double-tap/squeeze gestures. **Finger** mode accepts both finger and stylus input. **Scroll** mode allows normal touch scrolling. Select **Type** to use the keyboard.

## Notes and privacy

The repository contains app code and sample notes only. Personal notes are stored in the current browser’s local storage and are not sent to GitHub. There is no account system or cross-device sync. Export backups regularly, especially before switching website addresses or clearing browser data. Files preview is unsupported. Old Noteflow v1 backups can be restored; v1 local data at the same website origin is migrated automatically without deleting the old copy.

## Offline behavior

After a successful hosted visit and service worker installation, the app shell can load offline. The first visit requires a connection. The service worker uses the network when available. Browser-managed storage is not a permanent backup.

## Run locally

From this directory: `python3 -m http.server 8000`, then visit `http://localhost:8000`.

## Validation

See TEST-RESULTS.md for automated logic checks and remaining device checks.
