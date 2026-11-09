# Sagar Shahi | Developer Portfolio

Personal portfolio of **Sagar Shahi**, a computer engineering student and developer in Kathmandu, Nepal.

**Live site:** https://sagar-shahi.github.io/

A static site with no build step and no framework. It is plain HTML, CSS and JavaScript served by GitHub Pages.

## What is on the site

- Projects, including [Fitness Hub](https://github.com/Sagar-Shahi/fitness-hub), a Django fitness platform
- **S.A.G.E.**, a small on-page assistant that gives a tour and answers questions from the page's own content
- A downloadable CV ([Sagar-Shahi-CV.pdf](Sagar-Shahi-CV.pdf))
- Contact links, a custom 404 page, a social share image, `robots.txt` and a sitemap for search engines

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole site: markup, styles and scripts in one file |
| `404.html` | Page shown for unknown URLs |
| `Sagar-Shahi-CV.pdf` | CV download |
| `og-image.png` | Preview image used when the link is shared (1200 x 630) |
| `favicon.svg` | Browser tab icon |
| `robots.txt`, `sitemap.xml` | Search engine hints |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Run it locally

No install is needed. From this folder:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Pushing to `main` publishes the site through GitHub Pages (**Settings > Pages > Deploy from a branch > main**).

## Contact

- GitHub: [@Sagar-Shahi](https://github.com/Sagar-Shahi)
- LinkedIn: [Sagar Shahi](https://www.linkedin.com/in/sagar-shahi-570003435)
