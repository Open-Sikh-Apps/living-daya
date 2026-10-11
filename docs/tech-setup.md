# Tech Setup: Static Site + GitHub Pages

## Recommendation: Astro
- Built for content sites. It ships zero JavaScript by default, so pages load fast.
- Pages are written in Markdown, so `content/website-content.md` maps straight onto pages.
- Markdown footnotes (`[^id]`) render as numbered citations out of the box.
- Built-in i18n routing lets us add a **Punjabi (Gurmukhi)** version later, which matters for many Canadian Sikh readers.
- There's an official GitHub Action for deploying to GitHub Pages.

Alternatives:
- **Hugo**: a single binary with no Node.js, very fast. Its templating is harder to learn.
- **Eleventy (11ty)**: minimal and flexible, with less built in.

## Hosting plan
1. Build with Astro and deploy with GitHub Actions (`withastro/action`) to GitHub Pages.
2. Custom domain: add `public/CNAME` containing the domain (e.g. `livingdaya.ca`), then at the registrar:
   - apex domain: A records → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `www`: CNAME → `<github-username>.github.io`
   - then turn on "Enforce HTTPS" in the repo's Pages settings.
3. Fonts: Noto Sans Gurmukhi (Google Fonts) so Gurbani renders properly on every device.

The site is built once the content passes `docs/verification-checklist.md`.
