# Project Information

This is a Hugo static site project using the Ananke theme.

## About Neurowid

Neurowid is basically Erowid for LLMs, coding tools, and other associated things. As things get weirder, benchmarks become less helpful and the best tools are hard to determine except on vibes. Models and tools in this space all have weird quirks, so it's important to document and understand them for posterity if nothing else.

## Basic Project Structure

- `content/` - Contains markdown files for site content
- `archetypes/` - Contains content templates for new pages/posts
- `themes/ananke/` - The Ananke theme files
- `public/` - The generated static site (created when Hugo builds the site)
- `static/` - Static assets like images that will be copied directly to public/
- `layouts/` - Custom HTML templates (overrides theme templates)
- `assets/` - Custom CSS, JS, and other assets
- `config/` - Configuration files

## Hugo Configuration

The site configuration is in `hugo.toml`:
- Site title: "My New Hugo Site"
- Theme: "ananke"
- Language: English (en-us)

## Theme Information

The project uses the Ananke Gohugo Theme, which is a base theme for building full-featured Hugo sites. It includes features like:
- Blog functionality
- Responsive design
- Disqus comments
- Social media integration
- Multilingual support
- Tachyons CSS framework

## Working with the Project

To start the development server:
```
hugo server
```

To build the static site:
```
hugo
```

To create a new post:
```
hugo new posts/my-post.md
```

To create a new page:
```
hugo new my-page.md
```

## Deployment

The site can be built to the `public/` directory and deployed to any static hosting service like Netlify, GitHub Pages, or Vercel.