# Baan Rai Nai Fun - Static Website

A beautiful, responsive static website for Baan Rai Nai Fun, a garden homestay and café in Chiang Mai, Thailand.

## 🌿 About

This is a 4-page static website showcasing:
- **Landing Page** - Hero section with feature cards and location map
- **Our Story** - The inspiring journey from empty plot to garden sanctuary
- **Café & Restaurant** - Menu highlights and dining philosophy
- **Homestay** - Room types and booking information

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/maruai-co/baanrainaifun-temp.git
   cd baanrainaifun-temp
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
   
   **Option A: Python**
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000
   ```
   
   **Option B: Node.js**
   ```bash
   npx serve .
   # Visit http://localhost:3000
   ```

3. **Edit and customize**
   - Modify HTML files for content changes
   - Update CSS in `css/styles.css` for styling
   - Enhance functionality in `js/main.js`

### GitHub Pages Deployment

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Set Source to "Deploy from a branch"
   - Select branch: `main`
   - Select folder: `/ (root)`
   - Save

3. **Access your site**
   - Your site will be available at: `https://maruai-co.github.io/baanrainaifun-temp/`
   - It may take a few minutes to deploy initially

## 📁 Project Structure

```
/
├── index.html              # Landing page
├── our-story.html          # Our Story page
├── cafe.html              # Café & Restaurant page
├── homestay.html          # Homestay page
├── robots.txt             # SEO robots file
├── sitemap.xml            # SEO sitemap
├── /assets/
│   ├── /images/           # All images (placeholders included)
│   │   ├── landing-card-our-story.jpg
│   │   ├── landing-card-cafe.jpg
│   │   ├── landing-card-homestay.jpg
│   │   ├── map.jpg
│   │   ├── our-story-before.jpg
│   │   ├── our-story-after.jpg
│   │   ├── founders.jpg
│   │   ├── timeline-1.jpg
│   │   ├── timeline-2.jpg
│   │   ├── umami-sauce.jpg
│   │   ├── best-seller-1.jpg
│   │   ├── best-seller-2.jpg
│   │   ├── best-seller-3.jpg
│   │   ├── signature-drink-1.jpg
│   │   ├── signature-drink-2.jpg
│   │   ├── room-type-1.jpg
│   │   ├── room-type-2.jpg
│   │   └── room-type-3.jpg
│   └── /pdf/
│       └── menu.pdf       # Restaurant menu (placeholder)
├── /css/
│   └── styles.css         # Main stylesheet
└── /js/
    └── main.js           # JavaScript for navigation and enhancements
```

## 🎨 Design Features

### Color Palette
- **Primary Green**: `#2d5016` - Deep forest green
- **Accent Green**: `#4a7c59` - Medium garden green  
- **Light Green**: `#8fbc8f` - Soft sage green
- **Cream**: `#faf8f3` - Warm background
- **White**: `#ffffff` - Pure white for cards

### Typography
- Clean, readable Segoe UI font family
- Proper heading hierarchy (H1 → H2 → H3)
- Generous line spacing for readability

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Hamburger menu for mobile navigation
- Touch-friendly button sizes

## ♿ Accessibility Features

- **Semantic HTML** - Proper heading structure and landmarks
- **Keyboard Navigation** - All interactive elements are keyboard accessible
- **Screen Reader Support** - ARIA labels and alt text throughout
- **Color Contrast** - WCAG compliant contrast ratios
- **Focus Indicators** - Visible focus rings for keyboard users
- **Skip Links** - Quick navigation to main content

## 🔧 Customization

### Adding New Content

1. **New Page**: Copy an existing HTML file and update:
   - `<title>` and meta tags
   - Navigation `aria-current` attribute
   - Main content

2. **New Images**: 
   - Add to `/assets/images/`
   - Update alt text for accessibility
   - Use consistent sizing and `loading="lazy"`

3. **Styling**: 
   - Modify CSS custom properties in `:root` for global changes
   - Add new components following existing patterns

### Content Updates

**Replace Placeholder Content:**
- Update contact information in footer
- Replace Airbnb booking links with real URLs
- Add actual images to `/assets/images/`
- Replace `menu.pdf` with real menu

**SEO Optimization:**
- Update Open Graph images with real photos
- Customize meta descriptions for each page
- Add Google Analytics or other tracking

## 🚀 Performance

- **Optimized Images** - Lazy loading and proper sizing
- **Minimal CSS** - Under 400 lines, no frameworks
- **Fast Loading** - No external dependencies except font fallbacks
- **Progressive Enhancement** - Works without JavaScript

## 📱 Browser Support

- **Modern Browsers** - Chrome, Firefox, Safari, Edge (latest 2 versions)
- **Mobile** - iOS Safari, Chrome Mobile, Samsung Internet
- **Accessibility** - Screen readers and assistive technologies

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test on multiple devices/browsers
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions about the website or Baan Rai Nai Fun:
- **Email**: info@baanrainaifun.com
- **Location**: Chiang Mai, Thailand
- **Hours**: Daily 8:00 AM - 6:00 PM

---

Built with ❤️ for sustainable living and authentic Thai hospitality.
