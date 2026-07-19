# adityasharma.cc

Personal portfolio site for Aditya Sharma.

**Stack:** Astro + Tailwind CSS v4  
**Hosting:** Cloudflare Pages  
**Domain:** [adityasharma.cc](https://adityasharma.cc)

## Pages

- `/` — Home (about, featured work, tech stack)
- `/resume/` — Resume PDF viewer & download
- `/experience/` — Detailed work experience timeline
- `/contact/` — Contact methods

## SEO & Discoverability

- Server-rendered HTML (Astro static output)
- JSON-LD Person schema on every page
- Open Graph + Twitter meta tags
- Auto-generated sitemap (`/sitemap-index.xml`)
- `robots.txt` allowing all crawlers
- `llms.txt` + `llms-full.txt` for AI model discoverability

## Development

```bash
npm install
npm run dev      # Start dev server
npm run build    # Build for production
npm run preview  # Preview production build
```

## Deployment

Connected to Cloudflare Pages via GitHub integration. Pushes to `main` auto-deploy.

**Build settings:**
- Build command: `npm run build`
- Build output: `dist`
- Node version: 22
