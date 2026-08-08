# Sarojini Boga — Personal Website

A single-page personal site for Sarojini Boga, Women's Health Educator,
focused on perimenopause & menopause awareness. Plain HTML/CSS/JS —
no build step, no dependencies. Ready to publish on GitHub Pages.

## Files

```
sarojini-website/
├── index.html      the whole site (one page, anchor-linked sections)
├── styles.css      all styling
├── script.js       scroll reveal, sticky nav, mobile menu
└── assets/
    ├── avatar.jpg          square face-crop (used for social preview)
    ├── hero.png            feathered bust portrait used in the hero
    ├── favicon.png          512x512 monogram favicon
    ├── favicon-192.png
    └── favicon-32.png
```

## Publish it on GitHub Pages (free, ~5 minutes)

1. Create a new **public** repository on GitHub — e.g. `sarojini-boga.github.io`
   for a bare `yourusername.github.io` URL, or any name like `sarojini-site`
   for a `yourusername.github.io/sarojini-site` URL.
2. Upload everything **inside** this `sarojini-website` folder to the repo
   root (index.html, styles.css, script.js, assets/ — not the folder itself).
   Easiest way, from this folder:

   ```bash
   git init
   git add .
   git commit -m "Launch site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. On GitHub: go to the repo → **Settings → Pages** → under "Build and
   deployment", set **Source** to `Deploy from a branch`, branch `main`,
   folder `/ (root)` → **Save**.
4. Wait 1–2 minutes, then visit the URL GitHub shows on that same page
   (something like `https://<your-username>.github.io/<repo-name>/`).

## Things worth customizing later

- **Contact**: currently only the email `sarojini9575@gmail.com` is shown.
  Phone number and date of birth from the original CV were left out
  on purpose, since this page is public — add them back in `index.html`
  only if you're comfortable with that being visible to anyone.
- **Social links**: no Instagram/LinkedIn links are included since none
  were provided. Add them to the `.nav-links` or footer in `index.html`
  whenever ready.
- **Video**: the trailer embed points at
  `https://www.youtube.com/embed/oBUVhSJQbio` inside `#session` in
  `index.html` — swap the ID to feature a different session.
- **Photo**: `assets/hero.png` and `assets/avatar.jpg` were cropped from
  the mall photo provided. Swap either file (keep the same filename) to
  update the portrait without touching any code.
