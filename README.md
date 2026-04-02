# Modern Portfolio Website

A clean, modern, and responsive portfolio website built with HTML, CSS, and JavaScript.

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Home/About page
├── projects.html       # Projects showcase page
├── skills.html         # Skills and expertise page
├── contact.html        # Contact form page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🚀 Features

- **4 Separate Pages**: About, Projects, Skills, and Contact
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Design**: Clean UI with gradient accents and smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and animated transitions
- **Contact Form**: Functional form with validation (frontend only)
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Scroll Animations**: Elements animate into view as you scroll
- **Social Links**: Easy integration with GitHub, LinkedIn, and Twitter

## 🎨 Customization Guide

### 1. Personal Information

**In all HTML files**, update:
- `YourName` in the logo
- `Your Name` in titles and headings
- Email, phone, and location in `contact.html`

### 2. Social Media Links

Replace placeholder URLs in all HTML files:
```html
<a href="https://github.com/YOURUSERNAME" ...>
<a href="https://linkedin.com/in/YOURUSERNAME" ...>
<a href="https://twitter.com/YOURUSERNAME" ...>
```

### 3. Profile Image

Replace the SVG placeholder in `index.html` with your image:
```html
<div class="image-placeholder">
    <img src="your-photo.jpg" alt="Your Name" style="width: 100%; border-radius: 50%;">
</div>
```

### 4. Project Images

In `projects.html`, replace the gradient backgrounds with actual project images:
```html
<div class="project-image">
    <img src="project-image.jpg" alt="Project Name" style="width: 100%; height: 100%; object-fit: cover;">
    <div class="project-overlay">
        <a href="project-url" class="project-link" target="_blank">View Project →</a>
    </div>
</div>
```

### 5. Color Scheme

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;      /* Change to your brand color */
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
}
```

### 6. Content

Update all text content in the HTML files:
- About section in `index.html`
- Project descriptions in `projects.html`
- Skills and tools in `skills.html`
- Contact information in `contact.html`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript (ES6+)
- No frameworks or libraries required!

## 📦 Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select the main branch as source
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Other Hosting Options

- Netlify: Drag and drop the folder
- Vercel: Import from GitHub
- GitHub Pages: Push to gh-pages branch

## ✨ Tips for Best Results

1. **Use High-Quality Images**: For projects and profile picture
2. **Keep Content Concise**: Clear and focused descriptions
3. **Update Regularly**: Keep projects and skills current
4. **Test Responsiveness**: Check on multiple devices
5. **Optimize Images**: Compress images for faster loading
6. **Add Analytics**: Consider adding Google Analytics
7. **SEO Optimization**: Update meta descriptions and titles

## 🔧 Optional Enhancements

### Add a Blog Section
Create a `blog.html` page following the same structure

### Integrate Contact Form Backend
Use services like:
- Formspree
- EmailJS
- Netlify Forms
- Custom backend API

### Add Dark Mode
Implement theme toggle in `script.js`

### Include Actual Resume
Add a downloadable PDF resume link

## 📄 License

Free to use for personal and commercial projects. No attribution required.

## 🤝 Support

If you need help customizing this portfolio:
1. Check the code comments
2. Review this README
3. Search for HTML/CSS tutorials online

---

**Made with ❤️ for aspiring developers**

Good luck with your portfolio! 🚀
