# Full Site Bundle

Contains:
- `index.html` (homepage)
- `projects/*.html` (5 themed project pages)
- `css/style.css` (homepage styles), `css/project.css` (project theme)
- `images/*` placeholders (no 404s) + `favicon.ico`
- `.nojekyll` to disable Jekyll

## Deploy
```
git checkout main
cp -R * /path/to/your/repo   # or unzip and copy
git add .
git commit -m "Add full site bundle"
git push
```
Make sure GitHub Pages (Settings → Pages) points to **main / root**.
