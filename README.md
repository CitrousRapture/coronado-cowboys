# Coronado Cowboys

Top-down 1986 U.S. Navy F-14A Tomcat roguelike extraction survivor (5 Theaters + Secret).

## Repo Structure
- `index.html` — Main game application
- `assets/` — Transparent 16-bit sprites (`sprite_*.png`) and audio tracks (`level1_bgm.mp3`, etc.)
- `manifest.json` — Mobile Add-to-Home-Screen fullscreen config
- `.nojekyll` — Tells GitHub Pages to serve static files directly

## Deploying on GitHub Pages
1. Create a public GitHub repository (e.g., `coronado-cowboys`) and upload/push all files from this folder to the `main` branch root.
2. In your repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, select `main` and `/ (root)`, and click **Save**.
4. *(Optional)* To connect a custom subdomain (like `play.topgunbuilders.net`), add a `CNAME` DNS record at your domain registrar pointing `play` to `<your-github-username>.github.io`, then enter `play.topgunbuilders.net` under **Custom domain** in GitHub Pages settings and enable **Enforce HTTPS**.

## Swapping Art & Music
Replace any PNG inside `assets/` with your own hand-drawn sprite using the same filename, or add new level music tracks as we build toward v1.0.
