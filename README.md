# Abid Hasan Rafi — Professional Profile Website

A responsive, colourful personal profile website built with plain HTML, CSS, and JavaScript. Includes subtle animations, mobile navigation, SEO metadata, Open Graph tags, JSON-LD structured data, `robots.txt`, `sitemap.xml`, and a favicon.

## Before publishing — important edits

1. **Set the real website URL.** Search the project for `https://YOUR-USERNAME.github.io/abid-hasan-rafi/` and replace every occurrence with your actual GitHub Pages URL (or custom domain). Update `sitemap.xml` and `robots.txt` too.
2. **LinkedIn link:** the URL supplied for LinkedIn was the same Facebook URL. To avoid linking people to the wrong account, the website shows LinkedIn as a reminder only. Add your actual LinkedIn profile URL in `index.html` when you have it.
3. **Profile picture:** the page uses the GitHub user-attachment image URL supplied to us. If that image doesn't load reliably, download your photo and save it as `assets/profile.jpg`; then replace the image URL in `index.html`, Open Graph/Twitter image metadata, and JSON-LD with `assets/profile.jpg` (for social preview metadata, use the full deployed URL).
4. Review the wording in the SEO and experience sections so it accurately reflects your real skills and responsibilities. Do not add unverified claims, certifications, or performance numbers.

## Publish with GitHub Pages

1. Create a new public repository, for example `abid-hasan-rafi`.
2. Upload **the contents of this folder** (not just the ZIP) to the repository's root.
3. Open **Settings → Pages** in GitHub.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for the deployment URL shown by GitHub Pages. Put that exact URL in canonical tags, Open Graph URL, JSON-LD, `robots.txt`, and `sitemap.xml`.
6. Open Google Search Console, add/verify your website, submit `sitemap.xml`, and use URL Inspection to request indexing.

## Local preview

Open `index.html` in a browser. For a closer local web-server preview, run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Included files

- `index.html` — page content and on-page SEO metadata
- `assets/style.css` — responsive styling and animations
- `assets/script.js` — menu, scroll progress, reveal-on-scroll effects
- `assets/favicon.svg` — browser icon
- `robots.txt` — crawler access rules and sitemap location
- `sitemap.xml` — sitemap template (update the URL before launch)

## SEO expectations

The site is prepared with SEO fundamentals, but **no code can guarantee first-place rankings or immediate indexing** for “Abid Hasan Rafi.” Publish the site, use Google Search Console, keep the information accurate and useful, and build genuine links/mentions from relevant profiles and sites over time. Google may take days or weeks to crawl and process updates.
