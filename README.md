## Description

This repo just holds my blog content, written in MDX. I wanted to keep the content separate from the frontend so I can design and render things however I like without touching the actual posts.

Each blog lives as an `.mdx` file, so I can use normal markdown plus components when needed.

---

## What’s in here

* Blog posts written in MDX
* Frontmatter for metadata (title, date, tags, etc.)
* Some shared components (if needed)

---

## Structure

```
blogs/
├── posts/
│   ├── first-post.mdx
└── README.md
```


---

## Writing posts

Each post is an `.mdx` file with frontmatter at the top.

Example:

```mdx
---
title: "My First Blog"
date: "2026-04-02"
tags: ["tech", "notes"]
description: "first post"
---

# Hello

This is a blog post.
```

You can also use components inside MDX if needed.

---

## How I use this

This repo is not meant to run on its own.

My frontend reads these files, parses the metadata, and renders them. You can plug this into any setup you like.

Typical flow:

* read MDX files
* parse frontmatter
* render with your MDX setup

---

## Why separate repo?

* Keeps content independent from UI
* Easier to manage and version posts
* Can reuse the same content across different frontends later

---

## Notes

This is a simple content store, not a full CMS.

---

## License

MIT
