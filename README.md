# Twinzlab site

Static marketing site for Twinzlab (HTML/CSS/JS).

## Run locally

Serve the repo root with any static file server (paths are absolute from `/`).

```bash
# Python
python3 -m http.server 4817

# Node (if you have npx)
npx --yes serve -l 4817
```

Open [http://127.0.0.1:4817](http://127.0.0.1:4817).

Use a non-default port (e.g. `4817`) if `3000` / `8080` are already in use.

## Notes

- Contact form uses FormSubmit; activate the FormSubmit email once the site is publicly hosted.
- Keep `responsive.css` / `responsive.js`, `interactions.css` / `interactions.js`, `assets/`, page folders, and `f2c-sw.js` at the repo root.
