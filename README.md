# M3LEM Digital Agency Template

A modern, responsive digital agency website template with Arabic and English support, featuring performance optimizations and a clean, scalable architecture.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with seamless adaptation across all devices
- **Bilingual Support**: Arabic and English language support with RTL layout
- **Performance Optimized**: Minified CSS/JS, lazy loading, browser caching, and Gzip compression
- **Modern UI/UX**: Clean, professional design with smooth animations
- **SEO Friendly**: Optimized meta tags and semantic HTML structure
- **Cross-browser Compatible**: Works across all modern browsers

## 📁 Project Structure

```
M3LEM/
├── src/                    # Source files
│   ├── css/               # Source CSS files
│   │   └── styles.css     # Main stylesheet
│   └── js/                # Source JavaScript files
│       └── script.js      # Main JavaScript file
├── dist/                  # Production/build files
│   ├── css/               # Minified CSS files
│   │   └── styles.min.css # Minified stylesheet
│   ├── js/                # Minified JavaScript files
│   │   └── script.min.js  # Minified JavaScript
│   └── .htaccess          # Server configuration
├── assets/                # Static assets
│   ├── icons/             # Icons and logos
│   │   ├── favicon.svg    # Site favicon
│   │   └── M3LEM.png      # Company logo
│   └── images/            # Image assets
│       ├── landing/       # Landing page images
│       └── websites/      # Website portfolio images
├── docs/                  # Documentation
│   └── PERFORMANCE.md     # Performance optimization guide
├── index.html             # Main HTML file
├── package.json           # Project configuration
└── README.md              # This file
```

## 🛠️ Installation & Setup

1. **Clone or download** the project files
2. **Install dependencies** (optional, for build tools):
   ```bash
   npm install
   ```

## 🚀 Usage

### Development

1. **Start development server**:
   ```bash
   npm run dev
   ```
   This will start a local server at `http://localhost:8080`

2. **Make changes** to source files in the `src/` directory
3. **Build for production** when ready:
   ```bash
   npm run build
   ```

### Manual Setup

If you prefer not to use npm:

1. Open `index.html` in your browser
2. For local development, use any local server (Python, PHP, etc.)
3. For production, upload all files to your web server

## 📝 Customization

### Styling
- Edit `src/css/styles.css` for styling changes
- Run `npm run minify-css` to update the minified version

### JavaScript
- Edit `src/js/script.js` for functionality changes
- Run `npm run minify-js` to update the minified version

### Content
- Edit `index.html` to update content, text, and structure
- Replace images in `assets/images/` with your own
- Update `assets/icons/M3LEM.png` with your logo

### Configuration
- Modify `dist/.htaccess` for server-specific optimizations
- Update `package.json` with your project details

## 🎯 Performance Features

- **File Minification**: CSS and JavaScript files are minified for faster loading
- **Image Optimization**: Lazy loading and async decoding for images
- **Browser Caching**: Configured via .htaccess for optimal caching
- **Gzip Compression**: Enabled for all text-based files
- **Critical Resource Loading**: Preload hints for faster initial rendering

For detailed performance information, see [docs/PERFORMANCE.md](docs/PERFORMANCE.md)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 📱 Responsive Breakpoints

- Mobile: 320px - 768px
- Tablet: 768px - 1024px
- Desktop: 1024px+

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For support and questions, please contact M3LEM Digital Agency.

---

**M3LEM Digital Agency** - Creating digital experiences that matter.