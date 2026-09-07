# RICH — Privacy Policy

Public hosting for the RICH privacy policy, so App Store Connect has a URL to link to.
The app's source lives in a separate private repo; nothing here but the page.

**Live:** https://yysu-org.github.io/rich-privacy/

App Store Connect fields:

- Privacy Policy URL: https://yysu-org.github.io/rich-privacy/
- Support URL: https://yysu-org.github.io/rich-privacy/support.html

`index.html` is the English + 繁體中文 policy in one file, no dependencies.
`support.html` is the matching support page.

## First deploy

GitHub Pages is not on until someone with repo admin turns it on once
(Settings cannot be flipped by the API token we have):

1. Open https://github.com/yysu-org/rich-privacy/settings/pages
2. Build and deployment → Source: **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)` → Save

After the first Pages build, the two URLs above should load.

## Updating

The canonical copy lives at `docs/privacy-policy.html` and `docs/support.html` in the app repo. Edit it there,
copy it here as `index.html` / `support.html`, and push — GitHub Pages redeploys on push to `main`.
Bump the "Last updated" date in both language sections when the wording changes.
