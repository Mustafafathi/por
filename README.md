# Deployment

Publish the contents of this site directory as the site root.

## GitHub Pages

Create a repository for the portfolio, copy these files to its repository root, then enable **Settings → Pages → Deploy from a branch**. Select the branch and / (root) folder.

## Cloudflare Pages

Create a Pages project from the repository and use these settings:

- Framework preset: **None**
- Build command: leave empty
- Build output directory: /

The page has no build step, no framework dependency and no external font/CDN dependency.

## Custom domain

Add the domain in the host dashboard after deployment, then point its DNS records to the host's values. Do not publish the parent project directory: it contains source documents intended to remain private.
