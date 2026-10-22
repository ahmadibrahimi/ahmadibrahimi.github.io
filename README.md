# Ahmad Ibrahim - Blog & Portfolio

Personal blog and portfolio built with [Hugo](https://gohugo.io/) and the PaperMod theme.

Live site: https://ahmadibrahimi.github.io

## Run locally

```bash
git clone --recurse-submodules https://github.com/ahmadibrahimi/ahmadibrahimi.github.io.git
cd ahmadibrahimi.github.io
hugo server -D
```

## Add a post

```bash
hugo new content posts/my-post.md
```

Set `draft = false`, write the post, then commit and push. GitHub Actions rebuilds the site automatically.
