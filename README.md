# Halfway There - Website

A beautiful, modern website for the Halfway There iOS app that follows Apple design standards and works across all devices.

## 🎨 Design Features

- **Apple Design System**: Follows Apple's Human Interface Guidelines
- **Responsive Design**: Optimized for all devices (mobile, tablet, desktop)
- **Dark Mode Support**: Automatic dark mode detection and switching
- **Accessibility**: WCAG 2.1 AA compliant with keyboard navigation
- **Performance**: Optimized for fast loading and smooth animations
- **Modern Animations**: Subtle, purposeful animations that enhance UX

## 🚀 Quick Start

### Option 1: Simple HTTP Server
```bash
# Navigate to the website directory
cd website

# Start a simple HTTP server (Python 3)
python3 -m http.server 8000

# Or with Python 2
python -m SimpleHTTPServer 8000

# Or with Node.js (if you have http-server installed)
npx http-server

# Open in browser
open http://localhost:8000
```

### Option 2: Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Any Web Server
Simply upload the contents to any web hosting service:
- Netlify
- Vercel
- GitHub Pages
- AWS S3
- Any traditional web hosting

## 📁 File Structure

```
website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   └── images/
│       ├── logo.svg        # App logo
│       ├── favicon.svg     # Browser favicon
│       └── app-store-badge.svg # App Store badge
├── components/             # Reusable components (future)
├── pages/                  # Additional pages (future)
└── README.md              # This file
```

## 🎯 Key Features

### Hero Section
- Compelling headline with gradient text
- Interactive phone mockup with animated isochrone circles
- Clear call-to-action buttons
- Responsive design that works on all screen sizes

### Features Section
- Six key features with icons and descriptions
- Hover animations and smooth transitions
- Grid layout that adapts to screen size

### How It Works
- Three-step process explanation
- Numbered steps with visual hierarchy
- Clear, concise descriptions

### Pricing Section
- Three pricing tiers (Free, Plus, Lifetime)
- Featured plan highlighting
- Transparent pricing with clear feature lists

### Download Section
- App Store download button
- Coming soon indicators for other platforms
- Gradient background for visual impact

## 🎨 Design System

### Colors
- **Primary**: `#007AFF` (Apple Blue)
- **Secondary**: `#5856D6` (Apple Purple)
- **Success**: `#34C759` (Apple Green)
- **Warning**: `#FF9500` (Apple Orange)
- **Error**: `#FF3B30` (Apple Red)

### Typography
- **Font Family**: SF Pro Display (Apple's system font)
- **Fallbacks**: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto
- **Weights**: 300, 400, 500, 600, 700

### Spacing
- **Base Unit**: 1rem (16px)
- **Scale**: xs (0.25rem) to 3xl (4rem)
- **Consistent spacing throughout**

### Shadows
- **Subtle shadows** for depth and hierarchy
- **Hover effects** for interactive elements
- **Backdrop blur** for modern glass effects

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ♿ Accessibility Features

- **Keyboard Navigation**: Full keyboard support
- **Screen Reader**: Proper ARIA labels and semantic HTML
- **Focus Management**: Clear focus indicators
- **Color Contrast**: WCAG 2.1 AA compliant
- **Reduced Motion**: Respects user preferences
- **High Contrast**: Support for high contrast mode

## ⚡ Performance Optimizations

- **CSS Custom Properties**: Efficient theming
- **Optimized Animations**: Hardware-accelerated transforms
- **Lazy Loading**: Images load as needed
- **Minimal JavaScript**: Lightweight interactions
- **Efficient Selectors**: Optimized CSS performance

## 🔧 Customization

### Colors
Edit the CSS custom properties in `assets/css/styles.css`:
```css
:root {
    --primary: #007AFF;
    --secondary: #5856D6;
    /* ... other colors */
}
```

### Content
Update the content in `index.html`:
- Hero section text
- Feature descriptions
- Pricing information
- Contact details

### Images
Replace images in `assets/images/`:
- `logo.svg` - App logo
- `favicon.svg` - Browser icon
- `app-store-badge.svg` - Download button

## 📊 Analytics Integration

The website includes analytics tracking for:
- Download button clicks
- CTA button interactions
- Page load performance
- User engagement metrics

To enable analytics, add your tracking code to the `<head>` section of `index.html`.

## 🚀 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)

### Netlify
1. Connect your GitHub repository
2. Set build command: (leave empty for static site)
3. Set publish directory: `website`
4. Deploy automatically

### Vercel
1. Import your GitHub repository
2. Set framework preset to "Other"
3. Set root directory to `website`
4. Deploy

## 🔍 SEO Optimization

- **Meta Tags**: Proper title, description, and Open Graph tags
- **Semantic HTML**: Proper heading hierarchy and structure
- **Alt Text**: Descriptive alt text for images
- **Schema Markup**: Ready for structured data
- **Performance**: Fast loading times for better rankings

## 🛠️ Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile Browsers**: iOS Safari 14+, Chrome Mobile 90+

## 📝 License

This website is part of the Halfway There project and follows the same license terms.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different devices and browsers
5. Submit a pull request

## 📞 Support

For questions or issues with the website:
- Check the main project documentation
- Open an issue in the repository
- Contact the development team

---

**Last Updated**: December 2024
**Version**: 1.0.0
