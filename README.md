# Hello World! — Cloudflare Pages

A minimal static site that displays **Hello World!** and **I'm Jae Seung Lee**.

## Files

- `public/index.html` — page structure and content
- `public/styles.css` — responsive visual design
- `wrangler.toml` — Cloudflare Pages configuration

## Local preview

Open `public/index.html` in a browser, or run:

```bash
npx wrangler pages dev public
```

## Cloudflare Pages deployment

In Cloudflare, choose **Workers & Pages → Create application → Pages → Connect to Git**, select this repository, leave the build command empty, and set the build output directory to `public`.

Every push to `main` will then trigger a deployment.

## Maintenance

Edit the visible text in `public/index.html`. Edit colors, spacing, and typography in `public/styles.css`; both files contain comments describing their roles.
