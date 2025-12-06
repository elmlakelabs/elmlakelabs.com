# Elm Lake Labs Website

Marketing and brand website for Elm Lake Labs, a precision agriculture technology company.

## Overview

This is a static website built to replace the current Shopify-hosted site at elmlakelabs.com. The design focuses on showcasing Elm Lake Labs' precision agriculture solutions, products, and Blossom farm management software.

### Architecture

- **Main site** (elmlakelabs.com) - This repository. Brand, marketing, product showcases.
- **Store** (store.elmlakelabs.com) - Shopify store for e-commerce functionality.

This separation allows full design control over the marketing site while maintaining Shopify's robust e-commerce features for actual purchases.

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** - No framework dependencies
- **Google Fonts** - Instrument Serif + DM Sans

### Design Philosophy

"Precision Futurism meets Earth" - The design combines:

- **Technical precision** reflecting RTK/GPS technology (grid patterns, coordinates, data visualization)
- **Earth tones** grounding the site in agriculture
- **Bold typography** using Instrument Serif for headlines
- **Subtle tech-inspired details** (animated data points, grid overlays)
- **Dark theme** with vibrant green accents suggesting growth and innovation

## Development

### Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve

# PHP
php -S localhost:8000
```

### File Structure

```
elmlakelabs.com/
├── index.html      # Main page
├── styles.css      # All styles
├── main.js         # JavaScript functionality
├── README.md       # This file
└── TODO.md         # Future improvements
```

## Deployment

This site is designed to be deployed to any static hosting service:

- **GitHub Pages** - Enable in repository settings
- **Netlify** - Connect repository for automatic deploys
- **Vercel** - Similar to Netlify
- **Cloudflare Pages** - Free, fast CDN

### Domain Configuration

1. Deploy site to chosen host
2. Point elmlakelabs.com DNS to the host
3. Configure store.elmlakelabs.com subdomain in Shopify
4. Update all "Shop" links to point to store.elmlakelabs.com

## Content Sections

1. **Hero** - Main value proposition with animated GPS/coordinate visuals
2. **Stats Bar** - Key metrics (accuracy, support, farms equipped)
3. **Solutions** - Four main service areas
4. **Products** - Featured FJD equipment (links to Shopify store)
5. **Software** - Blossom farm management platform
6. **About** - Company mission and values
7. **Contact** - Email and social links
8. **Footer** - Navigation and legal links

## Browser Support

Tested and optimized for:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile Safari/Chrome

## License

Copyright 2024 Elm Lake Labs. All rights reserved.
