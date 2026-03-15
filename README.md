# Sriram Kannepalli Portfolio

Static portfolio site built with plain HTML, CSS, and JavaScript.

## Run locally

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

This site can be deployed as a static GitHub Pages site.

1. Push the contents of this folder to `https://github.com/skannepa2206/portfolio.git`.
2. In GitHub, open the repository and go to `Settings` -> `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Select branch `main` and folder `/(root)`.
5. Save and wait for GitHub Pages to publish the site.

Your site URL will be:

```text
https://skannepa2206.github.io/portfolio/
```

If you want the site at the root URL without the repository name, the repository must be named:

```text
<your-github-username>.github.io
```

## Files

- `index.html`: page structure and portfolio content
- `styles.css`: visual design and responsive layout
- `script.js`: mobile nav, scroll reveal, active nav state, role rotator
- `assets/Sriram_Kannepalli_Resume.docx`: downloadable resume
- `assets/favicon.svg`: site icon
