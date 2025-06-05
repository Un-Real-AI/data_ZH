# 📊 **Interactive Charts Gallery**

> A *purely static* GitHub Pages site for hosting and sharing fully‑interactive data visualisations. Think of this repo as an online portfolio: every chart is an **exported HTML file** that users can open, zoom, pan, and download – no servers, notebooks, or build scripts involved.

[![License](https://img.shields.io/github/license/USERNAME/REPO.svg)](LICENSE)
[![last-commit](https://img.shields.io/github/last-commit/USERNAME/REPO.svg)](https://github.com/USERNAME/REPO/commits/main)
[![GitHub pages](https://img.shields.io/badge/Live%20Site-online-brightgreen)](https://USERNAME.github.io/REPO/)

---

## 🗂️ Repository structure

```
├── charts/            # ← your interactive HTML files live here
│   ├── sales_trends_2024.html
│   ├── carbon_emissions_map.html
│   └── …
├── index.html         # Gallery landing page (auto‑includes every file in /charts)
├── assets/            # Optional static assets (images, CSS, favicon)
├── CNAME              # Optional – custom domain for GitHub Pages
└── README.md
```

> **Tip:** The default `index.html` is a tiny vanilla‑JS script that scans `charts/` at runtime. You can swap it for any static‑site generator or your own handcrafted page.

---

