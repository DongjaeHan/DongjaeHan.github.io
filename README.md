# DongjaeHan.github.io

Personal Jekyll blog for physics, research, and programming notes.

## Local preview

Use Ruby 3.1 or newer with Bundler installed.

```bash
bundle install
bundle exec jekyll serve
```

## Writing a post

Create `_posts/YYYY-MM-DD-title.md`. The filename determines the URL slug:
`_posts/2026-09-20-hello-world.md` becomes `/posts/hello-world/`.
Use unique slugs, even when posts have different dates.

```yaml
---
layout: post
title: "Hello World"
date: 2026-09-20
categories:
  - Miscellaneous
description: "A short summary for the post list."
---
```

Use one or more of these exact category names: `Research`, `Physics Notes`,
`Programming`, and `Miscellaneous`. Home and category pages update automatically.
If `description` is omitted, the list uses a shortened excerpt.

Use fenced code blocks with `python`, `cpp`, or `bash` language labels for Rouge
syntax highlighting. Edit `about.md` to update the profile.
