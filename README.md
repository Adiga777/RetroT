
# RetroZone 2000 — Static Site

A single-file retro website (late-90s/early-2000s vibe) with an in-page login modal (demo only).

## Demo Credentials
- **Username:** `demo`
- **Password:** `password`

## Run Locally
1. Open `index.html` in your browser **or**
2. In VS Code, install the **Live Server** extension → Right-click `index.html` → **Open with Live Server**.

## Deploy
### GitHub Pages
1. Create a new GitHub repo and upload `index.html` (and this README).
2. Go to **Settings → Pages**.
3. Set **Source** to your default branch (e.g., `main`) and folder `/root`.
4. Your site will be available at `https://<your-username>.github.io/<repo>/`.

### Netlify (Drag & Drop)
1. Go to https://app.netlify.com/drop
2. Drag the project folder to deploy. Netlify will give you a live URL instantly.

### Vercel
1. `vercel` (CLI) or import the repo at https://vercel.com/new
2. Deploy as a static site.

## Notes
- The login is **client-side only** (localStorage). Do **not** use for real authentication.
- External GIFs are referenced via public URLs; internet connection required to see them.
