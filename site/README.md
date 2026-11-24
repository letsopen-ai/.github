# Static site

This change does not deploy the site.

To deploy later to Cloudflare Workers Static Assets, run `npx wrangler deploy` from the `site/` directory using an account authorized to deploy the Worker. Wrangler reads `wrangler.jsonc` and serves the files in `public/`.

The `letsopen.ai` custom domain will be attached later.
