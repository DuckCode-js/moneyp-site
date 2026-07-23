# moneyp-site

Static site for a niche SaaS-affiliate content project targeting mobile car detailers.

- Build: none. Plain HTML/CSS.
- Deploy: Cloudflare Pages, auto-deploys on push to `main`.
- Working title: **The Detailer's Toolbox** (placeholder — final brand TBD).

## Structure

- `index.html` — home page
- `posts/` — published articles, one HTML file per post
- `drafts/` — article outlines and drafts before publish
- `assets/style.css` — shared styles

## Publishing flow

1. Agent writes an article in `drafts/`.
2. Human reviews.
3. On approval, article is finalized and moved to `posts/`, home page updated.
4. Git commit + push. Cloudflare Pages auto-deploys.
