# Hamed Tangestanizadeh - Professional Portfolio

A modern, responsive portfolio website showcasing expertise in robotics, embedded systems, and machine learning.

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling, hover effects, and dynamic content
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript for performance

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### Personal Information
Update the following sections in `index.html`:

1. **Hero Section** (lines 15-25):
   - Name and title
   - Description
   - Contact information

2. **About Section** (lines 60-80):
   - Personal description
   - Skills and expertise

3. **Experience Section** (lines 85-150):
   - Work history
   - Research positions
   - Key achievements

4. **Projects Section** (lines 155-220):
   - Featured projects
   - Technologies used
   - Project descriptions

5. **Publications Section** (lines 225-260):
   - Research papers
   - Patents
   - Links to publications

6. **Contact Section** (lines 265-290):
   - Contact details
   - Social media links

### Styling Customization

#### Colors
The portfolio uses a blue color scheme. To change colors, update these CSS variables in `style.css`:

```css
/* Primary Colors */
--primary-color: #2563eb;
--secondary-color: #3b82f6;
--text-dark: #1e293b;
--text-light: #64748b;
--background-light: #f8fafc;
```

#### Fonts
The portfolio uses Inter font. To change fonts, update the Google Fonts link in `index.html` and the font-family in `style.css`.

### Adding New Sections

1. **Create HTML Structure**:
   ```html
   <section id="new-section" class="new-section">
       <div class="container">
           <h2 class="section-title">New Section</h2>
           <!-- Your content here -->
       </div>
   </section>
   ```

2. **Add CSS Styles**:
   ```css
   .new-section {
       padding: 100px 0;
       background: white; /* or #f8fafc for alternating sections */
   }
   ```

3. **Update Navigation**:
   Add a new navigation link in the navbar.

## 🚀 Deployment

### GitHub Pages (Recommended)

1. **Create a GitHub Repository**:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Your portfolio will be available at `https://yourusername.github.io/portfolio`

### Netlify

1. **Drag and Drop**:
   - Go to [netlify.com](https://netlify.com)
   - Drag your portfolio folder to the deploy area
   - Get a custom URL instantly

2. **Custom Domain**:
   - Add your custom domain in Netlify settings
   - Update DNS records as instructed

### Vercel

1. **Install Vercel CLI**:
   ```bash
   npm i -g vercel
   ```

2. **Deploy**:
   ```bash
   vercel
   ```

## 📱 Mobile Optimization

The portfolio is fully responsive and includes:

- Mobile-first design approach
- Touch-friendly navigation
- Optimized images and animations
- Fast loading on mobile networks

## 🔧 Performance Optimization

### Images
- Use WebP format when possible
- Optimize images for web (compress)
- Consider lazy loading for large images

### CSS/JS
- Minify CSS and JavaScript for production
- Use CDN for external libraries
- Enable gzip compression on your server

## 🎯 SEO Optimization

The portfolio includes:

- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## 📧 Contact Form Integration

To add a contact form:

1. **Use a service like Formspree**:
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
       <input type="text" name="name" placeholder="Your Name" required>
       <input type="email" name="email" placeholder="Your Email" required>
       <textarea name="message" placeholder="Your Message" required></textarea>
       <button type="submit">Send Message</button>
   </form>
   ```

2. **Or integrate with your own backend**:
   - Create a server endpoint
   - Handle form submission
   - Send email notifications

## 🔄 Updates and Maintenance

### Regular Updates
- Keep project information current
- Add new publications and projects
- Update skills and experience
- Refresh design periodically

### Version Control
- Use Git for version control
- Create branches for major updates
- Tag releases for important changes

## 📞 Support

For questions or customization help:
- Email: tangestanihamed@gmail.com
- LinkedIn: [Hamed Tangestanizadeh](https://www.linkedin.com/in/hamed-tangestanizadeh-7590a7182/)

## 📄 License

This portfolio template is open source and available under the MIT License.

---

**Built with ❤️ for showcasing robotics and embedded systems expertise** 