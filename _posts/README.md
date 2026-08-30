# Adding a new blog post

This site is built with **Jekyll**, which GitHub Pages builds automatically. To publish a
new blog post, drop a Markdown file into this `_posts/` folder — nothing else needs to change.
It will automatically appear as a new card in the **Blog** section of the home page and get its
own page.

## 1. Name the file

Use the format:

```
YYYY-MM-DD-a-short-url-slug.md
```

Example: `2026-09-15-migrating-to-aem-cloud.md`

## 2. Add front matter + content

```markdown
---
layout: post
title: "Your Post Title"
date: 2026-09-15 10:00:00 +0530
author: Santhosh Murugesan Renuka Siva
tags: [AEM, Migration]
excerpt: >-
  A one or two sentence summary shown on the home page card.
image: /uploads/blog-02.jpg   # optional, defaults to /uploads/blog-01.jpg
---

Write the full post here in Markdown.
```

## 3. Commit & push

Push the new file to the repository's default branch. GitHub Pages rebuilds the site
automatically (usually within a minute), and the new post shows up on the home page's Blog
section, newest first, with a link to its own full page.

That's it — no HTML, templates, or home page edits required for new posts.
