# AriaProxy Website

The project landing page for AriaProxy.

## What this site is

AriaProxy is an experimental Android + Go software project exploring Minecraft Bedrock connectivity, RakNet transport, and NetherNet workflows. The project is actively being developed; this page does not advertise a stable release or promise that every feature is ready.

## Hosting

This site is a static HTML page deployed with GitHub Pages.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. The workflow in `.github/workflows/pages.yml` deploys the site when changes are pushed to `main`.

The GitHub Pages preview URL should be:

https://arhankhan-top.github.io/AriaProxy-Website/

## Custom domain

The intended free domain is `ariaproxy.is-a.dev`. Do not add a `CNAME` file or enter the custom domain in Pages until the is-a.dev registration has been approved and the DNS record has been merged. After approval, add the custom domain in **Settings → Pages** and commit a root-level `CNAME` file containing only:

```
ariaproxy.is-a.dev
```

## Project links

- GitHub profile: https://github.com/ArhanKhan-Top
- is-a.dev documentation: https://docs.is-a.dev/
