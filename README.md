# Masum Billal - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my work as an AI/ML Engineer and Researcher. Built with HTML5, CSS3, and JavaScript, featuring a clean design and smooth animations.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Research Showcase**: Highlighted publications and research work
- **Project Portfolio**: Detailed showcase of AI/ML projects
- **Skills Section**: Comprehensive technical skills display
- **Dark/Light Theme**: Optional theme toggle functionality
- **Performance Optimized**: Fast loading and smooth scrolling

## 🚀 Live Demo

Visit the live website: [Your GitHub Pages URL]

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── _config.yml         # Jekyll configuration (for GitHub Pages)
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling, animations, and responsive design
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons and visual elements
- **Google Fonts**: Typography (Inter font family)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🎨 Design Features

### Color Scheme
- **Primary**: #2563eb (Blue)
- **Secondary**: #7c3aed (Purple)
- **Success**: #10b981 (Green)
- **Background**: #fafafa (Light Gray)
- **Text**: #1f2937 (Dark Gray)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Headings**: 700 weight
- **Body Text**: 400-500 weight
- **Code**: Monospace

### Animations
- Smooth scroll navigation
- Fade-in animations on scroll
- Hover effects on interactive elements
- Typing animation for hero title
- Parallax effects
- Card tilt effects

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- GitHub account (for hosting)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Customize the content**
   - Edit `index.html` to update personal information
   - Modify `styles.css` to change colors and styling
   - Update `script.js` for custom functionality

3. **Deploy to GitHub Pages**
   - Push your code to GitHub
   - Go to repository Settings > Pages
   - Select source branch (usually `main`)
   - Your site will be available at `https://yourusername.github.io/repository-name`

### Local Development

1. **Simple HTTP Server**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js
   npx http-server
   ```

2. **Open in browser**
   ```
   http://localhost:8000
   ```

## 📝 Customization Guide

### Updating Personal Information

1. **Hero Section** (in `index.html`)
   ```html
   <h1 class="hero-title">
       <span class="greeting">👋 Hi, I'm</span>
       <span class="name">Your Name</span>
   </h1>
   ```

2. **About Section**
   - Update the description in the about section
   - Modify skills in the skills grid

3. **Projects Section**
   - Add/remove project cards
   - Update project descriptions and technologies

4. **Research Section**
   - Add new publications
   - Update research highlights

5. **Contact Information**
   - Update email, LinkedIn, and location
   - Modify contact form if needed

### Styling Customization

1. **Colors** (in `styles.css`)
   ```css
   :root {
       --primary-color: #2563eb;
       --secondary-color: #7c3aed;
       --success-color: #10b981;
   }
   ```

2. **Fonts**
   - Change Google Fonts import
   - Update font-family declarations

3. **Layout**
   - Modify grid layouts
   - Adjust spacing and padding
   - Change breakpoints for responsiveness

### Adding New Sections

1. **HTML Structure**
   ```html
   <section id="new-section" class="new-section">
       <div class="container">
           <h2 class="section-title">New Section</h2>
           <!-- Content here -->
       </div>
   </section>
   ```

2. **CSS Styling**
   ```css
   .new-section {
       padding: 5rem 0;
       background: #f8fafc;
   }
   ```

3. **Navigation Update**
   - Add new nav link
   - Update JavaScript for smooth scrolling

## 🔧 Advanced Features

### Contact Form Integration

The contact form is currently set up for demonstration. To make it functional:

1. **Backend Integration**
   - Use services like Formspree, Netlify Forms, or EmailJS
   - Or implement your own backend solution

2. **Formspree Example**
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
       <!-- form fields -->
   </form>
   ```

### Analytics Integration

Add Google Analytics or other tracking:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### SEO Optimization

1. **Meta Tags** (in `index.html` head)
   ```html
   <meta name="description" content="Your description">
   <meta name="keywords" content="your, keywords">
   <meta property="og:title" content="Your Title">
   <meta property="og:description" content="Your description">
   ```

2. **Structured Data**
   - Add JSON-LD schema markup
   - Include person, organization, and article schemas

## 📊 Performance Optimization

### Image Optimization
- Use WebP format when possible
- Implement lazy loading
- Compress images before upload

### Code Optimization
- Minify CSS and JavaScript for production
- Use CDN for external libraries
- Implement service worker for caching

### Loading Performance
- Optimize critical rendering path
- Use preload for important resources
- Implement progressive loading

## 🐛 Troubleshooting

### Common Issues

1. **GitHub Pages not updating**
   - Check if the repository is public
   - Verify the correct branch is selected
   - Wait a few minutes for changes to propagate

2. **Images not loading**
   - Check file paths and names
   - Ensure images are in the repository
   - Use relative paths for local images

3. **CSS not applying**
   - Check for syntax errors
   - Verify file paths
   - Clear browser cache

4. **JavaScript errors**
   - Check browser console for errors
   - Verify all dependencies are loaded
   - Test in different browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you have any questions or need help with customization:

- **Email**: billalmasum342@gmail.com
- **LinkedIn**: [linkedin.com/in/billalmasum342](https://linkedin.com/in/billalmasum342)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio websites
- Icons from Font Awesome
- Fonts from Google Fonts
- CSS animations and effects
- Responsive design patterns

---

**Made with ❤️ by Masum Billal**

*Last updated: January 2025*
