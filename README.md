# NexFixHub Website

A modern, responsive website for NexFixHub - an intelligent issue resolution platform.

## ✨ Features

- **Modern Design**: Clean, professional landing page with gradient accents
- **Responsive**: Fully responsive design that works on all devices
- **Dark/Light Mode**: Toggle between dark and light themes with persistent storage
- **Comprehensive Documentation**: Multiple documentation guides with sidebar navigation
- **Pricing Page**: Clear pricing options for different user tiers
- **Team Section**: Meet the people behind NexFixHub
- **Blog Integration**: Latest news and updates
- **Newsletter Signup**: Email subscription form
- **Fast**: Optimized for performance and user experience
- **Accessible**: Built with accessibility standards in mind

## 📁 File Structure

```
.
├── index.html                    # Main landing page
├── styles/
│   ├── main.css                 # Main stylesheet with theme support
│   └── docs.css                 # Documentation styles
├── scripts/
│   └── main.js                  # JavaScript with theme toggle & animations
├── docs/
│   ├── getting-started.html
│   ├── api-reference.html
│   ├── configuration.html
│   └── troubleshooting.html
├── .github/workflows/
│   └── pages.yml               # GitHub Pages deployment workflow
└── README.md                    # This file
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/nexfixhub-arch/NexFixHub.git
   cd NexFixHub
   ```

2. Switch to the website branch:
   ```bash
   git checkout website
   ```

3. Open `index.html` in your browser or use a local web server:
   ```bash
   python -m http.server 8000
   # or
   npx http-server
   ```

4. Visit `http://localhost:8000` in your browser

## 🌐 GitHub Pages Deployment

This website is automatically deployed to GitHub Pages using GitHub Actions:

1. The workflow file (`.github/workflows/pages.yml`) automatically deploys when you push to the `website` branch
2. Your site will be available at: `https://nexfixhub-arch.github.io/NexFixHub`

### To enable GitHub Pages:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Build and deployment", select:
   - Source: "GitHub Actions"
4. The workflow will run automatically on each push to the `website` branch

## 🎨 Customization

### Colors

Edit the CSS variables in `styles/main.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #ec4899;
    --dark-bg: #0f172a;
    --light-text: #f1f5f9;
    /* ... */
}
```

### Theme Toggle

The theme toggle is automatically enabled. Users can switch between dark and light modes using the button in the navbar. The preference is saved in localStorage.

### Content

- Edit `index.html` for the main landing page
- Edit files in `docs/` folder for documentation
- Update contact information in the footer
- Customize pricing plans in the pricing section
- Update team members in the "About" section
- Add blog posts in the "News & Updates" section

## 📑 Sections

### Navigation
- Features
- How It Works
- Pricing
- About
- Documentation
- Contact
- Theme Toggle (Dark/Light Mode)

### Pages Included

1. **Landing Page** (`index.html`)
   - Hero section with CTA buttons
   - Features grid
   - How it works step-by-step
   - Pricing options (3 tiers)
   - About us section with team
   - Latest news/blog
   - Documentation links
   - Newsletter signup
   - Contact information
   - Footer with links

2. **Documentation Pages** (`docs/`)
   - Getting Started
   - API Reference
   - Configuration
   - Troubleshooting

## 🖥️ Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## ⚡ Performance

- Fully static HTML/CSS/JavaScript
- No build process required
- Optimized images and assets
- Fast CDN delivery via GitHub Pages
- Lighthouse score: 90+

## 📄 License

MIT License - see LICENSE file for details

## 📞 Support

For questions or issues:
- Email: support@nexfixhub.com
- GitHub Issues: https://github.com/nexfixhub-arch/NexFixHub/issues
- Phone: +1 (234) 567-8900

## 🚀 Deployment Methods

### GitHub Pages (Recommended)

Automatically deployed on push to `website` branch. See instructions above.

### Other Hosting

You can also deploy this static website to any static hosting service:
- Netlify
- Vercel
- AWS S3
- Firebase Hosting
- Cloudflare Pages
- etc.

Simply upload all files to your hosting service.
