# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Jekyll-based academic research group website for the Computational Structural Biology Research Group at Gebze Technical University. The site showcases research, people, publications, and courses.

## Build and Development Commands

All commands must be run from the `/docs` directory:

```bash
cd docs

# Install dependencies
bundle install

# Local development server (http://localhost:4000)
bundle exec jekyll serve

# Build only (generates _site/)
bundle exec jekyll build
```

## Architecture

**Framework:** Jekyll with the `LeNPaul/academic` remote theme (academic-jekyll-theme)

**Key directories under `/docs`:**
- `_data/` - YAML data files that drive content
  - `settings.yml` - Navigation menu, people (personnel, graduates, alumni), courses, contacts
  - `publications.yml` - Bibliography entries with doi/url links
- `_layouts/` - HTML templates (default, home, people, publications, courses, cv, etc.)
- `_includes/` - Reusable HTML components (header, footer, head)
- `_posts/` - Blog posts in markdown format
- `_sass/` - SCSS stylesheets for customization
- `assets/` - Static files (CSS, images)

**Content pages:** Markdown files in `/docs` root (people.md, publications.md, courses.md, etc.)

## Common Editing Tasks

- **Add/edit people:** Modify `_data/settings.yml` under `people_personnel`, `people_graduate`, or `people_alumni`
- **Add publications:** Add entries to `_data/publications.yml`
- **Add blog posts:** Create new `.markdown` file in `_posts/` with format `YYYY-MM-DD-title.markdown`
- **Update navigation:** Edit `menu` section in `_data/settings.yml`
- **Modify styling:** Edit `_sass/main.scss`

## Deployment

The site is hosted on GitHub Pages. Push to the appropriate branch (currently `gh-pages`) to deploy automatically.
