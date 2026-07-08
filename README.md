# Research Homepage Template

This is a minimal bilingual Quarto homepage for GitHub Pages.

## What to replace

- In `_quarto.yml`, replace `Your Name` and the site description.
- In `index.qmd`, replace the placeholder biography, research directions, publications, projects, email, ORCID, Google Scholar, and GitHub links.
- Replace `assets/cv.pdf` with your real CV before publishing.
- Optional: add `assets/profile.jpg` and place it in the hero section if you want a profile photo.

## Publish with GitHub Actions

1. Create a public GitHub repository named `<your-github-username>.github.io`.
2. Upload all files in this folder to the repository.
3. Go to **Settings > Pages** and set the source to the `gh-pages` branch after the first workflow run creates it.
4. Push to the `main` branch. The workflow in `.github/workflows/publish.yml` will render the Quarto site and publish it to `gh-pages`.
5. Visit `https://<your-github-username>.github.io`.

## Publish locally

Install Git and Quarto, then run:

```bash
quarto preview
quarto publish gh-pages
```

Use `quarto preview` to check the site locally before publishing.
