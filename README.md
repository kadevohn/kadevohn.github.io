# kadevohn.github.io# Field Notes

A simple public blog for GitHub Pages. It uses GitHub's built-in Jekyll support,
so new posts can be written as Markdown files.

## Publish on GitHub Pages

1. Create a new public GitHub repository.
2. Upload these files to the repository.
3. In GitHub, open **Settings > Pages**.
4. Set **Source** to **Deploy from a branch**.
5. Choose the `main` branch and the `/root` folder, then save.

GitHub will publish the site at:

```text
https://kadevohn.github.io/
```

## Add a new post

1. Copy one of the files in `_posts/`.
2. Rename it with this format: `YYYY-MM-DD-post-title.md`.
3. Edit the title, description, and article content.
4. Commit or upload the file to GitHub.

Example:

```markdown
---
layout: post
title: My new post
description: A short sentence describing the post.
---

Write the post here.
```

The homepage lists posts by date, newest first.

## Customize

- Change the blog name and description in `_config.yml`.
- Edit the intro text in `index.html`.
- Adjust colors and layout in `styles.css`.
