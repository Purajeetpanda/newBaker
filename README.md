# Minimal, Honest Sourdough — Research & Steps (Root Deploy)
A single‑page, research‑informed sourdough guide. Local images first; if one fails, a WebGL 3D loaf renders and a small **Regenerate** button appears (only after failure).

## Publish from repo root
1) Create a new repo (or open yours).  
2) Upload all files in this folder to the **repo root** (you should see `index.html`, `.nojekyll`, and `assets/` at the top level).  
3) Go to **Settings → Pages** and set:  
   - Source: **Deploy from a branch**  
   - Branch: `main`  
   - Folder: **/** (root)  
4) Save and wait ~1–2 minutes. Your site will be at: `https://<username>.github.io/<repo>/`.

## Customize
- Replace images in `assets/images/`. The page randomly picks one for each `<img>`.
- Edit the content directly in `index.html` (all sections are plain HTML).

No Jekyll is used (due to `.nojekyll`). Just static files. Enjoy! 🥖
