# DAASK — Data As A Service Kenya

Static website for [daask.framer.website](https://daask.framer.website), exported from Framer using ToStatic and prepared for deployment on Vercel or GitHub Pages.

## Structure

```
/                   → Home page
/about-us           → About Us
/services           → Services overview
/services/*         → Individual service pages (6 pages)
/contact            → Contact page
/blog               → Blog listing
/blog/*             → Individual blog posts (6 posts)
/404                → Custom 404 page
/images             → All site images
/sites/icons        → Favicons and touch icons
```

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import from GitHub
3. Select this repo — no build step needed (static site)
4. Set **Framework Preset** to "Other"
5. Deploy

## Deploy to GitHub Pages

1. Push to a repo named `yourusername.github.io` (or use a custom domain)
2. Go to Settings → Pages → Source: `main` branch, `/ (root)` folder
3. Enable

## Notes

- All JavaScript is loaded from Framer's CDN (`framerusercontent.com`). An internet connection is required for full interactivity.
- Images are stored locally for performance and reliability.
- The `vercel.json` file handles clean URLs, caching headers, and the 404 route.
