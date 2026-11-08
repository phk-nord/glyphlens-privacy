# GlyphLens Privacy Policy

This public repository contains the privacy policy for the **GlyphLens** browser
extension. It is intentionally separate from the private extension source so the
policy can be published without exposing the application code.

Published at:

**https://phk-nord.github.io/glyphlens-privacy/**

## Files

- `index.html` — the published policy page.
- `icon.svg` — GlyphLens icon used by the page.
- `.nojekyll` — tells GitHub Pages to serve the files as-is.
- `robots.txt` — allows search engines to index the policy.

## Updating the policy

1. Edit `index.html`.
2. Update the effective date and the "Changes to this policy" section.
3. Commit and push to `main`.
4. GitHub Pages redeploys automatically.

Keep the policy consistent with the Chrome Web Store **Privacy practices** tab
and with what the extension actually does. In particular, mention any new
endpoint, data type, permission, or third party before shipping it.

## Custom domain

When a domain is ready:

1. Add a `CNAME` file at the repository root containing only the hostname, for
   example `privacy.example.com`.
2. At the DNS provider, create a `CNAME` record for that hostname pointing to
   `phk-nord.github.io`.
3. In **Settings → Pages → Custom domain**, enter the same hostname.
4. Wait for the DNS check, then enable **Enforce HTTPS**.
5. Update the canonical link, policy URL in `index.html`, and the Chrome Web
   Store listing to the custom domain.

Prefer a subdomain such as `privacy.example.com` or
`glyphlens.example.com`; it avoids apex-domain A records and keeps the main
domain free for a portfolio or product site.

## Contact

Privacy questions: open an issue at
https://github.com/phk-nord/glyphlens-privacy/issues
