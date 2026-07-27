# RideU Landing Page — GitHub Pages Setup

This repo contains a single static file, `index.html`, which is the full RideU landing page (bilingual ES/EN, phone mockup, savings calculator, waitlist form, app showcase carousel).

## Deploy with GitHub Pages (free hosting)

1. **Create a repo** (or use an existing one) on GitHub — e.g. `rideu-landing`.
2. **Add `index.html` to the root** of the repo (not inside a subfolder), either by:
   - Dragging it in via **Add file → Upload files** on the repo page, or
   - Using git locally:
     ```bash
     git clone https://github.com/yourusername/rideu-landing.git
     cd rideu-landing
     cp ~/Downloads/index.html .
     git add index.html
     git commit -m "Add RideU landing page"
     git push
     ```
3. **Enable Pages:**
   - Go to your repo → **Settings → Pages**
   - Under "Build and deployment", set **Source** to `Deploy from a branch`
   - Set **Branch** to `main` (or `master`) and folder to `/ (root)`
   - Click **Save**
4. **Wait 1–2 minutes**, then your site will be live at:
   ```
   https://yourusername.github.io/rideu-landing/
   ```
   GitHub will show you the exact URL at the top of the Pages settings once it's built.

## Notes

- Everything (HTML, CSS, JS) is self-contained in `index.html` — no build step, no dependencies to install.
- If you ever want a custom domain instead of the `github.io` URL, that's also configurable from the same **Settings → Pages** screen (there's a "Custom domain" field).
- Repo name doesn't need to be `rideu-landing` — use whatever you like, just make sure `index.html` sits at the root of whichever branch/folder you point Pages at.
