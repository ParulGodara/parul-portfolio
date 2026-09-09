# Parul Godara — Portfolio

A single-page portfolio website. Static HTML/CSS/JS — no build step, no dependencies.

## Folder structure
```
parul-portfolio/
├─ index.html                     ← the whole website
├─ assets/
│  ├─ parul-hero.png              ← hero photo
│  ├─ parul-about.png             ← about photo
│  ├─ parul-standing.jpg          ← spare full-length photo
│  ├─ parul-godara-resume.pdf     ← résumé (linked in nav)
│  ├─ video-1.mp4 / video-2.mp4   ← "In motion" videos
│  └─ projects/                   ← project decks (PDF/DOCX) + tableau-dashboard.jpg
```

## Host it free on GitHub Pages
1. Create a new GitHub repository (e.g. `parul-portfolio`).
2. Upload **everything in this folder** (keep the `assets/` folder structure intact).
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** → **/ (root)** → Save.
4. Your site goes live at `https://<your-username>.github.io/parul-portfolio/` within a minute or two.

Tip: to use it as your main site, name the repo `<your-username>.github.io`.

## Before you publish — quick edits
- **LinkedIn link:** in `index.html`, search for `https://www.linkedin.com/` (Contact section) and paste Parul's real profile URL.
- Everything else (email, phone, projects, experience) is already filled in from the résumé.

## Update / add a project
Each project is one `<a class="card">` block in the Work section of `index.html`.
Drop a new file into `assets/projects/` and point the card's `href` to it.
