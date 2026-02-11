# Strategic Development Advisory Landing Page

A professional, conversion-focused landing page for international development consulting services. Built with clean HTML5, CSS3, and vanilla JavaScript.

## 🎯 Project Overview

This landing page showcases strategic advisory services in international development, featuring:
- 20+ years of field experience
- $200M+ portfolio management track record
- Regional expertise across 15 countries
- Core services in strategic planning, compliance, stakeholder engagement, and proposal development

## 🚀 Live Demo

**View the live site:** [https://noxben.github.io/dev-consultant-landing/](https://noxben.github.io/dev-consultant-landing/)

## 📋 Features

- **Responsive Design**: Mobile-first approach, optimized for all devices
- **Modern Aesthetics**: Custom color palette with sophisticated typography
- **Smooth Animations**: Intersection Observer API for elegant scroll effects
- **Performance Optimized**: Single-file HTML with embedded CSS/JS, no dependencies
- **SEO Ready**: Semantic HTML5, proper meta tags, accessibility best practices
- **Fast Loading**: Optimized assets, web fonts preconnected

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties (CSS variables), Grid, Flexbox, animations
- **JavaScript**: Vanilla JS for smooth scroll and intersection observers
- **Fonts**: Google Fonts (Cormorant Garamond, Work Sans)

## 📁 Project Structure

```
dev-consultant-landing/
├── index.html              # Main landing page
├── versions/               # Version history
│   ├── v1-dev-consultant-landing.html
│   ├── v2-dev-consultant-landing.html
│   └── version-notes.md
├── assets/                 # Static assets
│   ├── images/            # Images and graphics
│   ├── fonts/             # Custom fonts (if needed)
│   └── downloads/         # Downloadable resources
├── css/                    # Future: Separate stylesheets
├── js/                     # Future: Separate scripts
├── docs/                   # Documentation
│   ├── design-notes.md
│   ├── content-strategy.md
│   └── deployment-guide.md
├── .gitignore             # Git ignore rules
├── LICENSE                # MIT License
└── README.md              # This file
```

## 🎨 Design System

### Color Palette
- **Midnight** (`#1a2332`): Primary dark, authority
- **Slate** (`#4a5568`): Body text, secondary
- **Sand** (`#e8dfd2`): Warm neutral, backgrounds
- **Terra** (`#c27355`): Accent, CTAs, highlights
- **Sage** (`#8a9a7b`): Secondary accent, nature
- **Ice** (`#f7f9fb`): Light backgrounds

### Typography
- **Headings**: Cormorant Garamond (serif, elegant)
- **Body**: Work Sans (sans-serif, readable)

### Spacing Scale
Based on 8px grid: 0.5rem (8px), 1rem (16px), 1.5rem (24px), 2rem (32px), 3rem (48px), 4rem (64px), 8rem (128px)

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Git installed
- GitHub account

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/noxben/dev-consultant-landing.git
   cd dev-consultant-landing
   ```

2. **Open in browser**
   - Simply double-click `index.html`
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Node.js (if you have it)
     npx serve
     ```
   - Visit `http://localhost:8000`

3. **Make changes**
   - Edit `index.html` in your favorite editor
   - Refresh browser to see changes
   - No build process required!

### Deployment

**GitHub Pages (Recommended)**
1. Push your code to GitHub
2. Go to Settings → Pages
3. Select source: `main` branch, `/ (root)` folder
4. Save and wait 1-2 minutes
5. Your site is live at `https://noxben.github.io/dev-consultant-landing/`

**Other Options**
- **Netlify**: Drag and drop deployment
- **Vercel**: Connect GitHub repo
- **Surge**: `surge` from command line

## 📝 Customization Guide

### Update Contact Information
Search for and replace:
- `your.email@example.com` → Your actual email
- `+1 (555) 123-4567` → Your phone number

### Modify Content
- **Hero Section**: Update headline, subtitle in `.hero`
- **Services**: Edit the 4 service cards in `.services-grid`
- **Stats**: Update numbers in `.stats-grid`
- **Organizations**: Modify logos in `.logos-grid`

### Change Colors
Update CSS variables in `:root`:
```css
:root {
    --midnight: #1a2332;  /* Your primary dark color */
    --terra: #c27355;     /* Your accent color */
    /* ... */
}
```

### Add New Sections
Follow the existing pattern:
```html
<section class="your-section">
    <div class="section-container">
        <div class="section-label">Label</div>
        <h2>Heading</h2>
        <!-- Your content -->
    </div>
</section>
```

## 🔧 Maintenance

### Version Control Best Practices
```bash
# Check status before committing
git status

# Add and commit changes
git add .
git commit -m "Update: Brief description of what changed"

# Push to GitHub (and deploy)
git push
```

### Commit Message Guidelines
- `feat:` New feature or section
- `fix:` Bug fix or correction
- `style:` Visual/CSS changes
- `content:` Copy updates
- `docs:` Documentation updates
- `refactor:` Code restructuring

Example: `feat: Add testimonials section`

## 📊 Performance

- **Load Time**: ~1.5s on 3G
- **Lighthouse Score**: 95+ (Performance, Accessibility, SEO)
- **Page Size**: ~15KB HTML (gzipped)
- **No Dependencies**: Zero npm packages, zero frameworks

## ♿ Accessibility

- Semantic HTML5 elements
- ARIA labels where needed
- Keyboard navigation support
- Color contrast WCAG AA compliant
- Responsive text sizing

## 🐛 Known Issues

- [ ] Email link needs updating with actual email
- [ ] Phone number is placeholder
- [ ] Organization logos are text-based (consider real logos)

## 📈 Future Enhancements

- [ ] Add testimonials section
- [ ] Integrate contact form with backend
- [ ] Add case studies/portfolio page
- [ ] Implement blog section
- [ ] Add analytics tracking
- [ ] Create separate CSS file for easier maintenance
- [ ] Add dark mode toggle
- [ ] Implement i18n for multiple languages

## 📜 License

MIT License - see [LICENSE](LICENSE) file for details

## 👤 Author

**Strategic Development Advisory**
- Website: [https://noxben.github.io/dev-consultant-landing/](https://noxben.github.io/dev-consultant-landing/)
- Email: your.email@example.com
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🤝 Contributing

This is a personal project, but feedback is welcome! Feel free to:
1. Open an issue for bugs or suggestions
2. Fork the repo and submit a pull request
3. Share your ideas via email

## 📞 Support

Questions or need help customizing? Reach out via email or open an issue.

---

**Last Updated**: February 2026  
**Version**: 1.0.0  
**Status**: Active Development
