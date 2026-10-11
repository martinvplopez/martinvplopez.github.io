# Personal Blog 

A clean, minimalist personal blog built with Hugo.

## Getting Started

### Prerequisites

- [Hugo](https://gohugo.io/installation/) installed on your system


### Start local server

```bash
hugo server -D
```

### Adding Blog Posts

Create new posts in the `content/posts/` directory:

```bash
hugo new posts/your-post-title.md
```

Each post should have:

```yaml
---
title: "Your Post Title"
date: 2024-01-01
description: "A brief description of your post"
tags: ["tag1", "tag2"]
---
```

Use `#` for top-level sections inside a post; headings are shifted down one level so the post title stays the page's only `<h1>`.

Standalone images become figures, and an optional title becomes the caption:

```markdown
![Alt text](/images/diagram.webp "Caption shown under the image")
```

### Customizing the Design

- Styles: `assets/css/main.css` (colors are CSS variables at the top, with dark mode overrides)
- Dark mode follows the visitor's system setting; the header toggle overrides it and is remembered in `localStorage`
- Templates: `layouts/_default/` (pages), `layouts/partials/` (head, header, footer, social card), `layouts/_default/_markup/` (heading, link and image render hooks)
- Font: [Newsreader](https://github.com/productiontype/Newsreader), self-hosted in `static/fonts/` (SIL OFL 1.1)
- Social preview images are generated at build time from `assets/og/base.png` with the post title and description

To add an About page, create `content/about.md` and uncomment the menu entry in `hugo.toml`.

## Deployment

This is a static site, so it can be deployed to any static hosting service.

### GitHub Pages

1. Build your site: `hugo`
2. Push the `public` directory to a GitHub repository
3. Enable GitHub Pages in your repository settings

## Acknowledgments

- Inspired by [Anand Sanwal's blog](https://anandsanwal.me/)
- Built with [Hugo](https://gohugo.io/)
- Design principles from modern minimalist web design

---

Martín vPL