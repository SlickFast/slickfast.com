# slickfast.com

The SlickFast marketing site — one static page + a docs page. No framework, no build step.

- `index.html` — the site. All charts on it are SlickFast engine output (baked SVG/PNG from
  `packages/render-core/build-gallery.mjs` in the platform repo, plus one live hero render
  from `api.slickfast.com` via the keyless demo allowlist).
- `docs.html` — API reference, rendered client-side from `openapi.yaml` by Redoc.
- `openapi.yaml` — synced from the platform repo (`apps/api/openapi.yaml`).
- Hosted on GitHub Pages, custom domain `slickfast.com` (see `CNAME`).

Engine / MCP / API source: [SlickFast/slickfast](https://github.com/SlickFast/slickfast).
