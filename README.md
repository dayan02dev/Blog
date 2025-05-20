# My Awesome Blog

A personal blog built with Hugo and the PaperMod theme. This project follows the "push Markdown, blogs get posted" workflow.

## Getting Started

### Prerequisites

- [Hugo Extended](https://gohugo.io/getting-started/installing/) (v0.80.0 or later)
- [Git](https://git-scm.com/downloads)

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/my-awesome-blog.git
   cd my-awesome-blog
   ```

2. Run the Hugo development server:
   ```bash
   hugo server
   ```

3. Open your browser and visit: http://localhost:1313

### Creating Content

#### New Blog Post

```bash
hugo new content posts/my-new-post.md
```

Then edit the file at `content/posts/my-new-post.md`, update the front matter, and write your content in Markdown.

#### Front Matter Example

```yaml
+++
title = "My New Post"
date = "2025-05-20T12:00:00+05:30"
description = "Description of the post"
tags = ["tag1", "tag2"]
categories = ["category1"]
draft = false  # Set to false to publish
+++
```

### Deployment

This blog is set up to automatically deploy when changes are pushed to the main branch. The deployment is handled by Netlify.

## Customization

### Configuration

The main configuration file is `hugo.toml` in the root directory.

### Theme

This blog uses the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. Refer to the theme's documentation for customization options.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 