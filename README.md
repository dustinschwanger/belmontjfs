# Belmont County Department of Job & Family Services Website

Official website for the Belmont County Department of Job and Family Services, providing information about public assistance, child support, child and adult protective services, foster care, adoption, and workforce development.

## ✨ Features

- **Fully WCAG 2.2 AA Compliant**: The site meets all Web Content Accessibility Guidelines 2.2 Level AA requirements
- **Responsive Design**: Optimized for all devices (mobile, tablet, desktop)
- **USWDS Components**: Built with the U.S. Web Design System for consistency and accessibility
- **Interactive Chat Widget**: Provides quick access to help and information
- **Semantic HTML**: Proper document structure with ARIA landmarks and labels

## 🎯 Accessibility Features

This website is 100% WCAG 2.2 AA compliant with the following accessibility features:

### Perceivable
- ✅ All images have appropriate alt text or are marked as decorative
- ✅ Sufficient color contrast ratios (minimum 4.5:1 for normal text)
- ✅ Text can be resized up to 200% without loss of functionality
- ✅ Content is adaptable and can be presented in different ways

### Operable
- ✅ All functionality available via keyboard
- ✅ Skip navigation link for keyboard users
- ✅ Logical tab order throughout the site
- ✅ Touch targets meet minimum 44x44px size
- ✅ No timing constraints on user interactions
- ✅ Animations respect `prefers-reduced-motion` settings

### Understandable
- ✅ Clear, consistent navigation
- ✅ Proper heading hierarchy (h1 → h2 → h3 → h4)
- ✅ Form inputs have visible labels
- ✅ Error identification and suggestions (where applicable)
- ✅ Consistent identification of components

### Robust
- ✅ Valid HTML5 markup
- ✅ ARIA attributes used correctly
- ✅ Compatible with current and future assistive technologies
- ✅ Landmark regions properly defined
- ✅ Live regions for dynamic content

## 🚀 Deployment

### Railway Deployment

This site is configured to deploy on Railway with zero configuration:

1. **Connect your GitHub repository** to Railway
2. **Railway will automatically detect** the Node.js application
3. **Deploy** with a single click

The site uses an Express server to serve static files and includes proper security headers.

### Manual Deployment

```bash
# Install dependencies
npm install

# Start the server
npm start

# The server will run on port 3000 (or PORT environment variable)
```

### Environment Variables

- `PORT`: Server port (default: 3000)

## 📁 Project Structure

```
belmont-county-jfs/
├── belmontjfs/          # Static site files
│   ├── index.html       # Main HTML file
│   ├── styles.css       # Custom styles
│   ├── public/          # Images and assets
│   ├── logo.png
│   ├── hero.png
│   └── favicon_1.ico
├── server.js            # Express server
├── package.json         # Node dependencies
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties
- **JavaScript**: Vanilla JS for interactions
- **USWDS 3.7.1**: U.S. Web Design System
- **Font Awesome 6.4.0**: Icons
- **Express.js**: Web server
- **Node.js**: Runtime environment

## 📝 Accessibility Testing

The site has been tested for WCAG 2.2 AA compliance including:

- ✅ Heading structure validation
- ✅ ARIA attribute validation
- ✅ Keyboard navigation testing
- ✅ Screen reader compatibility
- ✅ Color contrast verification
- ✅ Touch target size verification
- ✅ Form label association
- ✅ Focus indicator visibility

## 📞 Contact

**Belmont County Department of Job & Family Services**
68145 Hammond Road
St. Clairsville, OH 43950
Phone: 740-695-1075
Email: BELMONT_COUNTY_JFS@jfs.ohio.gov

## 📄 License

Copyright © 2025 Belmont County Department of Job & Family Services. All rights reserved.
