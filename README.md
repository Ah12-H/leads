# Mapillary App Starter (Static Site)
Created: 2025-08-26

This bundle gives you simple pages to satisfy Mapillary's app registration fields. You can host them on GitHub Pages, Netlify, or any static hosting.

## Files
- `index.html` — landing page (Website URL)
- `privacy.html` — basic privacy policy
- `terms.html` — simple terms
- `callback.html` — redirect/callback page that shows any `?code=` parameters

## Quick Hosting (GitHub Pages)
1. Create a new GitHub repo, add these files to the root, commit, and push.
2. In repo **Settings → Pages**: choose branch `main` (or `master`) and root `/`.
3. Your site will be live at something like: `https://YOUR-USER.github.io/YOUR-REPO/`.

## What to paste in Mapillary's Developer form
- **Application Name**: Junk Car Finder
- **Website URL**: `https://YOUR-USER.github.io/YOUR-REPO/`
- **Callback / Redirect URL**: `https://YOUR-USER.github.io/YOUR-REPO/callback.html`
- **Privacy Policy URL**: `https://YOUR-USER.github.io/YOUR-REPO/privacy.html`
- **Terms URL**: `https://YOUR-USER.github.io/YOUR-REPO/terms.html`
- **Contact Email**: your email

> For the free imagery browsing use case, you typically only need the **Client Token** from the app after it's created. You can then call the Mapillary Graph API by passing `?access_token=MLY|...` as a query parameter (or `Authorization: OAuth MLY|...`).

