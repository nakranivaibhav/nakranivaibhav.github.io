# nakranivaibhav.github.io

My personal blog, built with [Jekyll](https://jekyllrb.com) and hosted on
[GitHub Pages](https://pages.github.com).

**Live site:** https://nakranivaibhav.github.io

## Writing a post

Add a Markdown file to `_posts/` named `YYYY-MM-DD-title.md` with front matter:

```markdown
---
layout: post
title: "My post title"
date: 2026-06-28 12:00:00 +0300
categories: tag1 tag2
---

Content in Markdown...
```

Commit and push to `main`. GitHub Pages rebuilds automatically in ~1–2 minutes.

## Structure

| Path           | Purpose                                  |
| -------------- | ---------------------------------------- |
| `_config.yml`  | Site settings (title, description, etc.) |
| `_posts/`      | Blog posts                               |
| `index.md`     | Home page (lists posts)                  |
| `about.md`     | About page                               |
| `Gemfile`      | Pins the GitHub Pages gem versions       |

## Local preview (optional)

Requires Ruby 2.7+ (the system Ruby on this Mac is 2.6, which is too old).
With a newer Ruby installed:

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

Local previews are optional — GitHub builds and deploys the site server-side on
every push, so you don't need a working local toolchain to blog.
