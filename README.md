# Video Editing in Meta AI

Showcase website for the video editing model in Meta AI — high-fidelity edits of videos
up to 10 seconds, generated in under 30 seconds with no usage limits.

Based on the [announcement thread on X](https://x.com/mannat_singh/status/2058042276480499959).

## Structure

- `index.html` / `style.css` — static site, no build step or dependencies
- `videos/` — demo recording and 4 example videos per capability (original left, edit right)
- `posters/` — first-frame JPEGs used as video posters while the videos lazy-load

## Local preview

```sh
python3 -m http.server -d . 8000
# open http://localhost:8000
```

## Deploy on GitHub Pages

Push to GitHub, then in the repo settings enable **Pages → Deploy from a branch → main / (root)**.
The `.nojekyll` file is already in place.
