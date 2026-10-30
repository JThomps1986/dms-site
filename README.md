# DMS preview site

A static, read-only demo of DMS (a customisable data migration system) running on recorded sample data. There is no back end.

Deploy: connect this repository in Cloudflare with no build command and `npx wrangler deploy` as the deploy command. `wrangler.jsonc` serves the files as static assets and falls back to `index.html`, so deep links and refreshes work. Do not add a `_redirects` file with a `/* /index.html 200` rule: Workers static assets reject it as an infinite loop.

Sign in with any credentials. Changes are not saved.

Built from the `itg-front-end` repository with `npm run build:demo`.
