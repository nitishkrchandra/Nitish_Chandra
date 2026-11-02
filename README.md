# Nitish Kumar Chandra — Academic Website

A responsive academic site built entirely with HTML and CSS. No Jekyll, Ruby, JavaScript, third-party fonts, build step, or external CDN.

## Files
- `index.html` — homepage
- `research/index.html` — research areas
- `publications/index.html` — publication list (2021–2026)
- `cv/index.html` — concise CV
- `teaching/index.html` — teaching
- `site/style.css` — all styling
- `assets/images/bio-photo.jpg` — retained existing photo
- `.nojekyll` — disable Jekyll for GitHub Pages

The old Jekyll Markdown files are retained for archival purposes, but no longer drive the live HTML pages. To edit content, edit the appropriate HTML file directly.

## Publishing
GitHub Pages: Publish master branch from repository root. Existing project URL: https://nitishkrchandra.github.io/Nitish_Chandra/ . Relative asset/page links also work on a domain root.

Cloudflare Pages (separate hosting domain):
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Import Git repository.
2. Select this repository and production branch `master`.
3. Framework preset: None. Build command: `exit 0` or blank. Build output directory: `.` (repository root).
4. Deploy and test the resulting `*.pages.dev` URL on the affected university network. Ideally connect a custom domain.

A static redesign alone does **not** bypass university filtering of the github.io domain. Hosting must change if that domain is blocked. No alternate URL is guaranteed universally accessible.

Source for deployment configuration: https://developers.cloudflare.com/pages/framework-guides/deploy-anything/

Publication and profile content refreshed in November 2026 using the September 2026 CV and publicly available research records. Confidential patent details are omitted.