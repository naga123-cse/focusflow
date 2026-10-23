# FocusFlow — Productivity & Task Manager

A responsive task manager built with plain HTML, CSS, and JavaScript.

## Features
- Add, edit, delete, and complete tasks
- Assign categories, due dates, priorities, and statuses
- Search tasks and filter by status
- Summary cards and a progress overview
- Local browser storage (`localStorage`)
- Responsive desktop and mobile layout
- No npm packages or framework required

## Run locally
Requirements: Python 3 and a modern browser (or open `index.html` directly).

```bash
git clone https://github.com/YOUR-USERNAME/focusflow.git
cd focusflow
python -m http.server 8000
```

Open http://localhost:8000.

## Deploy using GitHub Pages
1. Create a **public** GitHub repository named `focusflow`.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for the public URL shown there. Open it in an incognito/private browser to test.

## Known limitations
- Tasks are stored in the current browser only; there is no login, server database, or cloud sync.
- The progress overview is a simple status summary, not a time-tracking analytics chart.
- No push notifications or calendar integration.

## AI assistance
Disclose any AI tools you actually used in the submission. Review the code and describe a real issue you personally tested or fixed; do not invent a bug story.
