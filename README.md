# OpenLeaf Studio — Vercel-Ready Flat Repository

This repository is structured for instant, zero-error deployment on **Vercel** and **GitHub Pages**:
- `index.html` is placed at the repository root (no nested `public/` folder required).
- `Dockerfile` is removed so Vercel does not trigger `buildah` container builds.
- `vercel.json` has no legacy `rewrites`, eliminating the Vercel backend framework rewrite warning.
- `api/compile.js` runs automatically as a Vercel Serverless Function at `/api/compile`.
