# LabWebPage

A static website for the lab. Plain HTML/CSS/JS — no build step required.

## Structure

- `index.html` — page content and section layout (Home, People, Research, Publications, News, Contact)
- `css/style.css` — styling, responsive layout, light/dark theme
- `js/main.js` — mobile nav toggle
- `assets/images/` — photos (headshots, lab photos, etc.)
- `assets/pubs/` — publication PDFs

## Customize

Search `index.html` for bracketed placeholders (e.g. `[Lab Name]`, `&lt;Your Department&gt;`) and replace with real content. Add people, publications, and news items by duplicating the existing `<div>`/`<li>` blocks in their respective sections.

## Run locally

Open `index.html` directly in a browser, or serve it:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Works as-is on GitHub Pages, Netlify, Vercel, or any static host — just upload the folder contents.
