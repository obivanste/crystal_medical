# Crystal Medical Website (Static Frontend)

This repository contains the full source code for the **Crystal Medical** website — a **multi-page, static** medical services presentation site built with **HTML + CSS + JS** and a shared `assets/` directory.

The work in this repo includes ongoing structural improvements, content updates, page optimizations, and frontend fixes across service pages and the blog section.  [oai_citation:1‡GitHub](https://github.com/obivanste/crystal_medical)

---

## Tech Stack

- **HTML / CSS / JavaScript** (static website)
- Responsive UI components (template-style structure)
- Google Analytics (gtag) is embedded in pages (example in `cenovnik.html`).  [oai_citation:2‡cenovnik.html](file-service://file-3mWcC8Kj7gsyeSyzRXqa1g)

---

## Pages & Content

The site is organized as standalone HTML pages, including:

- **Home**
  - `index.html`  [oai_citation:3‡GitHub](https://github.com/obivanste/crystal_medical)
- **Services**
  - `usluge.html`
  - `hirurgija-lica.html`
  - `hirurgija-tela.html`
  - `genitalna-hirurgija.html`
  - `nehirurski-tretmani.html`
  - `lecenje-opekotina-i-rana.html`
  - `korekcija-oziljaka.html`  [oai_citation:4‡GitHub](https://github.com/obivanste/crystal_medical)
- **Clinic / Team / Contact**
  - `o-klinici.html`
  - `nas-tim.html`
  - `kontakt.html`  [oai_citation:5‡GitHub](https://github.com/obivanste/crystal_medical)
- **Pricing**
  - `cenovnik.html`  [oai_citation:6‡GitHub](https://github.com/obivanste/crystal_medical)
- **Blog**
  - `blog.html` (listing page)
  - `blog-1.html` … `blog-14.html` (individual posts)  [oai_citation:7‡GitHub](https://github.com/obivanste/crystal_medical)
- **Multi-language**
  - `index-english.html`
  - `индекс-русский-язык.html`  [oai_citation:8‡GitHub](https://github.com/obivanste/crystal_medical)

---

## Repository Structure (high level)

- `index.html` / other `*.html` pages (standalone pages)
- `blog.html` + `blog-*.html` (blog listing + blog posts)
- `style.css` (main stylesheet override/entry)
- `assets/` (theme assets: css/js/images/fonts/etc.)  [oai_citation:9‡GitHub](https://github.com/obivanste/crystal_medical)

---

## Run Locally

Because this is a static website, you can run it with any local web server.

### Option A) VS Code Live Server
1. Install **Live Server** extension
2. Right-click `index.html` → **Open with Live Server**

### Option B) Python simple server
From the repo root:

```bash
python -m http.server 8080
