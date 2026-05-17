# Editing Guide

This site is designed so most content can be edited directly in Markdown files.

## Main Files

- Homepage and profile block: `_pages/about.md`
- Publications: `_pages/publications.md`
- Academic service: `_pages/service.md`
- Teaching and thesis supervision: `_pages/teaching.md`
- CV content: `_data/cv.yml`
- Social links: `_data/socials.yml`
- Site title, URL, and global settings: `_config.yml`

## Common Updates

To update your profile text, edit the paragraphs in `_pages/about.md`.

To update the information below your photo, edit the `profile.more_info` block near the top of `_pages/about.md`.

To add a new publication, add a new bullet under the correct section in `_pages/publications.md`.

To add a new conference or journal service item, edit `_pages/service.md`.

To add thesis supervision, edit `_pages/teaching.md`. Keep each university section ordered from newest to oldest.

## Publishing

After editing content on GitHub, commit the change to `main`. The `Deploy site` workflow will build the site and publish the generated version to the `gh-pages` branch.

GitHub Pages should be configured to serve from:

- Branch: `gh-pages`
- Folder: `/ (root)`
