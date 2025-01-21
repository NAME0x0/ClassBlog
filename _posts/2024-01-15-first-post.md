3. In GitHub repository settings:
   - Go to "Settings" > "Pages"
   - Source: "GitHub Actions"
   - Wait for the workflow to complete

4. Delete unnecessary files:
- Delete: index.md (keep only index.html)
- Delete: Gemfile (not needed with GitHub Pages)
- Delete: .gitignore (optional)

5. Create a sample post to test:

---
layout: post
title: "First Post - CST1340"
date: 2024-01-15
---

Introduction paragraph here...

## Main Content

Your post content here...

<!--more-->

Everything should be working now with:
- Proper GitHub Pages setup
- Working image support
- Correct path handling
- Dark/light mode support
