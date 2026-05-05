# LeaderPalooza 2026

Festival-style landing page for the CBP Leadership event — June 24, 2026, TUDUM Theater, Los Angeles.

Single `index.html` with all CSS/JS inline. No build step required.

## Deploying to GitHub Pages

1. **Create a GitHub repo** at github.com → New repository. Name it something like `leaderpalooza`. Keep it private if needed; GitHub Pages works on private repos with a paid plan.

2. **Push the folder:**
   ```bash
   cd ~/Desktop/Leaderpalooza
   git init
   git add .
   git commit -m "Initial LeaderPalooza site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/leaderpalooza.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:** Repo → Settings → Pages → Source: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)` → Save.

4. Your site will be live at `https://YOUR-USERNAME.github.io/leaderpalooza/` within ~2 minutes.

5. **Embed in Google Sites:** Insert → Embed → paste the URL above.

## Files

- `index.html` — the whole site (HTML + CSS + JS inline)
- `Logo.jpg` — hero logo
- `.gitignore` — ignores macOS junk
