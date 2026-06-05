# Production Log

## 2026-06-05

- Artifact: Codex Token Burn Dashboard
- Local path: `outputs/codex-token-burn-dashboard`
- Public posture: approved for public repo and Vercel Production by Kevin
- Indexing posture: keep noindex, nofollow, noarchive
- Data posture: aggregate token usage only; no prompts, paths, task contents, credentials, or billing records
- GitHub repo: `https://github.com/Kevin-Yeh-egroup/codex-token-burn-dashboard`
- Commit: `e755ff1`
- Vercel target: `codex-token-burn-dashboard`
- Local verification: `npm run check` passed; Chrome headless rendered `local-preview.png`
- GitHub verification: public repo created and `main` pushed
- Vercel attempt 1: CLI deploy with team scope failed because token lacked account access
- Vercel attempt 2: CLI deploy without scope failed because token was invalid
- Vercel API check: `/v2/user` returned 403 with the available token
- Verification status: Vercel Production deployment blocked by missing valid Vercel deploy authentication

## 2026-06-05 Bright Theme Revision

- Updated presentation to a brighter, softer palette for non-technical readers.
- Added `PRESENTATION_NOTES.md` with simulated agent discussion and extension ideas.
- Local verification: `npm run check` passed; Chrome headless rendered desktop and 430px mobile previews.

## 2026-06-05 Production Deployment

- Vercel project: `codex-token-burn-dashboard`
- Vercel project ID: `prj_mLJtLf35zU4Ju1PBmlbrY8nkoREG`
- Stable URL: `https://codex-token-burn-dashboard.vercel.app/`
- Deployment ID: `dpl_43oCtzb5fiuje4fSM1coY3jykFMm`
- Production target: `READY`
- GitHub-backed commit deployed: `e247126`
- HTTP verification: root returned `200 OK`
- Noindex verification: root returned `X-Robots-Tag: noindex, nofollow, noarchive`
- Robots verification: `/robots.txt` returned `User-agent: *` and `Disallow: /`
- Deployment-scope verification: preview images and markdown notes returned `404`
