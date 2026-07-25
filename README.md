# Trainano AI Website

Static HTML/CSS/JS site for Cloudflare Pages.

## Clean URLs

Pages use folder `index.html` files so routes stay extension-free:

| URL | File |
| --- | --- |
| `/` | `index.html` |
| `/about` | `about/index.html` |
| `/solutions` | `solutions/index.html` |
| `/technology` | `technology/index.html` |
| `/company` | `company/index.html` |
| `/careers` | `careers/index.html` |
| `/contact` | `contact/index.html` |

`_redirects` maps common `.html` paths to the clean routes.

## Local preview

Serve the project root with any static server, for example:

```bash
npx --yes serve .
```

Then open `http://localhost:3000`.

## Cloudflare Pages

- **Build command:** none (static)
- **Output directory:** `/` (project root)
