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
- [ ] Vercel Production deployment is READY.
- [ ] Root URL returns 200.
- [ ] `X-Robots-Tag` header verified.
- [ ] `robots.txt` verified.

## Current External Blocker

- Vercel connector can list projects but does not deploy from this local folder.
- `npx vercel@latest deploy --prod --yes` failed because the available token was rejected by Vercel.
- Vercel Production can resume after a valid Vercel CLI login/token is available.
