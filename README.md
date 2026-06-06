# microsites

A grab-bag of tiny single-page sites, each one served from its own folder on GitHub Pages.

## Convention

```
microsites/
  cheese/
    index.html
  <next-site>/
    index.html
```

Each top-level folder is published at:

```
https://grahamton.github.io/microsites/<folder>/
```

## To add a new one

1. Create a new folder at the repo root.
2. Drop an `index.html` (and any assets it needs) inside.
3. Commit and push to `main`.
4. Wait ~1–2 minutes for Pages to redeploy. Done.

Pages source: `main` branch, `/` (root). No build step, no framework, no CI — just static files.

## Heads up

GitHub Pages is fully public. Don't commit anything you wouldn't want indexed.
