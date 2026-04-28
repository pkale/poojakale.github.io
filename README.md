# poojakale.github.io

Personal website and blog built with Jekyll and hosted on GitHub Pages.

## Local Development

To run locally:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`

## Structure

- `_config.yml` - Site configuration
- `_layouts/` - Page templates
- `_includes/` - Reusable components
- `_posts/` - Blog posts (format: YYYY-MM-DD-title.md)
- `css/` - Stylesheets
- `index.html` - Home page
- `about/` - About page
- `blog/` - Blog archive

## Writing Posts

Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
---

Your content here...
```
