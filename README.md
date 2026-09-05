# coovadia-nyoka portfolio

Static portfolio site for Coovadia Nyoka. Plain HTML/CSS, no build step.

## Deploy to GitHub Pages (5 minutes)

1. Create a new public repository named exactly `cnyoka.github.io` on GitHub.
2. Upload everything in this folder to the repository root (index.html must sit at the root). Either drag-and-drop on github.com, or:

   ```
   git init
   git add .
   git commit -m "Portfolio v1"
   git branch -M main
   git remote add origin https://github.com/cnyoka/cnyoka.github.io.git
   git push -u origin main
   ```

3. The site goes live at https://cnyoka.github.io within a minute or two. No settings needed for a repo with this name.

## Custom domain (optional, ~$12/year)

1. Buy the domain (e.g. coovadianyoka.com) at any registrar.
2. In the repo: Settings > Pages > Custom domain > enter the domain, and tick "Enforce HTTPS" once it verifies.
3. At the registrar, add these DNS records:
   - A records for `@` pointing to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME record for `www` pointing to `cnyoka.github.io`
4. Update the CV header and LinkedIn with the domain.

## Updating content

- CV: replace `assets/Coovadia_Nyoka_CV.pdf` (keep the filename so links don't break).
- All page content is plain HTML; edit and push.

## Files

- `index.html` — positioning + four analytics projects
- `weird-leaf.html` — the financing case study (chart is inline SVG, built from the original workbook data)
- `about.html` — background and contact
- `style.css` — all styling
- `assets/Coovadia_Nyoka_CV.pdf` — CV download (currently the Business Analyst version)
