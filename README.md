# Brightside Company website

Static site for Brightside Company.

- Site files live in `public/` (`index.html` + images). Only this folder is published.
- Hosted as a Cloudflare Worker with static assets (`wrangler.jsonc`).
- Every push to `main` builds and deploys automatically via Cloudflare Workers Builds.
