# Growth App Landing Page

A modern, responsive landing page for a startup growth tool built with HTML5, CSS3, and Font Awesome icons.

## 🚀 Overview

This landing page showcases a fictional startup growth application with a clean, professional design. It features a hero section, video preview, testimonials, and contact form to drive user engagement and conversions.

## ✨ Features

- **Responsive Design**: Mobile-first approach with breakpoints for tablets and desktop
- **Modern CSS**: Uses CSS Grid, Flexbox, and custom CSS variables
- **Interactive Elements**: Hover effects, smooth transitions, and call-to-action buttons
- **Font Integration**: Google Fonts (Poppins) and Font Awesome icons
- **Cross-browser Compatible**: Works on all modern browsers

## 🏗️ Structure

```
Landing-PAGE/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Main stylesheet
├── images/
│   ├── logo.png       # Company logo
│   ├── hero-bg.png    # Hero background image
│   ├── video-preview.png # Video thumbnail
│   └── favicon.ico    # Site favicon
└── js/
    └── main.js        # JavaScript functionality
```

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#4891ff`
- **Light Gray**: `#f4f4f6`
- **Dark**: `#111`
- **White**: `#fff`
- **Black**: `#000`

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Font Weights**: 300, 400, 600, 700
- **Responsive Text Sizes**: `.text-xxl` to `.text-sm`

### Components
- Navigation bar with logo and menu
- Hero section with CTA buttons
- Video preview section
- Testimonials cards
- Contact form
- Data table
- Back-to-top functionality

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Text editor (VS Code, Sublime Text, etc.)
- Local server (optional, for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/chrisarpong/Landing-PAGE.git
   cd Landing-PAGE
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

3. **For development with live server**
   ```bash
   # If using VS Code with Live Server extension
   # Right-click on index.html → "Open with Live Server"
   ```

## 📱 Responsive Breakpoints

- **Mobile**: `< 768px`
- **Tablet**: `768px - 1024px`
- **Desktop**: `> 1024px`

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #4891ff;    /* Your brand color */
    --light-color: #f4f4f6;     /* Light background */
    --dark-color: #111;         /* Dark text/backgrounds */
}
```

### Adding Content
1. **Hero Section**: Edit the `<section class="hero">` in `index.html`
2. **Testimonials**: Add more `.card` elements in the testimonials section
3. **Navigation**: Modify the `.main-menu ul` structure

### Styling
- **Buttons**: Use `.btn`, `.btn-primary`, `.btn-dark` classes
- **Text Sizes**: Apply `.text-xxl`, `.text-xl`, `.text-lg`, etc.
- **Backgrounds**: Use `.bg-primary`, `.bg-light`, `.bg-dark`

## 🔧 Known Issues & Improvements Needed

### Current Issues
- [ ] Missing hero background image (`hero-bg.png`)
- [ ] Incomplete form validation
- [ ] Mixed content (test elements alongside landing page content)
- [ ] No JavaScript functionality implemented

### Recommended Improvements
- [ ] Add form validation and submission handling
- [ ] Implement smooth scrolling navigation
- [ ] Add loading animations
- [ ] Optimize images for web
- [ ] Add meta tags for SEO
- [ ] Remove test/placeholder content
- [ ] Add proper error handling

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 📄 File Descriptions

### HTML (`index.html`)
- Semantic HTML5 structure
- External resource links (fonts, icons)
- Responsive viewport meta tag
- Structured content sections

### CSS (`css/style.css`)
- CSS reset and normalization
- CSS custom properties (variables)
- Flexbox and Grid layouts
- Responsive media queries
- Utility classes for reusability

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to repository Settings
3. Navigate to Pages section
4. Select source branch (usually `main`)
5. Site will be available at `https://username.github.io/Landing-PAGE`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: `# No build command needed`
3. Set publish directory: `./`
4. Deploy automatically on git push

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Christian Sarpong**
- GitHub: [@chrisarpong](https://github.com/chrisarpong)

## 🙏 Acknowledgments

- [Google Fonts](https://fonts.google.com/) for Poppins font family
- [Font Awesome](https://fontawesome.com/) for icons
- [CSS-Tricks](https://css-tricks.com/) for CSS techniques and best practices

---

*Built with ❤️ for learning and showcasing web development skills*
