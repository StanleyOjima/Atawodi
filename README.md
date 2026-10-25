# Emmanuel Atawodi: portfolio

Static site. Upload this folder as-is to any static host. Vercel, Netlify and GitHub Pages all work with no build step.

| File | What it is |
|---|---|
| `index.html` | The whole landing page: fonts, styles and scripts are inlined |
| `404.html` | The "still being drawn" page, shown for any address that doesn't exist yet (case studies, etc.) |
| `og.png` | Link-preview image, 1200 × 630 |
| `favicon.svg`, `apple-touch-icon.png` | Browser-tab and home-screen icons |

Vercel and Netlify serve `404.html` automatically for missing pages.

## Before going live
- **Domain:** the link-preview tags in `index.html` point to `https://emmanuelatawodi.com`. If the site lives elsewhere, find and replace that address so previews on WhatsApp, LinkedIn and X load the image.
- **Links:** the email (`hello@emmanuelatawodi.com`) and the GitHub, LinkedIn and X links are still placeholders.
