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

### Customizing the Design

The design is built with CSS in the `layouts/_default/baseof.html` file

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