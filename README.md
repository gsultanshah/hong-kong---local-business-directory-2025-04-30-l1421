# Hong Kong - Local Business Directory 🏢

> Discover the best local businesses in Hong Kong - A comprehensive directory website featuring local establishments, services, and venues across Hong Kong.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
  - [Directory Items](#directory-items)
  - [Categories](#categories)
  - [Hero Section](#hero-section)
  - [Styling](#styling)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Overview

This directory website showcases Hong Kong's local businesses in a clean, responsive 3-column grid layout. Built with HTML5, CSS3, and JavaScript, it provides an easy-to-navigate interface for discovering local establishments.

## Features

- 📱 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📍 Interactive map integration
- 💼 Business profile pages
- 📱 Mobile-friendly design
- 🔄 Easy content updates
- 🎨 Customizable styling

## Getting Started

### Prerequisites

- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS
- Git installed
- Web browser

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hk-business-directory.git
```

2. Navigate to project directory:
```bash
cd hk-business-directory
```

3. Open `index.html` in your browser to view the site.

## Directory Structure

```
hk-business-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   ├── main.js
│   │   └── search.js
│   └── images/
├── data/
│   └── businesses.json
└── README.md
```

## Customization Guide

### Directory Items

To add or edit business listings, modify the `data/businesses.json` file:

```json
{
  "businesses": [
    {
      "id": "001",
      "name": "Business Name",
      "category": "Restaurant",
      "address": "123 Nathan Road, TST",
      "phone": "+852 1234 5678",
      "website": "https://example.com",
      "image": "assets/images/business.jpg"
    }
  ]
}
```

### Categories

Update categories in the `index.html` file:

```html
<div class="categories">
  <button class="category-btn" data-category="all">All</button>
  <button class="category-btn" data-category="restaurants">Restaurants</button>
  <button class="category-btn" data-category="retail">Retail</button>
  <!-- Add more categories as needed -->
</div>
```

### Hero Section

Modify the hero section in `index.html`:

```html
<section class="hero">
  <h1>Your Custom Title</h1>
  <p>Your custom description text</p>
  <img src="path/to/your/image.jpg" alt="Hero Image">
</section>
```

### Styling

Customize colors and styles in `assets/css/style.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
  --background-color: #your-color;
}
```

## Deployment

1. Build your site:
```bash
npm run build
```

2. Deploy to your hosting service:
```bash
npm run deploy
```

## Custom Domain Setup

1. Purchase domain from your preferred registrar
2. Add DNS records:
   ```
   A Record: @ -> your-server-ip
   CNAME: www -> your-domain.com
   ```
3. Update domain settings in your hosting panel
4. Wait for DNS propagation (24-48 hours)

## Troubleshooting

Common issues and solutions:

- **Images not loading**: Check file paths and permissions
- **Search not working**: Clear browser cache and verify JavaScript console
- **Styling issues**: Validate CSS and check browser compatibility
- **Mobile layout problems**: Test with different devices and screen sizes

## Resources

- [Documentation Wiki](https://github.com/yourusername/hk-business-directory/wiki)
- [Issue Tracker](https://github.com/yourusername/hk-business-directory/issues)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

📫 **Contact Support**: support@hkdirectory.com

Made with ❤️ in Hong Kong