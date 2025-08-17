
# Football Hub (v2)

A polished, responsive football website you can host on **GitHub Pages**.  
Built with semantic HTML, modern CSS, and a tiny bit of vanilla JS.

## Quick start (local)
Use a local server to preview (so `fetch` for JSON works):

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Deploy to GitHub Pages
1. Create a new repository, e.g. `football-hub`.
2. Upload all files in this folder (or `git push`).
3. In GitHub, open **Settings → Pages**.
4. Set Source to **Deploy from a branch**, select **main** and **/(root)**.
5. Save — after a minute your site will be live.

### Customize
- Update `assets/data.json` with real fixtures, table, and scorers.
- Change colors in `assets/styles.css` under `:root`.
- Replace hero image by editing `.hero-card .media` background-image.
