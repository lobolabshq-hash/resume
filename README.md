# Eduardo Whittington — Resume Site

**Project folder:** `/Users/mobilewolf/Desktop/resume-site`

| Link | URL |
|------|-----|
| **GitHub repo** | [github.com/SOYLOBO/resume](https://github.com/SOYLOBO/resume) |
| **Live site** | [soylobo.github.io/resume](https://soylobo.github.io/resume/) |

A modern, clean, fast one-page resume site tailored for the **Creative Strategist, Paid Social** role at Jones Road Beauty.

## Connect to Git (one command)

In **Terminal**, paste and run (from your project folder):

```bash
cd /Users/mobilewolf/Desktop/resume-site && chmod +x publish-to-github.sh && ./publish-to-github.sh
```

This initializes git (if needed), commits your files, and pushes to [github.com/SOYLOBO/resume](https://github.com/SOYLOBO/resume). If you get a 404 on the live site, turn on **Settings → Pages** in the repo and choose **Deploy from branch** → `main` → `/ (root)`.

## What's included

- **index.html** — Semantic, accessible HTML with your summary, skills, AI workflow, experience, education, and links
- **styles.css** — Minimal CSS: warm neutrals, DM Serif Display + DM Sans, print-friendly

No JavaScript. Fast load, works everywhere.

## Run locally

Open `index.html` in a browser, or use a simple server:

```bash
# Python 3
python3 -m http.server 8000

# Then open http://localhost:8000
```

## Publish to GitHub (SOYLOBO)

Repo: **https://github.com/SOYLOBO/resume**

1. **In Terminal**, go to this folder and run:
   ```bash
   cd /Users/mobilewolf/Desktop/resume-site
   chmod +x publish-to-github.sh
   ./publish-to-github.sh
   ```

2. **Turn on GitHub Pages** so the site is live:
   - Open **https://github.com/SOYLOBO/resume**
   - **Settings** → **Pages** → **Source**: “Deploy from a branch”
   - **Branch**: `main` → `/ (root)` → **Save**
   - In a minute or two the site will be at: **https://soylobo.github.io/resume/**

Use that URL in your resume and cover letter where it says `Portfolio: [add link]`.

## Other deployment options

- **Netlify:** Drag this folder to [netlify.com/drop](https://app.netlify.com/drop) for an instant URL
- **Vercel:** `npx vercel` in this folder

## Customize

- **Contact:** Edit the hero and footer in `index.html`
- **Colors/fonts:** Adjust `:root` in `styles.css`
- **Print/PDF:** Use the browser's Print → Save as PDF for a clean one-doc version
