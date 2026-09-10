# Tusher Chandra Mondol — Research Portfolio

A lightweight static research portfolio built with plain HTML, CSS, and JavaScript. No build tools or paid services are required.

## Local preview
Open `index.html` in a browser, or from this folder run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Netlify — easiest method
1. Sign in to Netlify.
2. Choose **Add new project** / **Deploy manually** (or use Netlify Drop).
3. Drag the entire `tusher-portfolio` folder into the deploy area.
4. Netlify will publish it and assign a `*.netlify.app` URL.
5. In **Domain management**, change the site/project name if you want a cleaner available `*.netlify.app` subdomain.

## Recommended deployment — GitHub + Netlify
1. Create a GitHub repository (for example `portfolio`).
2. Put all files in this folder at the repository root and push to `main`.
3. In Netlify choose **Add new project → Import an existing project → GitHub**.
4. Select the repository. This site has no build command; publish directory is `.`.
5. Publish. Future pushes to `main` will automatically update the website.

## Before publishing
- Review all publication statuses and dates.
- Add a professional headshot if desired. The current design intentionally works without one.
- If you want a Resume/CV button, copy your PDF into `assets/Tusher_Chandra_Mondol_Resume.pdf` and add a link to it in `index.html`.
- Replace or add project links (GitHub, paper DOI, slides) as they become public.
- Add your final Netlify/custom-domain URL to the Open Graph metadata and optionally create `sitemap.xml`.

## Structure
- `index.html` — all portfolio content
- `assets/styles.css` — responsive design
- `assets/script.js` — mobile navigation and current year
- `assets/favicon.svg` — site icon
- `netlify.toml` — publish configuration and security headers
- `robots.txt` — crawler access
