# policies

Privacy policies for published iOS apps, served by GitHub Pages.

This repository is public **only** so the policy pages resolve at a URL that App Store
review and AdMob can open. It contains no application source.

| App | Page | Purpose |
|---|---|---|
| Converter | [converter.html](converter.html) | Privacy policy (App Store + AdMob require it) |
| Converter | [converter-support.html](converter-support.html) | Support URL (App Store listing requires it) |

Every App Store listing needs **both** a privacy policy URL and a support URL. Neither
may 404 — reviewers open them.

## Adding pages for a new app

1. Copy `converter.html` and `converter-support.html`, renaming for the new app
2. Edit the contact address and app-specific sections
3. Add rows to the table above and links in `index.html`
4. Commit and push — GitHub Pages redeploys automatically

## Hosting

Settings → Pages → Deploy from a branch → `main` / `(root)`.
