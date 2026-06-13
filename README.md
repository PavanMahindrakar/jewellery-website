# S.S Bondre Jewellers - Website

A modern, responsive e-commerce website for S.S Bondre Jewellers, showcasing fine jewellery collections with an elegant user interface and seamless shopping experience.

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📋 Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Browser Support](#browser-support)
- [Features in Detail](#features-in-detail)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly on mobile, tablet, and desktop devices
- **Dark/Light Mode Toggle**: Automatic theme switching with localStorage persistence
- **Product Showcase**: Elegant display of jewellery products with category organization
- **Image Sliders**: Multiple carousel implementations for featured products and galleries
- **Smooth Animations**: CSS animations and transitions for enhanced user experience
- **Modern UI Components**: Bootstrap-based responsive components
- **Professional Navigation**: Clean and intuitive navigation system
- **Contact Information**: Easy access to helpline and inquiry channels
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Performance Optimized**: Lightweight and fast-loading assets

---

## 🛠️ Technology Stack

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with responsive design
- **JavaScript (ES6+)**: Interactive functionality
- **jQuery**: DOM manipulation and event handling

### UI Frameworks & Libraries
- **Bootstrap 5.0**: Responsive grid system and components
- **Owl Carousel 2.3**: Image slider functionality
- **Slick Carousel 1.8**: Additional carousel features
- **Animate.css 4.1**: CSS-based animations
- **Ionicons 2.0**: Icon library
- **WOW.js**: Scroll animation effects

### Icons & Fonts
- **Ionicons**: Modern icon set
- **Poppins & Baloo 2**: Google Fonts for typography

---

## 📁 Project Structure

```
Jewellery-website/
├── index.html              # Main HTML file
├── main.js                 # Core JavaScript functionality
├── style.css               # Custom CSS styling
├── favicon.ico             # Browser tab icon
├── images/                 # Image assets directory
│   ├── banner/             # Banner images
│   ├── blog/               # Blog-related images
│   ├── icon/               # Icon images
│   ├── instagram/          # Instagram integration images
│   ├── logo/               # Logo and branding assets
│   ├── nav-product/        # Navigation product images
│   ├── product/            # Product showcase images
│   └── slider/             # Slider/carousel images
├── .git/                   # Git version control
└── README.md               # Project documentation
```

---

## 🚀 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: Local web server (for optimal performance)
- Optional: Git (for cloning the repository)

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Jewellery-website.git
   cd Jewellery-website
   ```

2. **Open in Browser**
   - Double-click `index.html` to open directly in your default browser
   - OR use a local web server:
   
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (install http-server first)
   npx http-server
   ```

3. **Access the Website**
   - Direct: Open `index.html` in your browser
   - Local Server: Navigate to `http://localhost:8000`

---

## 💻 Usage

### Basic Navigation
- **Logo**: Click to return to homepage
- **Navigation Menu**: Browse different jewellery categories
- **Theme Toggle**: Click the sun/moon icon to switch between dark and light modes
- **Product Carousel**: Scroll through featured products
- **Contact Information**: Tap the helpline number to initiate a call

### Theme Persistence
- Your preferred theme (dark/light) is saved automatically in the browser's localStorage
- Theme preference persists across browser sessions

### Image Assets
- Replace images in the respective folders to update product displays
- Maintain proper image dimensions for optimal display
- Use optimized formats (WebP, JPEG, PNG) for better performance

---

## 🌐 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | Latest 2 | ✅ Full Support |
| Firefox | Latest 2 | ✅ Full Support |
| Safari | Latest 2 | ✅ Full Support |
| Edge | Latest 2 | ✅ Full Support |
| Opera | Latest 2 | ✅ Full Support |
| IE 11 | Any | ⚠️ Limited Support |

---

## 🎯 Features in Detail

### Dark/Light Mode Theme Toggle
The website includes an intelligent theme system that:
- Automatically detects user preference
- Persists choice in browser storage
- Applies comprehensive color scheme changes
- Enhances readability and user comfort

### Responsive Carousel System
Multiple carousel implementations provide:
- Featured product showcases
- Image galleries
- Customer testimonials
- Smooth transitions and navigation

### Performance Optimizations
- Minified CSS and JavaScript assets
- Lazy loading support for images
- Efficient DOM manipulation
- Optimized animation performance

---

## ⚙️ Configuration

### Updating Contact Information
Edit the phone number in `index.html`:
```html
<a href="tel: 1234567894">1234567894</a>
```

### Customizing Colors & Fonts
Modify `style.css`:
```css
/* Update primary color */
--primary-color: #a8741a;

/* Update font family */
font-family: 'Poppins', sans-serif;
```

### Adding New Products
1. Add product images to appropriate folders in `images/`
2. Update HTML structure in `index.html` with new product cards
3. Add corresponding styles in `style.css` if needed
4. Update JavaScript functionality in `main.js` if necessary

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Maintain responsive design across all screen sizes
- Follow existing code styling and conventions
- Test changes across multiple browsers
- Optimize images before committing
- Update documentation for significant changes

---

## 📞 Contact

**S.S Bondre Jewellers**

- **Helpline/Inquiry**: [1234567894](tel:1234567894)
- **Website**: [Your Website URL]
- **Social Media**: [Instagram Link]
- **Email**: [Your Email]

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📝 Notes

- This is a static website implementation. For e-commerce functionality (checkout, payments), backend integration is required.
- External CDN links are used for libraries. Ensure internet connectivity or download libraries locally for offline use.
- Image optimization and lazy loading can be implemented for better performance with large image catalogs.
- Consider implementing progressive enhancement for better SEO and accessibility.

---

## 🙏 Acknowledgments

- Bootstrap team for the responsive framework
- Ionicons for the beautiful icon library
- Developers of Owl Carousel and Slick Carousel
- WOW.js and Animate.css creators for smooth animations

---

**Last Updated**: June 2026  
**Version**: 1.0.0

