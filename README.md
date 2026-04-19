# Genre Discovery App

Static prototype designed for GitHub Pages.

## Files
- `genre-discovery-app.html` — main app file
- `data.json` — genre/listened-date seed data from your spreadsheet and exports

## GitHub Pages
1. Create a repo.
2. Upload both files to the repo root (or docs/).
3. In GitHub Pages settings, publish from that branch/folder.
4. Open the published URL.

## Live features
This build supports:
- local fallback summaries/suggestions
- optional Perplexity API key for live summaries and chat
- refresh examples button
- Discord split-copy
- star rating and same-category same-star drag ranking

## Important note
Putting a Perplexity API key directly into a static site exposes it to the browser. For a safer production setup, use a small proxy function (Cloudflare Worker, Netlify Function, or Vercel serverless endpoint) to hold the key server-side.