# frontenddev_project
GenFashy is a responsive e-commerce website showcasing contemporary clothing and accessories. It features interactive product cards, a sticky navigation menu, wishlist, cart, newsletter signup, and a sleek, modern design with vibrant accents, optimized for mobile and desktop browsing.
# GenFashy — Contemporary Clothing

A modern, responsive e-commerce website for contemporary clothing featuring a dark theme with vibrant gradients and smooth animations.

![GenFashy Preview](https://images.unsplash.com/photo-1512436991641-6745cdb1723f?q=80&w=1200&auto=format&fit=crop)

## Features

- **Modern UI/UX**: Dark theme with vibrant violet and cyan gradients
- **Fully Responsive**: Mobile-first design that works on all devices
- **Interactive Elements**: Smooth animations, hover effects, and micro-interactions
- **Shopping Features**:
  - Product catalog with filtering
  - Shopping cart functionality
  - Wishlist system
  - Newsletter subscription
- **Accessibility**: ARIA labels and semantic HTML
- **Performance**: Optimized images and minimal dependencies

## Tech Stack

- Pure HTML5
- CSS3 (Custom properties, Grid, Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)
- Unsplash for product images

## Quick Start

### Option 1: Direct Deployment

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/voguevista.git
   cd voguevista
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   open index.html
   # Or use a local server
   python -m http.server 8000
   # Or with Node.js
   npx serve
   ```

### Option 2: Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/voguevista/`

### Option 3: Deploy to Netlify

1. Connect your GitHub repository to Netlify
2. Build command: (leave empty)
3. Publish directory: `/`
4. Deploy!

### Option 4: Deploy to Vercel

1. Import your GitHub repository to Vercel
2. Framework preset: Other
3. Deploy!

## Project Structure

```
voguevista/
├── index.html          # Main HTML file with embedded CSS & JS
├── README.md           # This file
├── LICENSE             # MIT License
├── .gitignore          # Git ignore file
└── images/             # (Optional) Local images directory
    └── screenshot.png  # Project screenshot
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Colors

Edit CSS variables in the `:root` selector:

```css
:root {
  --bg: #0b0b0c;           /* Background */
  --card: #111214;         /* Card background */
  --muted: #8a8f98;        /* Muted text */
  --text: #f2f3f5;         /* Primary text */
  --accent: #8b5cf6;       /* Violet accent */
  --accent-2: #22d3ee;     /* Cyan accent */
  --success: #10b981;      /* Success color */
  --danger: #ef4444;       /* Danger color */
}
```

### Content

- Update product information in the HTML
- Replace Unsplash image URLs with your own
- Modify navigation links and footer content

## Performance Optimization

Current optimizations:
- Preconnect to Google Fonts
- Optimized Unsplash images with auto-format
- Minimal JavaScript (< 1KB)
- Single file architecture (no HTTP requests for CSS/JS)

## Future Enhancements

- [ ] Backend integration for products
- [ ] Shopping cart persistence
- [ ] User authentication
- [ ] Product search functionality
- [ ] Checkout process
- [ ] Order management
- [ ] Product filtering and sorting
- [ ] Reviews and ratings

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Images from [Unsplash](https://unsplash.com)
- Fonts from [Google Fonts](https://fonts.google.com)
- Design inspiration from contemporary e-commerce sites

## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/voguevista](https://github.com/yourusername/voguevista)

---

**Made with ❤️ for modern web experiences**
