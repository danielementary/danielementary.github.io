# danielementary.github.io

Source of [danielementary.me](https://danielementary.me), built with [Hugo](https://gohugo.io) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Local development

```bash
git clone --recurse-submodules https://github.com/danielementary/danielementary.github.io.git
hugo server
```

## Deployment

Every push to `main` is built and deployed to GitHub Pages by [`.github/workflows/hugo.yaml`](.github/workflows/hugo.yaml).

## Updating

- **Hugo:** bump `HUGO_VERSION` in the workflow (and `brew upgrade hugo` locally).
- **PaperMod:** `git submodule update --remote themes/PaperMod`, then commit the submodule.
