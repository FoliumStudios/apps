# Folium Studios (apps

Public support and privacy pages for the Folium Studios apps, served by
GitHub Pages at <https://apps.foliumstudios.com>. App stores require stable
public URLs for both, and the app repositories are private.

- `canhoto/support/`) Canhoto support page
- `canhoto/privacy/` (Canhoto privacy policy

Each page is in English at its base path, with `pt/` (Portuguese) and `es/`
(Spanish) versions) the same languages as the app. When changing one
language, change all three and bump the "last updated" date.

Plain HTML with one shared `style.css`; no build step. `CNAME` binds the
custom domain, which needs a DNS `CNAME` record `apps` →
`foliumstudios.github.io`.
