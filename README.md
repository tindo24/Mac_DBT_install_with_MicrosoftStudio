# 🛠️ dbt Environment Setup on macOS for Microsoft Studio

A step-by-step installation guide for setting up a complete **dbt (data build tool)** development environment on macOS — covering SQL Server connectivity, VS Code, Python, and dbt itself.

📖 **Live site:** `https://yourusername.github.io/dbt-tutorial/`

---

## What's covered

| Step | Component | Notes |
|------|-----------|-------|
| 1 | Azure Data Studio | macOS replacement for SSMS |
| 2 | Visual Studio Code | Editor + recommended dbt extensions |
| 3 | Python 3.7+ | Installed via Homebrew or python.org |
| 4 | dbt-core | Core dbt framework via pip |
| 5 | dbt adapter | Database-specific connector (e.g. dbt-sqlserver) |
| 6 | ODBC Driver | Low-level database connectivity layer |

---

## Files

```
├── index.html      # Main tutorial page (hosted via GitHub Pages)
└── README.md       # This file
```

---

## Viewing locally

Just open `index.html` in any browser — no server or build step required.

```bash
open index.html
```

---

## Contributing / Adding content

This site is intentionally simple — a single HTML file — so it's easy to extend. Some ideas for future additions:

- `profiles.html` — how to configure `profiles.yml` for different adapters
- `first-project.html` — walkthrough of `dbt init` and your first model
- `troubleshooting.html` — common macOS errors and fixes
- A nav bar linking between pages

To add a page, create a new `.html` file in this repo and link to it from `index.html`.

---

## Deployment

This site is hosted via **GitHub Pages**. Any commit to the `main` branch automatically updates the live site within ~60 seconds.

To enable GitHub Pages on a fork:
1. Go to **Settings → Pages**
2. Set source to **Deploy from branch → main → / (root)**
3. Click **Save**

---

## Tech stack

- Pure HTML, CSS, and vanilla JavaScript — no frameworks, no build tools
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts
- Hosted on GitHub Pages (free)
