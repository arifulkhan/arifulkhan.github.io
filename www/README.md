# arifulkhan.github.io (clean rebuild)

This project is a clean static rebuild of your personal site with the same core content and layout sections:

- Home/About
- CV link
- Publications
- Contact

## Local preview

From this folder, run:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Publish to GitHub Pages

Use this folder as the root of your `arifulkhan.github.io` repository and push to `main`.

```bash
git add .
git commit -m "Rebuild site without deprecated plugins"
git push origin main
```
