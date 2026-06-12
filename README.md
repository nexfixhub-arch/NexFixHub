# NexFixHub Website

A modern, responsive website for NexFixHub - an intelligent issue resolution platform.

## Features

- **Modern Design**: Clean, professional landing page with gradient accents
- **Responsive**: Fully responsive design that works on all devices
- **Documentation**: Comprehensive documentation with multiple guides
- **Fast**: Optimized for performance and user experience
- **Accessible**: Built with accessibility standards in mind

## File Structure

```
.
├── index.html              # Main landing page
├── styles/
│   ├── main.css           # Main stylesheet
│   └── docs.css           # Documentation styles
├── scripts/
│   └── main.js            # Main JavaScript file
├── docs/
│   ├── getting-started.html
│   ├── api-reference.html
│   ├── configuration.html
│   └── troubleshooting.html
└── README.md              # This file
```

## Getting Started

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

## Deployment

### GitHub Pages

To deploy this website using GitHub Pages:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select the `website` branch as the source
4. Your site will be available at `https://nexfixhub-arch.github.io/NexFixHub`

### Other Hosting

You can also deploy this static website to any static hosting service:
- Netlify
- Vercel
- AWS S3
- Firebase Hosting
- etc.

## Customization

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

### Content

- Edit `index.html` for the main landing page
- Edit files in `docs/` folder for documentation
- Update contact information in the footer

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - see LICENSE file for details

## Support

For questions or issues:
- Email: support@nexfixhub.com
- GitHub Issues: https://github.com/nexfixhub-arch/NexFixHub/issues
