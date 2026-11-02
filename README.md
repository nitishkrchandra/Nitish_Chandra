# Nitish Kumar Chandra — Academic Website

A responsive, dependency-free academic website maintained with HTML and CSS. No Jekyll, Ruby, Node, external fonts, or external JavaScript.

## Site structure

- `index.html` — academic homepage and research highlights
- `research/index.html` — research overview and current projects
- `publications/index.html` — journal articles, conference/workshop papers, and preprints
- `honors/index.html` — honors, awards, conference presentations, research schools, peer review, and training
- `teaching/index.html` — teaching assistantships
- `cv/index.html` — web-based curriculum vitae
- `site/style.css` — all layout, typography, responsive and print styles
- `assets/images/bio-photo.jpg` — original site portrait

Update the HTML files directly; no build step is required. The old Jekyll source files remain in the repository for historical reference, but `.nojekyll` ensures the static HTML is served.

## Hosting

GitHub Pages should publish the `master` branch from the repository root. The site uses relative links and works at `/Nitish_Chandra/` or at a custom domain root.

If a campus network blocks `github.io`, changing the theme will not resolve the network block. A separate hosting address such as Cloudflare Pages or a custom domain needs separate deployment and testing.

## Academic content

Academic information updated in November 2026 from `Nitish_Chandra_CV_Yale.pdf` (October 2026) and the earlier academic profile. Current papers in progress are explicitly separated from public publications. No confidential or intellectual-property-specific material is included.