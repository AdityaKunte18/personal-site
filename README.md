# personal-site

A static personal landing page. Two files, no build step, no dependencies.

```
index.html   markup and content
style.css    styling (light + dark via prefers-color-scheme)
```

## Running it

Open `index.html` in a browser, or serve the directory:

```sh
python3 -m http.server 8000
```

## Editing

Content lives directly in `index.html`:

- **Bio** — the `<p class="bio">` block. This is a draft inferred from public
  repos; rewrite it.
- **Links** — the `<nav class="links">` block.
- **Projects** — the `<ul class="projects">` list. Each entry is a name, a
  one-line description, and a language tag.

Colors, spacing, and the text measure are CSS custom properties at the top of
`style.css`.

## Publishing

GitHub Pages is not enabled. To turn it on: **Settings → Pages → Source: deploy
from branch → `main` / root**.
