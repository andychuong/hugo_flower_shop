# Blooming Flowers - Hugo Site

A complete Hugo website for a flower shop, ready to be imported into Hugo Manager.

## Features

- Complete content structure (home, about, products, blog, contact)
- Responsive design with modern CSS
- Product listings with images
- Blog section for flower care tips
- Contact information and store hours
- Social media links

## Structure

```
flower-shop/
├── content/          # All content pages
│   ├── _index.md    # Home page
│   ├── about.md
│   ├── contact.md
│   ├── products/    # Product pages
│   └── blog/        # Blog posts
├── layouts/          # HTML templates
│   └── _default/    # Default templates
├── static/          # Static assets
│   ├── css/         # Stylesheets
│   └── images/      # Images
├── data/            # Data files
└── hugo.toml        # Site configuration
```

## Getting Started

1. Import this project into Hugo Manager
2. Build the site: `hugo`
3. Serve locally: `hugo server`

## Customization

- Edit `hugo.toml` to change site settings
- Modify content in `content/` directory
- Update styles in `static/css/style.css`
- Replace placeholder images in `static/images/` with your own

## Notes

- Images are SVG placeholders - replace with actual photos
- All content is example/demo content
- Customize colors, fonts, and layout as needed

