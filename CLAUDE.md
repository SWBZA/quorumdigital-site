# CLAUDE.md — quorumdigital-site

The public website of Quorum Digital Solutions (Pty) Ltd at quorumdigital.co.za:
plain static HTML on GitHub Pages (D18 in `../first-100/docs/DECISIONS.md`).

- No build step, no framework, no JavaScript. Pages are `index.html` files in
  folders; links are relative so the site also works before the domain points
  here. The shared look is `assets/style.css`.
- **No third-party requests**: no analytics, no cookies, no web fonts, no CDNs.
  The site must keep the promise the app makes.
- `privacy/` is generated from `../first-100/store-assets/PRIVACY_POLICY.md`
  (the source of truth); change the Markdown first, then the page.
- Copy follows first-100's rules: British English, no em-dashes joining
  sentences in our own copy, and only claims the app verifiably makes
  (`../first-100/store-assets/LISTING.md`). Never "your data never leaves your
  phone" while D19 is open.
- The Terms of use go up only after the legal review.
