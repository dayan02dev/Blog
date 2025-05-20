+++
title = 'How to Add New Blog Posts'
date = '2025-05-20T13:11:19+05:30'
description = 'A guide to adding new content to your Hugo blog'
tags = ['hugo', 'markdown', 'tutorial']
categories = ['tutorials']
draft = false
+++

## Adding New Content to Your Blog

Creating and publishing new blog posts with Hugo is incredibly simple. This post will show you exactly how to do it.

### Step 1: Create a New Markdown File

Use the Hugo command line to create a new post:

```bash
hugo new content posts/your-post-name.md
```

This will create a new Markdown file with the proper frontmatter already included.

### Step 2: Edit Your Post

Open the file in your favorite text editor and update:

1. The title, description, tags, and categories
2. Change `draft = true` to `draft = false` when you're ready to publish
3. Write your content using Markdown formatting

### Step 3: Preview Your Changes Locally

Run the Hugo server to see how your post looks:

```bash
hugo server
```

Visit http://localhost:1313/Blog/ in your browser to preview.

### Step 4: Commit and Push

Once you're happy with your post, commit and push to GitHub:

```bash
git add .
git commit -m "Add new blog post about XYZ"
git push
```

### Step 5: Automatic Deployment

That's it! GitHub Actions will automatically:

1. Detect your push
2. Build the site with Hugo
3. Deploy to GitHub Pages

Your new post will be live at https://dayan02dev.github.io/Blog/ within a minute or two.

### Markdown Tips

You can use all standard Markdown features:

- **Bold text** with `**double asterisks**`
- *Italic text* with `*single asterisks*`
- Lists (like this one!)
- [Links](https://gohugo.io/) with `[text](url)`
- And much more!

### Images

To add images, place them in the `static/images/` directory and reference them like this:

```markdown
![Image description](/Blog/images/your-image.jpg)
```

Happy blogging!
