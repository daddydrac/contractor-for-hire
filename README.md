# Joseph Hoeller — Vanilla HTML5 Marketing Site

This is a static GitHub Pages-ready marketing site. It does **not** require Jekyll, Ruby, Bundler, Sass, npm, a theme, or a build step.

## Deploy

1. Unzip the package.
2. Commit the contents to the root of your `github-username.github.io` repository.
3. In GitHub: **Settings → Pages → Deploy from a branch → root**.
4. Update the canonical URL in `index.html`, `robots.txt`, `sitemap.xml`, and the semantic files if your GitHub username is not `daddydrac`.

## Files

- `index.html` — semantic HTML5, RDFa, Schema.org, OpenGraph, JSON-LD.
- `assets/css/main.css` — vanilla CSS3 design and animations.
- `assets/pdf/joseph-hoeller-resume.pdf` — downloadable resume.
- `assets/semantic/profile.jsonld` — standalone Schema.org JSON-LD.
- `assets/semantic/profile.ttl` — RDF/Turtle profile.
- `.nojekyll` — keeps GitHub Pages from attempting Jekyll processing.

## Design notes

The layout follows the requested one-page portfolio format: sticky navigation, oversized split-name hero, proof metrics, expertise cards, public projects, case studies, skills, timeline, work philosophy, and contact CTA. It is static-first and SEO-friendly.
