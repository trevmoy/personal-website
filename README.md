# Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript. Features include a hero section, about me, projects showcase, skills display, and contact form.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile navigation, hover effects
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading and optimized for SEO

## Getting Started

### 1. Customize Your Content

Replace the placeholder content with your own information:

#### In `index.html`:
- Replace "Your Name" with your actual name
- Update the job title/subtitle in the hero section
- Add your own description and bio in the about section
- Update the statistics (years of experience, projects, clients)
- Replace project information with your actual projects
- Update skills to match your expertise
- Add your contact information (email, phone, location)
- Update social media links in the footer

#### In `styles.css`:
- Customize colors by changing the CSS custom properties
- Adjust fonts, spacing, or layout as needed
- Modify the hero background gradient

### 2. Add Your Images

Replace the placeholder images:
- Add your profile photo (300x300px recommended)
- Add project screenshots (400x250px recommended)
- Update image paths in the HTML

### 3. Set Up the Contact Form

The contact form currently shows an alert. To make it functional:

1. **Using a Form Service** (Recommended for beginners):
   - Sign up for services like Formspree, Netlify Forms, or Getform
   - Update the form action attribute
   - Remove the JavaScript preventDefault

2. **Using Your Own Backend**:
   - Set up a server with Node.js, PHP, or Python
   - Create an endpoint to handle form submissions
   - Update the fetch request in `script.js`

### 4. Deploy Your Website

#### Option 1: GitHub Pages (Free)
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `username.github.io/repository-name`

#### Option 2: Netlify (Free)
1. Create an account at netlify.com
2. Drag and drop your project folder
3. Your site will be live instantly with a custom URL

#### Option 3: Vercel (Free)
1. Create an account at vercel.com
2. Import your GitHub repository
3. Deploy automatically with each push

#### Option 4: Traditional Web Hosting
1. Purchase hosting from providers like Bluehost, HostGator, etc.
2. Upload files via FTP to the public_html folder
3. Your site will be live at your domain

### 5. Custom Domain (Optional)

If you want a custom domain (yourname.com):
1. Purchase a domain from registrars like Namecheap, GoDaddy, or Google Domains
2. Update DNS settings to point to your hosting provider
3. Configure SSL certificate for HTTPS

## Customization Tips

### Colors
The website uses a blue color scheme. To change colors:
1. Find the CSS color values (like `#3498db`) in `styles.css`
2. Replace them with your preferred colors
3. Maintain consistency across the site

### Fonts
To use different fonts:
1. Import Google Fonts in the `<head>` section
2. Update the `font-family` property in CSS

### Animations
The site includes several animations:
- Fade-in effects for sections
- Hover effects on cards and buttons
- Smooth scrolling navigation
- Typing animation for the hero title

To modify or disable animations, edit the CSS and JavaScript files.

### Additional Sections
To add new sections:
1. Add the HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation links
4. Add smooth scrolling support in `script.js`

## Project Structure

```
personal-website/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js          # JavaScript functionality
└── README.md          # This file
```

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 10+
- Edge 16+
- Mobile browsers (iOS Safari, Chrome Mobile)

## SEO Optimization

To improve search engine ranking:
1. Add meta descriptions and keywords
2. Use semantic HTML tags
3. Optimize images (compress and add alt text)
4. Create a sitemap.xml file
5. Add Google Analytics tracking

## Performance Tips

- Compress images before uploading
- Minify CSS and JavaScript for production
- Use a Content Delivery Network (CDN) for faster loading
- Enable GZIP compression on your server

## Troubleshooting

### Common Issues:

1. **Images not loading**: Check file paths and ensure images are in the correct directory
2. **Form not working**: Verify form action URL and server configuration
3. **Mobile menu not working**: Check JavaScript console for errors
4. **Animations not working**: Ensure JavaScript is enabled and files are properly linked

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your website:
1. Check the browser console for error messages
2. Validate your HTML and CSS
3. Test on different devices and browsers
4. Consider hiring a web developer for complex customizations

---

**Happy coding! 🚀**

Make sure to test your website thoroughly before deploying and keep your content updated regularly.
