# Elm Lake Labs Website

Marketing and brand website for Elm Lake Labs, a precision agriculture technology company.

## Overview

This site replaces the current Shopify-hosted site at elmlakelabs.com. The design showcases Elm Lake Labs' precision agriculture solutions, products, and Blossom farm management software.

### Architecture

- **Main site** (elmlakelabs.com) - This repository. Brand, marketing, product showcases.
- **Store** (store.elmlakelabs.com) - Shopify store for e-commerce functionality.

This separation allows full design control over the marketing site while maintaining Shopify's robust e-commerce features for actual purchases.

## Tech Stack

- **Astro 5.x** - Static site generator
- **Tailwind CSS 4.x** - Utility-first styling
- **TypeScript** - Strict mode enabled
- **Google Fonts** - Instrument Serif + DM Sans

### Design Philosophy

"Precision Futurism meets Earth" - The design combines:

- **Technical precision** reflecting RTK/GPS technology (grid patterns, coordinates, data visualization)
- **Earth tones** grounding the site in agriculture
- **Bold typography** using Instrument Serif for headlines
- **Subtle tech-inspired details** (animated data points, grid overlays)
- **Dark theme** with vibrant green accents suggesting growth and innovation

## Development

### Setup

```bash
npm install
```

### Local Development

```bash
npm run dev
```

Opens at http://localhost:4321

### Build

```bash
npm run build
```

Output in `dist/`

### Preview Production Build

```bash
npm run preview
```

### File Structure

```
elmlakelabs.com/
├── src/
│   ├── components/     # Astro components
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── StatsBar.astro
│   │   ├── Solutions.astro
│   │   ├── Products.astro
│   │   ├── Software.astro
│   │   ├── About.astro
│   │   └── Contact.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── public/             # Static assets
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── README.md
└── TODO.md
```

## Deployment

Deploy to Cloudflare Pages:

1. Connect repository to Cloudflare Pages
2. Build command: `npm run build`
3. Output directory: `dist`
4. Point elmlakelabs.com DNS to Cloudflare

### Domain Configuration

1. Deploy site to Cloudflare Pages
2. Add custom domain elmlakelabs.com
3. Configure store.elmlakelabs.com subdomain in Shopify
4. Update Shopify DNS (CNAME to shops.myshopify.com)

## Content Sections

1. **Hero** - Main value proposition with animated GPS/coordinate visuals
2. **Stats Bar** - Key metrics (accuracy, support, farms equipped)
3. **Solutions** - Four main service areas
4. **Products** - Featured FJD equipment (links to Shopify store)
5. **Software** - Blossom farm management platform
6. **About** - Company mission and values
7. **Contact** - Email and social links
8. **Footer** - Navigation and legal links

## License

Copyright 2024 Elm Lake Labs. All rights reserved.
