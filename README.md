
# UK Migration Impact Dashboard (No-Code Deploy)

This folder contains a ready-to-use website that shows a live UK migration impact dashboard.

## Easiest way (no code): Deploy to Vercel
1. Go to https://vercel.com/new (create a free account if needed).
2. Click **Import** → **Upload** and drag-drop this whole ZIP.
3. Vercel will detect a **Vite + React** app automatically.
4. When asked for the **Build Command**, keep the default `npm run build`. Output directory is `dist`.
5. Click **Deploy**. In ~1–2 minutes, you get a public URL you can bookmark.

## How to update data sources later (optional)
- Open `src/App.jsx` and edit the `DATA_SOURCES` URLs near the top.
- If you have public CSV links (ONS, Home Office etc.), paste them in and redeploy.
- If left blank, the dashboard uses realistic sample data so it still works.

## Run locally (optional)
- Install Node.js 18+.
- In this folder, run:
  ```bash
  npm install
  npm run dev
  ```
- Open the printed local URL (e.g. http://localhost:5173).

## Notes
- Charts are built with [Recharts].
- Design is self-contained (no special UI libraries).

Enjoy! 🎉
