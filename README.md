# Mattias - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a full-stack developer.

## 🚀 Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading times and smooth scrolling
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessibility**: WCAG compliant with proper ARIA labels

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: Advanced styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **Font Awesome**: Icon library for consistent iconography
- **Google Fonts**: Inter font family for typography

### Design Features
- CSS Grid and Flexbox for layouts
- CSS Custom Properties (variables)
- Smooth scroll behavior
- Intersection Observer API for scroll animations
- Responsive breakpoints
- Modern CSS animations and transitions

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone <your-repo-url>
   cd Portfolio
   ```

2. **Open the project**
   - Option 1: Open `index.html` directly in your browser
   - Option 2: Use a local server for development:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website**
   - Direct file: Open `index.html` in your browser
   - Local server: Navigate to `http://localhost:8000`

## 🎨 Customization

### Personal Information
Update the following sections in `index.html`:

1. **Hero Section** (lines 45-60):
   ```html
   <h1 class="hero-title">
       Hi, I'm <span class="highlight">Your Name</span>
   </h1>
   <h2 class="hero-subtitle">Your Title</h2>
   ```

2. **About Section** (lines 80-95):
   ```html
   <p>Your personal description...</p>
   ```

3. **Contact Information** (lines 200-220):
   ```html
   <p>your.email@example.com</p>
   <p>+1 (555) 123-4567</p>
   <p>Your City, Country</p>
   ```

4. **Social Links** (lines 230-250):
   ```html
   <a href="https://github.com/yourusername" class="social-link">
   <a href="https://linkedin.com/in/yourusername" class="social-link">
   ```

### Projects
Update the projects section (lines 100-180) with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://yourproject.com" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### Skills
Modify the skills section (lines 185-250) to reflect your technologies:

```html
<div class="skill-item">
    <i class="fab fa-your-technology"></i>
    <span>Technology Name</span>
</div>
```

### Colors and Styling
Update the CSS custom properties in `styles.css` (lines 1-20) to match your brand:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #fbbf24;
    --text-color: #1f2937;
    --bg-color: #ffffff;
}
```

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🎯 Performance Features

- **Optimized Images**: Using Font Awesome icons instead of images for better performance
- **Debounced Scroll Events**: Improved scroll performance
- **CSS Animations**: Hardware-accelerated animations
- **Minimal Dependencies**: Only essential external libraries

## 🔧 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to:

- Open an issue on GitHub
- Contact me through the portfolio contact form
- Email me at your.email@example.com

## 🎉 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for the amazing icon library
- [Google Fonts](https://fonts.google.com/) for the Inter font family
- [Unsplash](https://unsplash.com/) for inspiration on modern web design

---

**Happy Coding! 🚀**

*Built with ❤️ and modern web technologies*
