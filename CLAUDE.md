# CLAUDE.md

## Project Overview

This is a **Jekyll-based GitHub Pages portfolio site** for Image Bhattarai, showcasing GIS (Geographic Information Systems) and Remote Sensing research. The site is hosted at `bhattaraicool-spec.github.io`.

## Repository Structure

```
/
├── _config.yml      # Jekyll configuration (theme, title)
├── index.md         # Main portfolio page — all site content lives here
├── output/          # Project visualization images (PNG, JPG)
├── README.md        # Repository description
└── CLAUDE.md        # This file
```

## Tech Stack

- **Static site generator:** Jekyll (via GitHub Pages automatic builds)
- **Theme:** `jekyll-theme-cayman`
- **Content format:** Markdown with Jekyll front matter conventions
- **No JavaScript, CSS overrides, or custom layouts**

## Build & Deployment

- There is **no local build step** — GitHub Pages builds and deploys automatically on push to the default branch.
- To test locally, install Jekyll and run `bundle exec jekyll serve`, but this is not required for the workflow.
- There are **no npm scripts, Makefile, or CI/CD pipelines**.

## Development Conventions

### Content editing
- All portfolio content is in `index.md`. Edit this single file to update projects.
- Each project section uses `###` headings, bullet lists with bold labels, and embedded images from `output/`.
- Project sections are separated by horizontal rules (`---`).

### Images and assets
- Store output images in the `output/` directory.
- Reference images with relative paths: `./output/filename.ext`.
- Use descriptive filenames (e.g., `Figure3_Classification_Map.png`).

### Commit style
- Historical commits use short messages like "Update index.md" or "Add files via upload".
- Prefer descriptive messages that explain what content changed.

## Key Files

| File | Purpose |
|------|---------|
| `_config.yml` | Jekyll theme (`jekyll-theme-cayman`) and site title |
| `index.md` | All portfolio content — project descriptions, images, links |
| `output/` | Directory for project visualization images |

## Testing & Linting

- No test suite, linting, or formatting tools are configured.
- Validate Markdown syntax manually or with a Markdown preview before committing.

## Notes for AI Assistants

- This is a minimal static site. Avoid introducing build tooling, frameworks, or unnecessary complexity.
- When adding new projects to `index.md`, follow the existing pattern: heading, description paragraph, bullet-list methodology, image embed, and GitHub repo link.
- Do not modify the Jekyll theme or `_config.yml` unless explicitly asked.
- Keep Markdown clean and compatible with GitHub-flavored Markdown / Jekyll rendering.
