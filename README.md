# CST1340 Blog

Modern academic blog with grid layout and image support.

## Setup

1. Fork this repository
2. Rename it to `<your-username>.github.io/ClassBlog`
3. Enable GitHub Pages in repository settings (Settings > Pages)
   - Set source to: `main` branch
   - Save

## Adding Posts

1. Create a new file in `_posts` folder using: `YYYY-MM-DD-title.md`
2. Use this header format:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
image: /assets/images/your-image.jpg  # Optional header image
---
```

## Adding Images

1. Create an `assets/images` folder
2. Add images to this folder
3. Reference in posts using:
   ```markdown
   ![Alt text](/ClassBlog/assets/images/your-image.jpg)
   ```

## Grid Layout Examples

Use HTML in your markdown posts for custom layouts:

```html
<div class="image-grid">
    <img src="/ClassBlog/assets/images/image1.jpg" alt="Description">
    <img src="/ClassBlog/assets/images/image2.jpg" alt="Description">
</div>

<div class="post-content">
    Your text content here...
</div>
```

## Example Post Structure
```markdown
---
layout: post
title: "Week 1: CST1340 Introduction"
date: 2024-01-15
image: /assets/images/header.jpg
---

Text content here...

<div class="image-grid">
    <img src="/ClassBlog/assets/images/diagram1.jpg" alt="Diagram 1">
    <img src="/ClassBlog/assets/images/diagram2.jpg" alt="Diagram 2">
</div>

More text content...
```

## Customization

Edit `_config.yml` to change:
- Site title
- Description
- Navigation links

## Local Testing
Open index.html in a browser to preview the layout
