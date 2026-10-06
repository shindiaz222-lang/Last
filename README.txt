SCHOOLTRACK — OFFLINE SCHOOL INVENTORY SYSTEM

Files:
index.html        Main app
style.css         Light/dark responsive design
app.js            Inventory functions, stock status, sounds, speech, reports, history
manifest.json     Installable web-app settings
service-worker.js Offline cache
click-sound.mp3   User-provided click sound
icon.svg          App icon

Features:
- Light and dark mode
- User-provided click sound on controls
- Sound on/off switch
- Automatic In Stock / Low Stock / Out of Stock status
- Automatic spoken stock announcements using the device browser speech feature
- Dashboard
- Inventory add/edit/delete
- Borrow/return/repair/missing/found
- Problem reports
- Transaction history
- JSON backup/restore
- CSV export
- Local offline storage

Low stock threshold defaults to 5 units.

GitHub Pages:
Upload all files to the repository root. In Settings > Pages, choose Deploy from a branch, main, /(root), then Save. Wait for the site to publish. Open the published site once while online so the offline cache can be installed.
