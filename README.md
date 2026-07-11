# Dhivya — Portfolio

A single-page developer/UI-UX portfolio built with plain HTML, CSS, and JavaScript (no build step, no dependencies).

## Structure
```
portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── assets/
    └── profile.jpg   ← add your photo here
```

## Before you publish — 2 things to update

1. **Your photo**: drop an image into `assets/` named `profile.jpg` (portrait orientation works best, roughly 800×1000px). Until you add it, the hero shows a placeholder box.
2. **Contact details**: open `index.html`, search for `Contact` section, and replace:
   - `youremail@example.com` → your real email
   - `linkedin.com/in/your-linkedin-handle` → your real LinkedIn URL (appears twice)
   - `+91 00000 00000` → your real phone number
   - Also double-check the GitHub link already points to `github.com/Dhivya-web-maker`.

## Deploy on GitHub Pages (free, live in ~2 minutes)

1. Create a new repository on GitHub, e.g. `dhivya-portfolio`.
2. Upload these files (or push via git — see below) keeping the folder structure intact.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save. GitHub gives you a live URL like `https://<your-username>.github.io/dhivya-portfolio/` within a minute or two.

### Or push via terminal
```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/dhivya-portfolio.git
git push -u origin main
```
Then enable Pages as above.

## Customizing further
- Colors and fonts are defined as CSS variables at the top of `css/style.css` (`:root { ... }`) — change them once, they apply everywhere.
- Sections are independent blocks in `index.html` in this order: Hero → About → Skills → Experience → Contact. Reorder by moving `<section>` blocks.
- Scroll-reveal and active-nav-highlight behavior live in `js/script.js` — no external libraries used.
