# Gray Home Decor Estimator — GitHub Pages

This repo hosts a static estimator with _no embedded prices_.

## Use it
1. Open **index.html**.
2. Click **Import JSON** and select your `ghd_estimator_data.json`.

## Publish on GitHub Pages
1. Create a new repo and upload these files.
2. In **Settings → Pages**, choose `Deploy from branch` (root).
3. Visit your Pages URL (it will load `index.html`).

## Optional: public JSON auto-load
If you want prices to auto-load from `pricing/ghd_estimator_data.json`, insert a small `fetch()` snippet at the end of `index.html`.
**Note:** Any JSON committed here is public.
