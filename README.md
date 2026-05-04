# Qiankun Zhang Homepage

This repository contains the source for `https://qiankuntcs.github.io/`.

The site is built on top of the Academic Pages Jekyll template, but the repository has been trimmed to focus on the current homepage rather than the full upstream demo content.

## Current Structure

- `_config.yml`: site-wide settings, author info, collections, and plugins.
- `_data/navigation.yml`: top navigation bar.
- `_pages/about.md`: homepage.
- `_pages/publications.md`: publication list page.
- `_pages/teaching.md`: teaching page.
- `_pages/students.md`: group page.
- `_pages/cv.md`: CV page.
- `_publications/`: publication detail pages currently kept as standalone HTML files.
- `assets/`, `images/`, `files/`: static resources.
- `使用说明.md`: quick editing notes for common content updates.

## Local Preview

1. Install Ruby, Bundler, and Node.js.
2. Install dependencies:

```bash
bundle install
npm install
```

3. Start the local server:

```bash
bundle exec jekyll serve -l -H localhost
```

If you prefer Docker, the repository still includes `Dockerfile` and `docker-compose.yaml`.

## Notes

- Most template demo pages, sample posts, and duplicate route files have been removed.
- `vendor/bundle/` is a local dependency cache and should not be relied on as project source.
- The publication entries under `_publications/` are usable as-is, but they are less maintainable than normal Jekyll source files with front matter. If you want a second cleanup pass later, that is the next place to simplify.

## Upstream Base

The site is derived from Academic Pages / Minimal Mistakes. The upstream license information remains in `LICENSE`.
