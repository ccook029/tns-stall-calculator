# TNS Quote Calculator

Internal quote tool for True North Steelworks.

## Deploy to Vercel

1. Install Vercel CLI: `npm install -g vercel`
2. From this folder: `vercel --prod`
3. Follow prompts — choose "No framework", output dir is `public`

Or drag-and-drop the `public/` folder at vercel.com/new

## What's included

- `public/index.html` — the full calculator app
- `public/products/` — product images (SKU-named JPGs)
- `public/logo_sm.png` — TNS logo
- `vercel.json` — deployment config (serves `public/` as root)

## PDF generation

Uses pdf-lib loaded from CDN (no build step required).
The PDF generates entirely in the browser — no server needed.
