# margo.stoic.codes

Personal landing page of Margarita Ushakova — community builder & governance practitioner.

- `index.html` — the page (self-contained, no build step)
- `Ushakova_CV.pdf` — public CV, linked from the contact section
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy

Served via GitHub Pages: Settings → Pages → "Deploy from a branch" → `main` / `/ (root)`.
Live at https://stoic-codes.github.io/margo/

## Custom domain (optional)

Settings → Pages → Custom domain → `margo.stoic.codes`, then add a DNS CNAME
record: `margo` → `stoic-codes.github.io`. After it's live, update the
canonical URL in `index.html` (marked with a comment in the head).
