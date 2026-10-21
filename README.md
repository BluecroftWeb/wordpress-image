# wordpress-image

Rebuild of Docker's official [`wordpress:php8.3-apache`](https://github.com/docker-library/wordpress) on the latest `php:8.3-apache`, published to `ghcr.io/bluecroftweb/wordpress:php8.3-apache`.

Use it only to bridge the gap between a PHP security release and Docker Hub rebuilding its WordPress image. Run the **Build WordPress image** workflow, set `WP_BASE=ghcr.io/bluecroftweb/wordpress:php8.3-apache` on the site in Coolify and redeploy. Remove `WP_BASE` once Docker Hub's image catches up.
