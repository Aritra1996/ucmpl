# Plastik Global Export Website

A complete export-focused website for **Plastik Global** built with HTML, CSS, and vanilla JavaScript. This modern, dark-themed website showcases Plastik Global's products, export capabilities, and global presence.

## 🌟 Features

### Design & Theme
- **Dark Theme**: Professional dark navy/charcoal background with light cyan and bright green accents
- **Modern UI**: Clean, professional design with subtle animations and hover effects
- **Responsive**: Fully responsive design that works perfectly on desktop, tablet, and mobile
- **Typography**: Clean, professional fonts (Inter, Poppins) for excellent readability

### Pages
1. **Home Page** - Hero section, company intro, features, stats, and CTAs
2. **About Us** - Company overview, mission/vision, values, manufacturing capabilities, and leadership team
3. **Products** - Comprehensive product catalog with filtering, detailed descriptions, and export capabilities
4. **Global Presence** - Interactive world map, export statistics, regional markets, and client testimonials
5. **Contact** - Contact form, office locations, map, and FAQ section

### Interactive Features
- **Smooth Scrolling**: Seamless navigation between sections
- **Scroll Animations**: Elements reveal as you scroll with fade-in effects
- **Animated Counters**: Statistics animate when they come into view
- **Hover Effects**: Interactive cards and buttons with smooth transitions
- **Mobile Menu**: Responsive navigation for mobile devices
- **Form Validation**: Contact form with real-time validation
- **FAQ Accordion**: Expandable FAQ section
- **Product Filtering**: Filter products by category
- **Modal Windows**: Detailed product information in popup modals

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation
1. Download or clone this repository
2. Open `index.html` in your web browser
3. For development, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

### File Structure
```
plastik-global-export-website/
├── index.html              # Homepage
├── about.html              # About Us page
├── products.html           # Products page
├── global-presence.html    # Global Presence page
├── contact.html            # Contact page
├── assets/
│   ├── css/
│   │   └── main.css        # Main stylesheet
│   ├── js/
│   │   ├── main.js         # Main JavaScript
│   │   └── animations.js   # Animation controller
│   └── images/             # Image assets (to be added)
└── README.md               # This file
```

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` section in `assets/css/main.css`:

```css
:root {
    --primary-bg: #0f1419;        /* Dark background */
    --secondary-bg: #1a1f2e;      /* Secondary background */
    --brand-primary: #00d4ff;     /* Light cyan accent */
    --brand-secondary: #00ff88;   /* Bright green accent */
    --text-primary: #ffffff;      /* Primary text color */
    --text-secondary: #b8c5d1;   /* Secondary text color */
}
```

### Content
- **Company Information**: Update company details in each HTML file
- **Products**: Modify product information in `products.html`
- **Contact Details**: Update contact information in `contact.html`
- **Statistics**: Change counter values in the respective pages

### Images
Add your company images to the `assets/images/` directory and update the image paths in the HTML files.

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1024px
- **Mobile**: Below 768px

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern CSS with Grid, Flexbox, and custom properties
- **Vanilla JavaScript**: No frameworks, pure JavaScript
- **Font Awesome**: Icons
- **Google Fonts**: Typography

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers

### Performance
- Optimized CSS and JavaScript
- Lazy loading for images
- Efficient animations using CSS transforms
- Minimal external dependencies

## 📞 Contact Information

For questions about this website or Plastik Global's services:

- **Company**: Plastik Global.
- **Location**: Haridwar, Uttarakhand, India
- **Email**: info@ucmpl.com
- **Website**: https://ucmpl.com

## 📄 License

This website is created for Plastik Global. All rights reserved.

## 🚀 Deployment

### Static Hosting
This website can be deployed to any static hosting service:
- **Netlify**: Drag and drop the files
- **Vercel**: Connect your repository
- **GitHub Pages**: Push to a GitHub repository
- **AWS S3**: Upload files to an S3 bucket

### Web Server
Upload all files to your web server's public directory (e.g., `public_html` or `www`).

## 🔄 Updates and Maintenance

### Regular Updates
- Update statistics and numbers quarterly
- Add new products as they become available
- Update client testimonials
- Refresh content to keep it current

### Performance Monitoring
- Monitor page load times
- Check mobile responsiveness
- Test contact form functionality
- Verify all links work correctly

## 🎯 SEO Features

- Semantic HTML structure
- Meta tags for social sharing
- Open Graph tags
- Proper heading hierarchy
- Alt text for images
- Clean URL structure

## 🛠️ Development

### Adding New Pages
1. Create a new HTML file
2. Include the main CSS and JavaScript files
3. Follow the existing structure and styling patterns
4. Update navigation menus

### Adding New Animations
1. Add CSS keyframes in `assets/css/main.css`
2. Use the AnimationController class in `assets/js/animations.js`
3. Add appropriate classes to HTML elements

### Customizing Forms
1. Update form fields in the HTML
2. Modify validation in the JavaScript
3. Connect to your backend API for form submission

---

**Created by**: Senior Full-Stack Web Developer & Creative UI Designer  
**Date**: January 2025  
**Framework**: HTML5, CSS3, Vanilla JavaScript  
**Theme**: Dark Professional Export Website
