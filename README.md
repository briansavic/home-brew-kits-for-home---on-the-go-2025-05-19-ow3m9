# Home Brew Kits For Home & On The Go 🍺

> Your home brewing ideas Start...Now

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources & Support](#resources--support)

## Overview

Home Brew Kits For Home & On The Go is a responsive directory website showcasing brewing equipment and supplies in a clean, 3-column grid layout. The site is built with HTML5, CSS3, and JavaScript, offering easy customization and maintenance.

## Features

- Responsive 3-column grid layout
- Category-based filtering
- Search functionality
- Dynamic item cards
- Mobile-friendly design
- SEO optimized structure
- Fast loading performance
- Cross-browser compatibility

## Getting Started

### Prerequisites
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS
- Git installed
- Web browser

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/homebrew-directory.git
```

2. Navigate to project directory:
```bash
cd homebrew-directory
```

3. Open `index.html` in your browser to view the site

## Directory Structure

```
homebrew-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── main.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── data/
│   └── directory-items.json
└── README.md
```

## Customization Guide

### Adding Directory Items

1. Open `data/directory-items.json`
2. Add new items following this format:

```json
{
  "id": "item-1",
  "title": "Basic Brewing Kit",
  "category": "starter-kits",
  "description": "Perfect for beginners",
  "image": "assets/images/basic-kit.jpg",
  "price": "49.99"
}
```

### Modifying Categories

1. Open `index.html`
2. Locate the category section:

```html
<div class="categories">
  <button class="category-btn" data-category="all">All</button>
  <button class="category-btn" data-category="starter-kits">Starter Kits</button>
  <!-- Add more categories here -->
</div>
```

### Updating Hero Section

1. Navigate to `index.html`
2. Find the hero section:

```html
<section class="hero">
  <h1>Your home brewing ideas Start...Now</h1>
  <!-- Modify content here -->
</section>
```

### Customizing Colors

1. Open `assets/css/main.css`
2. Modify the root variables:

```css
:root {
  --primary-color: #4A90E2;
  --secondary-color: #2C3E50;
  --background-color: #F5F5F5;
}
```

## Deployment

### GitHub Pages
1. Go to repository settings
2. Navigate to "Pages" section
3. Select main branch
4. Save changes

### Alternative Hosting
- Upload files to your web host via FTP
- Deploy to Netlify or Vercel
- Use any static site hosting service

## Custom Domain Setup

1. Purchase domain from registrar
2. Add these DNS records:
```
A     @     185.199.108.153
A     @     185.199.109.153
CNAME www   yourusername.github.io
```
3. Add domain in repository settings

## Troubleshooting

### Common Issues

1. Images not loading
   - Check file paths
   - Verify image extensions
   - Ensure proper permissions

2. Layout breaks
   - Validate HTML
   - Check responsive breakpoints
   - Clear browser cache

3. Categories not filtering
   - Check console for errors
   - Verify category names match
   - Review JavaScript connections

## Resources & Support

- [Documentation Wiki](https://github.com/yourusername/homebrew-directory/wiki)
- [Issue Tracker](https://github.com/yourusername/homebrew-directory/issues)
- [Contributing Guidelines](CONTRIBUTING.md)

### Support Channels
- Email: support@homebrewkits.com
- Twitter: [@HomeBrewKits](https://twitter.com/homebrewkits)
- Discord: [Join Community](https://discord.gg/homebrewkits)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Made with ❤️ by [Your Name]