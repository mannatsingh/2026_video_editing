# Fast high-fidelity video editing

A personally curated compilation (by Mannat Singh) of video editing examples and
capabilities from the publicly available model on Meta AI and Instagram Edits.

Based on the [announcement thread on X](https://x.com/mannat_singh/status/2058042276480499959).

## Structure

- `index.html` / `style.css` — static site, no build step or dependencies
- `videos/` — example videos per capability (original left, edit right)
- `posters/` — first-frame JPEGs used as video posters while the videos lazy-load

## Local preview

```sh
python3 -m http.server -d . 8000
# open http://localhost:8000
```

## Deploy on GitHub Pages

Push to GitHub, then in the repo settings enable **Pages → Deploy from a branch → main / (root)**.
The `.nojekyll` file is already in place.
