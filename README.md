# DMS preview site

A static, read-only demo of DMS (a customisable data migration system) running on recorded sample data. There is no back end.

Deploy: point Cloudflare Pages at this repository with no build command and `/` as the output directory (or drag the files in with Direct Upload). `_redirects` makes deep links work.

Sign in with any credentials. Changes are not saved.

Built from the `itg-front-end` repository with `npm run build:demo`.
