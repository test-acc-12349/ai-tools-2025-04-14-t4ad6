# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for professionals, developers, and enthusiasts.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Support & Resources](#support--resources)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools and resources in a clean, three-column grid layout. The directory is built with HTML5, CSS3, and vanilla JavaScript, ensuring fast loading times and easy customization.

## Features

- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 💨 Fast loading times
- 📱 Mobile-friendly design
- 🎨 Customizable styling
- 🔄 Easy content updates

## Getting Started

### Prerequisites
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS
- Git installed locally

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Open index.html in your browser
```

## Directory Structure

```
ai-tools-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
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
  "name": "Tool Name",
  "description": "Tool description",
  "category": "Category",
  "url": "https://toolurl.com",
  "image": "tool-image.jpg"
}
```

### Modifying Categories

1. Open `index.html`
2. Locate the category section:

```html
<div class="categories">
  <button class="category-btn" data-category="all">All</button>
  <!-- Add new categories here -->
</div>
```

### Updating Hero Section

1. Open `index.html`
2. Find the hero section:

```html
<section class="hero">
  <h1>AI Tools Directory</h1>
  <p>Your custom description here</p>
</section>
```

### Customizing Colors

1. Open `assets/css/style.css`
2. Modify the CSS variables:

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
}
```

## Deployment

### GitHub Pages
1. Go to repository settings
2. Navigate to "Pages"
3. Select main branch
4. Save changes

### Netlify
1. Connect your GitHub repository
2. Select main branch
3. Deploy

## Custom Domain Setup

1. Purchase domain from registrar
2. Add custom domain in deployment platform
3. Configure DNS settings:
```
A Record: @ 76.76.21.21
CNAME: www your-username.github.io
```

## Troubleshooting

### Common Issues

**Images not loading**
- Check file paths
- Verify image formats
- Ensure proper permissions

**Search not working**
- Check console for errors
- Verify JavaScript loading
- Clear browser cache

## Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## Support & Resources

- 📚 [Documentation Wiki](https://github.com/yourusername/ai-tools-directory/wiki)
- 🐛 [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- 💬 [Community Forum](https://github.com/yourusername/ai-tools-directory/discussions)

### Helpful Links
- [HTML5 Guide](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3 Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Your Name]