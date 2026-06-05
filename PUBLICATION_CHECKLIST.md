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
- [ ] GitHub repo created or updated.
- [ ] Vercel Production deployment is READY.
- [ ] Root URL returns 200.
- [ ] `X-Robots-Tag` header verified.
- [ ] `robots.txt` verified.
