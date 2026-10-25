# James Scarberry — Portfolio

Static portfolio site (HTML + CSS only, no build step).

```
index.html                         homepage (about, project summaries, experience, skills…)
projects/amigo-alert.html          Amigo Alert capstone project page
projects/compiler-thesis.html      Cóndor compiler thesis project page
style.css                          all styling, shared by every page (light + dark mode, responsive)
assets/james-scarberry.jpg         headshot
assets/James-Scarberry-Resume.pdf  downloadable résumé
```

## Publish on GitHub Pages

1. Create a repository named `<your-username>.github.io` (or any name for a project site).
2. Upload the contents of this folder to the repository root and commit to `main`.
3. In the repository, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. The site will be live at `https://<your-username>.github.io/` (or `/<repo-name>/` for a project site) within a minute or two.

## Updating

- Text lives in `index.html`; each section is marked with a comment (`<!-- About -->`, `<!-- Experience -->`, …).
- To add a project, copy one of the files in `projects/`, edit it, then add a summary card for it in the `<!-- Projects -->` section of `index.html`.
- Colors and fonts are defined as variables at the top of `style.css`.
- To update the résumé, replace `assets/James-Scarberry-Resume.pdf` with a file of the same name.
