# robbieadi.github.io

Personal portfolio. Plain HTML and CSS, no build step.

```
index.html            home page
work/*.html           case studies
assets/style.css      all styles (light and dark tokens at the top)
assets/theme.js       theme toggle
404.html              GitHub Pages not-found page
```

Preview locally:

```sh
python -m http.server 8000
```

## Publishing on GitHub Pages

1. Create a public repository named `robbieadi.github.io`.
2. Push this directory to `main`. `.gitignore` keeps the source notes
   (`github_prs.md`, `CLAUDE.md`) out of the repository. They contain
   internal repository names and must never be published.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.

The site is served at https://robbieadi.github.io/.
