# Publication Checklist

## Sensitivity

- [x] Public viewing approved by Kevin.
- [x] No raw prompts or conversation text.
- [x] No local filesystem paths in the public page.
- [x] No account credentials, API keys, or billing records.
- [x] USD spend is not estimated without a billing source.

## Indexing Controls

- [x] `index.html` has `meta robots` noindex.
- [x] `robots.txt` disallows crawling.
- [x] `vercel.json` sets `X-Robots-Tag`.

## Verification

- [x] Local visual check.
- [x] Desktop bright-theme screenshot rendered.
- [x] Mobile bright-theme screenshot rendered at 430px width.
- [x] GitHub repo created or updated.
- [x] Vercel Production deployment is READY.
- [x] Root URL returns 200.
- [x] `X-Robots-Tag` header verified.
- [x] `robots.txt` verified.
- [x] Non-site files are excluded from Vercel deployment.

## Current External Blocker

- Earlier CLI attempts failed only when passing the Codex token file.
- Deploy succeeded after using the existing local Vercel CLI login with no explicit token.
- Stable URL: `https://codex-token-burn-dashboard.vercel.app/`
