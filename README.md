# Madhuri B. Patil — portfolio

Single-file personal site. Open `index.html` locally or publish with GitHub Pages.

## Publish on GitHub Pages
1. Create a public repo named `<your-github-username>.github.io`.
2. Add these files (`index.html`, `.nojekyll`, `README.md`) and push to `main`:
   ```bash
   git init && git add . && git commit -m "portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
   The site goes live at `https://<your-github-username>.github.io` within a minute or two.

## Edit content
All content is in plain JavaScript arrays near the top of the `<script>` block in `index.html`:
`JOBS`, `SYSTEMS`, `LAB`, `PATTERNS`, `SKILLS` (a trailing `*` marks "used in production"), `USES` (skill → systems map)
and `DEMOS` (links to the executive demo pages — share those pages publicly, or point them at your own hosting).
Product screenshots live in `assets/`; the social preview image is `og.png` (for LinkedIn/Twitter cards, set `og:image` to the absolute URL once deployed, e.g. `https://<user>.github.io/og.png`).

Shortcuts on the site: `⌘K` / `Ctrl+K` or `/` opens the command palette; the terminal in the About section accepts `help`.
