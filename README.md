# majitha.github.io

Personal portfolio site for Majitha Selvalingam — MA International Economics candidate at the Geneva Graduate Institute (IHEID).

Live site: <https://majitha.github.io> *(once deployed)*

## Stack

Plain HTML and CSS in a single file. No build step, no framework, no JavaScript dependencies. Hosted on GitHub Pages.

## Local preview

Open `index.html` directly in any browser, or run a tiny local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Updating

Edit `index.html`, commit, and push to `main`. GitHub Pages redeploys automatically within a minute.

## Deploying to GitHub Pages

1. Create a new public repo on GitHub named exactly `<your-username>.github.io` (e.g. `majitha.github.io`).
2. Push `index.html` (and this `README.md`) to the `main` branch.
3. In the repo, go to **Settings → Pages**, set the source to `main` / root, and save.
4. The site will be live at `https://<your-username>.github.io` within a minute or two.

## Optional: adding a CV PDF

Drop a `cv.pdf` next to `index.html` and add a download link in the hero section, e.g.:

```html
<a href="cv.pdf" download class="hero-meta-item">📄 Download CV</a>
```
