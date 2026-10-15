# Mehad El-Khattib — Portfolio

Static portfolio site (no build step). Open `index.html` in a browser to preview.

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `portfolio`, or `<username>.github.io` for a root URL).
2. Upload **everything in this folder** (`index.html`, `assets/`, `.nojekyll`, `README.md`) to the repository root. Keep the `assets` folder next to `index.html`.
3. Go to **Settings → Pages**, set **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After a minute the site is live at `https://<username>.github.io/<repo>/`.

## Edit content
Everything lives in the `<script>` block of `index.html`:
- `PROJECTS` — the six featured case studies (title, category, year, description, role, images). Replace placeholder text and fill in challenge/approach/outcome only with verified information.
- `IMG` — maps an image key to a file in `assets/`. To add an image: put the file in `assets/`, add `"mykey": "assets/mykey.jpg"` to `IMG`, then use `['mykey','Alt text']` in a project's `imgs`.
- Images with no matching key show a labelled placeholder.
- Contact details and the LinkedIn link are in the Contact section near the bottom of the page.
