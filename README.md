

**Live (local) preview:** [http://127.0.0.1:5500/ASSIGNEMENT.HTML/A1.HTML](http://127.0.0.1:5500/ASSIGNEMENT.HTML/A1.HTML)

---

## Project Description

This repository contains a small static web project (Assignment A1). It is written using plain **HTML** and **CSS** (no JavaScript). The main page for this assignment is `A1.HTML` located inside the `ASSIGNEMENT.HTML/` folder.

The site is intended to be opened in a web browser. It was developed locally and can be served using a development Live Server or uploaded to GitHub Pages for public hosting.

---

## Features

* Static HTML pages
* Responsive-ish layout (depends on CSS in the repo)
* Clean, minimal structure suitable for a portfolio/assignment page

---

## File structure

```
ASSIGNEMENT.HTML/
├── A1.HTML           # Main assignment HTML file
├── styles.css        # (or cdd.css) CSS used by the page
├── assets/           # images, fonts, other assets (if present)
└── README.md         # (this file)
```

> Note: Replace `styles.css` with the actual CSS filename in your repo (e.g. `cdd.css`) if different.

---

## How to run (locally)

You have three simple options:

### 1) Open directly in browser

* Navigate to the project folder and double-click `A1.HTML` to open it in your browser.

### 2) Use Live Server (recommended for development)

* If you use VS Code, install the **Live Server** extension.
* Open the project folder in VS Code, open `A1.HTML`, then click **Go Live**. The page will be served at an address like `http://127.0.0.1:5500/ASSIGNEMENT.HTML/A1.HTML` (the exact port may vary).

### 3) Host on GitHub Pages (for public demo)

1. Create a GitHub repository and push the project files.
2. In the repository settings, enable **GitHub Pages** from the `main` branch (or `gh-pages` branch) and set the folder to `/` or `/docs` depending on where you put the files.
3. After a moment GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/ASSIGNEMENT.HTML/A1.HTML`.

---

## Install & push to GitHub (example commands)

```bash
# inside your project folder
git init
git add .
git commit -m "Initial commit - Assignment A1"
# create repo on GitHub, then:
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

If you want to use GitHub Pages and prefer the `gh-pages` branch:

```bash
# install gh-pages locally (optional) and deploy, or manually push to gh-pages branch
git checkout -b gh-pages
git push origin gh-pages
# then enable GitHub Pages to use gh-pages branch in repo settings
```

---

## Notes & Tips

* If your CSS filename is `cdd.css` (or something else), make sure the `<link rel="stylesheet">` path in `A1.HTML` matches the filename and relative path.
* Keep asset paths (images, fonts) relative and checked in to the repo so GitHub Pages can serve them.
* If any images are missing locally, add them to an `assets/` or `images/` folder and update the HTML paths.

---

## Contributing

If you want others to contribute:

* Add a short CONTRIBUTING.md explaining how to submit changes and run the project.
* Use clear commit messages and optionally enable issues/PRs on the GitHub repo.

---

## License

Add a license file if you want to specify reuse terms. Example: **MIT License**.

---

## Contact

If you want to include contact info, add an email or link to your GitHub profile here.

---

*Generated README — edit any section to better match your project details.*
