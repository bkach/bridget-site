# Bridget Barnes Psychotherapy

A modern, clean website for Bridget Barnes Psychotherapy built with Hugo and the PaperMod theme.

## Local Development

### Prerequisites
- Hugo Extended version 0.147.9 or later
- Git

### Running Locally
```bash
# Clone the repository
git clone <your-repo-url>
cd bridget-site

# Start the development server
hugo server --bind 0.0.0.0 --port 1313
```

The site will be available at `http://localhost:1313`

## Deployment

### Netlify (Recommended)
This site is configured for automatic deployment on Netlify:

1. Connect your GitHub repository to Netlify
2. Netlify will automatically detect Hugo and use the settings in `netlify.toml`
3. Build settings:
   - Build command: `hugo --gc --minify`
   - Publish directory: `public`
   - Hugo version: 0.147.9

### Manual Build
```bash
# Build the site
hugo --gc --minify

# The built site will be in the `public/` directory
```

## Site Structure

- `content/` - Markdown content files
- `layouts/` - Custom Hugo templates
- `static/` - Static assets (images, CSS, JS)
- `config.toml` - Hugo configuration
- `netlify.toml` - Netlify deployment configuration

## Content Management

### Adding New Pages
Create markdown files in the `content/` directory:

```markdown
---
title: "Page Title"
date: 2024-01-01
draft: false
---

Page content here...
```

### Blog Posts
Add blog posts to `content/posts/` with the same front matter format.

## Customization

### Theme
This site uses the PaperMod theme with custom modifications. Theme files are in `themes/PaperMod/`.

### Styling
Custom CSS can be added to `assets/css/` and will be automatically compiled.

## Support

For issues or questions about the site, please contact the development team. 