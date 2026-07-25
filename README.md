# Transovo AI Website

Static HTML/CSS/JS site for Cloudflare Pages.

Transovo AI LLC is presented as the parent software company for cloud applications, communications infrastructure, and AI workflow technology. Local SEO Express is featured as a product under that platform.

## Clean URLs

| URL | File |
| --- | --- |
| `/` | `index.html` |
| `/solutions` | `solutions/index.html` |
| `/technology` | `technology/index.html` |
| `/company` | `company/index.html` |
| `/contact` | `contact/index.html` |
| `/privacy` | `privacy/index.html` |
| `/terms` | `terms/index.html` |
| `/acceptable-use` | `acceptable-use/index.html` |

`_redirects` maps common legacy paths (including `/about`) to clean routes.

## Local preview

```bash
npx --yes serve .
```

## Cloudflare Pages

- **Build command:** none
- **Output directory:** `/` (project root)
