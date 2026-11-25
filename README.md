# CampusMate
AI-generated progressive web app (PWA), not a native APK. Run `python3 -m http.server 8000` in this folder, then open http://localhost:8000. For phone GPS and installation deploy the folder to an HTTPS static host (e.g. GitHub Pages). Run `node --test model.test.js` with Node 22. Internet needed for weather; tasks and cached shell work offline after service worker installation. No account or encryption; avoid sensitive tasks. Open-Meteo API: https://open-meteo.com/en/docs. Generated with ChatGPT; review and adapt before submission.

Manual checks pending: add task, reload, complete, undo, delete, clear, deny GPS, allow GPS, Dundee weather, offline weather failure, narrow and landscape layouts, keyboard and screen reader. Record actual outcomes and device/browser. No human testing claimed.

Proposal (new, not previously submitted): help students plan deadlines and travel around campus. Flow: launch → add task → sorted list → complete/delete; weather → choose Dundee or GPS → result/error. Core features: local tasks, live weather, optional location, offline shell.
