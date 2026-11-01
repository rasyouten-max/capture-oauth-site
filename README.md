# Capture OAuth informational site

This public repository hosts a **static, bilingual information site** for the private, owner-operated OAuth application named **Intelligence Monitor PROD clasp / Capture**.

It contains only public product descriptions, privacy information, terms, and presentation CSS. It does **not** contain OAuth client secrets, refresh tokens, Google account contents, research materials, or production source code.

## Files

- `index.html` — Homepage, identity and Google authorization purpose
- `privacy.html` — Privacy policy (Chinese / English)
- `terms.html` — Terms of use (Chinese / English)
- `style.css` — Local styles; no external JS, fonts, analytics, advertising, or cookie scripts

## Publish on GitHub Pages (free)

Repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.

The default GitHub Pages URL, once deployment succeeds, will be:
`https://rasyouten-max.github.io/capture-oauth-site/`

The domain `capture-rasyouten.duckdns.org` has been reserved by the owner but **is not configured as this site's custom domain**. Do not add a `CNAME` file or enter a custom domain unless DNS record compatibility and ownership verification have been validated. GitHub Pages requires CNAME for true subdomains, while DuckDNS's documented DNS controls are limited.

For the Google OAuth brand application, use the same exact reachable HTTPS homepage and privacy policy under one verified domain. Publication to GitHub Pages alone does not certify Google Search Console ownership or OAuth verification.

## Updates

Keep this public repository separate from the private intelligence-monitor source repository. Changes to OAuth scopes, storage or external provider sharing should be reflected in the privacy policy before public publication if they materially change the declared processing behavior.
