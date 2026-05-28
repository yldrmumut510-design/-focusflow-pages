# FocusFlow — Public website

Static marketing and legal pages for the FocusFlow iOS app. Published via [GitHub Pages](https://pages.github.com/).

**This repository contains only public website files.** It does not include app source code, Firebase configuration, API keys, or private project files.

## Pages

| File | URL (after publish) |
|------|---------------------|
| `index.html` | `/` |
| `privacy.html` | `/privacy.html` |
| `support.html` | `/support.html` |

## Local preview

Open any HTML file in a browser, or serve the folder:

```bash
cd focusflow-pages
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Publish to GitHub Pages

1. Repository: `yldrmumut510-design/-focusflow-pages`
2. Push only the contents of this folder (not the FocusFlow app repo).
3. On GitHub: **Settings → Pages → Build and deployment → Deploy from branch**
4. Branch: `main`, folder: `/ (root)`
5. After a few minutes, the site is live at:

   `https://yldrmumut510-design.github.io/-focusflow-pages/`

## App Store URLs

- Privacy Policy: `https://yldrmumut510-design.github.io/-focusflow-pages/privacy.html`
- Support: `https://yldrmumut510-design.github.io/-focusflow-pages/support.html`

## Contact

focusflow.uy@gmail.com

## Tech

- Plain HTML and CSS (`css/style.css`)
- System fonts only
- No analytics, tracking, or external JavaScript
- Light/dark mode via `prefers-color-scheme`
