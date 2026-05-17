# smart-home-docs

A self-contained, single-file smart home guide, hosted as a static site on
Cloudflare Pages at [smarthome-docs.onit.systems](https://smarthome-docs.onit.systems).

## Deployment

Pushing to `main` triggers the [`deploy.yml`](.github/workflows/deploy.yml)
workflow, which deploys the site to the `smart-home-docs` Cloudflare Pages
project via `wrangler pages deploy`.

The workflow needs two secrets in the `cloudflare` environment:

- `CLOUDFLARE_API_TOKEN`
- `CLOUDFLARE_ACCOUNT_ID`
