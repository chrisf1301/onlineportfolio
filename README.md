# Personal Portfolio Website

A modern, responsive personal website built with HTML, CSS, and JavaScript. This website features a beautiful design with smooth animations, mobile-first responsive design, and interactive elements.

## Features

- 🎨 **Modern Design**: Clean, professional layout with beautiful gradients and typography
- 📱 **Responsive**: Mobile-first design that works perfectly on all devices
- ✨ **Animations**: Smooth scroll animations and interactive hover effects
- 🧭 **Navigation**: Fixed navigation bar with smooth scrolling to sections
- 📊 **Skills Display**: Organized skill categories with interactive elements
- 📞 **Contact Section**: Professional contact information with social media links
- 🚀 **Performance**: Optimized for fast loading and smooth performance

## File Structure

```
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality and interactions
└── README.md           # This file
```

## Customization Guide

### 1. Personal Information

Edit the `index.html` file to update your personal information:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Update "Web Developer & Designer" to match your profession
- **Description**: Customize the hero description to reflect your expertise
- **About Me**: Update the about section with your personal story
- **Stats**: Modify the experience numbers to match your background
- **Skills**: Update the skills and technologies to match your expertise
- **Contact**: Replace placeholder contact information with your actual details

### 2. Styling

The `styles.css` file contains all the styling. You can customize:

- **Colors**: Update the color scheme by changing CSS variables
- **Fonts**: Modify the font family and sizes
- **Layout**: Adjust spacing, padding, and margins
- **Animations**: Customize animation durations and effects

### 3. Functionality

The `script.js` file handles all interactive features:

- Mobile navigation
- Smooth scrolling
- Scroll animations
- Typing effects
- Interactive elements

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize content**: Edit the HTML file with your personal information
3. **Modify styling**: Update the CSS file to match your preferred design
4. **Test responsiveness**: Resize your browser window to test mobile responsiveness

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

To deploy your website:

1. **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages
2. **Netlify**: Drag and drop your folder to Netlify
3. **Vercel**: Connect your GitHub repository to Vercel
4. **Traditional hosting**: Upload files to any web hosting service

## Customization Examples

### Changing the Color Scheme

In `styles.css`, look for these color values and update them:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #7c3aed;
--accent-color: #fbbf24;

/* Background colors */
--bg-light: #f8fafc;
--bg-dark: #1f2937;
```

### Adding New Sections

To add a new section, follow this pattern in `index.html`:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section Title</h2>
        <div class="new-section-content">
            <!-- Your content here -->
        </div>
    </div>
</section>
```

Then add corresponding CSS in `styles.css`:

```css
.new-section {
    padding: 5rem 0;
    background: var(--bg-light);
}

.new-section-content {
    /* Your styling here */
}
```

## Tips for Best Results

1. **Images**: Replace the profile placeholder with your actual photo
2. **Content**: Write authentic, engaging content that represents you
3. **Performance**: Optimize images and keep file sizes small
4. **SEO**: Add meta tags and descriptions for better search visibility
5. **Testing**: Test on multiple devices and browsers

## Support

If you need help customizing your website:

1. Check the HTML structure for the section you want to modify
2. Look for corresponding CSS classes in the stylesheet
3. Use browser developer tools to inspect and modify elements
4. Test changes incrementally to avoid breaking the layout

## License

This project is open source and available under the MIT License. Feel free to use and modify it for your personal or commercial projects.

---

**Happy coding! 🚀**
