# Sai-SuperAI
This blog explores how Artificial Intelligence can be applied pragmatically to solve real business problems and improve everyday productivity. It bridges strategy and execution, translating cutting edge AI research, industry reports, and enterprise use cases into clear, actionable insights.

Welcome — this repository is configured as a GitHub Pages blog using the "minimal-mistakes" Jekyll theme.

Quick publish instructions

1) Create a new post file in `_posts/` with the filename format:

	YYYY-MM-DD-your-title.md

2) Minimal front matter example (top of the post file):

```yaml
---
layout: post
title: "My Post Title"
date: 2025-12-31 09:00:00 +0000
categories: blog
tags: [tag1, tag2]
excerpt: "A one-line summary for index cards."
---
```

3) Commit and push to the repository's default branch (usually `main`). For a user/organization page (repository named `sai-superai.github.io`) GitHub Pages will publish from the default branch automatically.

Local preview (optional): install Ruby + Jekyll and run:

```bash
bundle install
bundle exec jekyll serve
```

Notes
- The site uses `remote_theme: mmistakes/minimal-mistakes` in `_config.yml` and only uses plugins supported by GitHub Pages (`jekyll-feed`, `jekyll-seo-tag`).
- If you want GitHub to build the site via Actions instead, there is a workflow at `.github/workflows/jekyll-gh-pages.yml` included.
