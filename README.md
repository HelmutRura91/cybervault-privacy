# Cyber Vault — Privacy Policy

Public hosting for the Cyber Vault Android app's privacy policy.

- Live URL: https://helmutrura91.github.io/cybervault-privacy/
- Source of truth: [`docs/play-store/privacy-policy.md`](https://github.com/HelmutRura91/vault/blob/master/docs/play-store/privacy-policy.md) in the (private) `vault` repo.

## Updating the policy

When the source-of-truth file changes, copy the body into `index.md` here and push. Two stripping rules to apply on copy:

1. Drop the `# Privacy Policy for Cyber Vault` h1 — `_layouts/default.html` renders it as part of the page header.
2. Drop the `Last updated: YYYY-MM-DD` line — the layout renders it from the date in the header markup. **Update the date in `_layouts/default.html` (the `<p class="updated">Last updated: ...</p>` line) when the policy itself changes.**
3. Drop the internal-only `<!-- TODO ... -->` HTML comment and the "Source-of-truth note" blockquote — both are dev-only annotations that don't belong on the public page.

## Theming

The page uses a custom dark layout (`_layouts/default.html`) with the Cyber Vault brand palette: dark navy `#0A0E1A` background, cyan `#00FFFF` + magenta `#FF00FF` accents, Orbitron Bold headings + JetBrains Mono Regular body via Google Fonts. No Jekyll theme is loaded; the layout is fully self-contained.
