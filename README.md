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

## Adding student/member photos

Naming convention for `assets/images/`: `firstname-lastname.jpg`, all lowercase, hyphen-separated, no middle names/initials. Square-ish headshots, shoulders-up, `.jpg` or `.png`, 500×500px or larger.

Expected filenames for current members:

| Person | Filename |
|---|---|
| Dr. Anamika Prasad | `anamika-prasad.jpg` |
| Dr. Utpal Dhar | `utpal-dhar.jpg` |
| Rachelle A. Gomez-Guevara | `rachelle-gomezguevara.jpg` |
| Ariadna Herrera | `ariadna-herrera.jpg` |
| Kiyana Saeedian | `kiyana-saeedian.jpg` |
| Basil Usama Ahmad | `basil-ahmad.jpg` |
| Hilda Kafui Nuworku | `hilda-nuworku.jpg` |
| Alexi Switz | `alexi-switz.jpg` |
| Mohammad Salman Ibna Jamal | `salman-jamal.jpg` |
| Daniel Gallego Lopez | `daniel-gallegolopez.jpg` |
| Paula Gustin | `paula-gustin.jpg` |
| Zion Michael | `zion-michael.jpg` |
| Jalaica Ann Jaramillo | `jalaica-jaramillo.jpg` |
| Emily Idiarte | `emily-idiarte.jpg` |
| Jennifer Acevado | `jennifer-acevado.jpg` |
| Giana Lopez | `giana-lopez.jpg` |
| Paula Gait | `paula-gait.jpg` |
| Paulina Perez | `paulina-perez.jpg` |
| Daniela Lozano Infante | `daniela-lozanoinfante.jpg` |
| Vitaliia Arifova | `vitaliia-arifova.jpg` |
| Hafsa Mariam | `hafsa-mariam.jpg` |
| Nestha Venepally | `nestha-venepally.jpg` |
| Jhoan Gonzales | `jhoan-gonzales.jpg` |
| Aaron Teijeiro | `aaron-teijeiro.jpg` |

LinkedIn URLs (optional, collected alongside photos) can be dropped in a plain list and handed over when ready — no special format needed.
