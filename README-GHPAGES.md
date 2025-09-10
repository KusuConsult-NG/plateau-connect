# Plateau Connect – GitHub Pages Build (Static)

This folder is ready to deploy on **GitHub Pages** as-is. It uses **localStorage** to emulate the backend so everything runs client-side (no servers).

## How to publish
1. Create a new repo (e.g., `Plateau-Connect`).
2. Upload all files in this zip to the repo root (or to `/docs`).
3. In **Settings → Pages**: 
   - Source: `Deploy from a branch`
   - Branch: `main` (root) or `main` `/docs`
4. Visit the Pages URL (e.g., `https://<your-username>.github.io/<repo>/`).

**SPA tip**: Include `404.html` (copy of index) for client-side routing fallback.
