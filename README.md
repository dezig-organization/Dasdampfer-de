# Efajki Jednorazówki - Single Page Website

## 📋 Project Overview
Pixel-perfect single-page responsive website for **efajki-jednorazowki.pl** - Polish e-cigarette/disposable vape shop.

Design inspiration: Premium streaming service aesthetic with dark theme, smooth animations, and modern UI.

## 🎯 Features
✅ **Single Page Design** - All content in one HTML file  
✅ **Pixel-Perfect Layout** - Exact reproduction of design specifications  
✅ **Fully Responsive** - Desktop (1920px+), Tablet (1024px), Mobile (768px), Small Mobile (480px), Extra Small (320px+)  
✅ **Mobile Hamburger Menu** - Smooth slide-in animation with CSS transitions  
✅ **Hero Slider** - Auto-playing carousel with manual controls  
✅ **Product Grid** - 10 product cards with hover effects and interactions  
✅ **Pricing Plans** - 3 tiers with featured highlighting  
✅ **SEO Optimized** - Polish keywords, meta tags, semantic HTML  
✅ **No External Libraries** - Pure HTML5, CSS3, and Vanilla JavaScript  

## 📁 Project Structure
```
efajki-jednorazowki.pl/
├── index.html          # Main HTML file with all content
├── style.css           # All styling (dark theme, responsive, animations)
├── script.js           # Interactive features (menu, slider, etc.)
├── images/             # Directory for product images (empty - add your own)
└── README.md           # This file
```

## 🖼️ Image Placeholders
The website includes placeholders for the following images. Replace them with your actual product images:

### Hero Section:
- `images/hero-product.png` (500x500px) - Main hero product image
- `images/hero-product-2.png` (500x500px) - Second slide
- `images/hero-product-3.png` (500x500px) - Third slide
- `images/thumb-1.png` (100x140px) - Thumbnail 1
- `images/thumb-2.png` (100x140px) - Thumbnail 2
- `images/thumb-3.png` (100x140px) - Thumbnail 3

### Navigation:
- `images/user-avatar.png` (32x32px) - User profile picture

### Product Grid (Nowości Section):
- `images/product-1.png` (600x900px recommended)
- `images/product-2.png` (600x900px recommended)
- `images/product-3.png` (600x900px recommended)
- `images/product-4.png` (600x900px recommended)
- `images/product-5.png` (600x900px recommended)
- `images/product-6.png` (600x900px recommended)
- `images/product-7.png` (600x900px recommended)
- `images/product-8.png` (600x900px recommended)
- `images/product-9.png` (600x900px recommended)
- `images/product-10.png` (600x900px recommended)

## 🎨 Polish Keywords Integration
The website includes all your keywords naturally throughout:
- efajki
- najlepsze
- najtańsze
- Darmowa dostawa
- Wyprzedaż
- Nowości
- Najlepsze ceny
- Top kolekcje
- Promocje
- Tylko u nas
- Popularne
- buchów
- jednorazówka
- jednorazówki
- e papieros
- najlepsze jednorazówki
- e papierosy jednorazowe
- e papierosy sklep

## 🚀 How to Use

### 1. Add Your Images
Simply copy your product images into the `images/` folder with the exact names listed above.

### 2. Open the Website
- **Local**: Double-click `index.html` to open in your browser
- **Server**: Upload all files to your web hosting

### 3. Customize Content (Optional)
Edit `index.html` to update:
- Product titles and descriptions
- Prices and details
- Links and URLs
- Additional text content

## 📱 Responsive Breakpoints
- **Desktop**: 1920px+ (full experience)
- **Laptop**: 1024px - 1919px (optimized layout)
- **Tablet**: 768px - 1023px (adjusted grid)
- **Mobile**: 481px - 767px (mobile menu, stacked layout)
- **Small Mobile**: 320px - 480px (single column)

## 🎯 Mobile Menu Behavior
- **Desktop**: Horizontal navigation in header
- **Mobile (768px and below)**: 
  - Hamburger icon appears (top left)
  - Menu slides in from left with smooth animation
  - Backdrop blur effect
  - Click outside or press ESC to close
  - Body scroll locked when menu open

## ⚡ Interactive Features

### Hero Slider
- **Auto-play**: Changes every 5 seconds
- **Manual control**: Click dots or thumbnails
- **Keyboard**: Arrow keys to navigate
- **Pause**: Hover over hero to pause autoplay

### Product Cards
- **Hover effect**: Lift animation with shadow
- **Favorite button**: Click heart icon to toggle
- **CTA button**: Click to simulate purchase action

### Filters
- Click category buttons to filter products (visual feedback)
- Smooth fade animation when switching

### Pagination
- Navigate between product pages
- Active page highlighted
- Smooth scroll to top on page change

## 🎨 Design Colors
```css
Primary Red:     #E50914
Background:      #0A0A0A
Card Background: #1A1A1A
Text Primary:    #FFFFFF
Text Secondary:  #B3B3B3
Accent Gold:     #FFB800
```

## 🔧 Technical Stack
- **HTML5**: Semantic markup, SEO-friendly structure
- **CSS3**: Flexbox, Grid, Custom Properties, Animations
- **JavaScript ES6+**: Modern vanilla JS, no frameworks
- **Google Fonts**: Inter font family

## ✅ Browser Compatibility
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 SEO Features
✓ Descriptive title tag with keywords  
✓ Meta description optimized for Polish market  
✓ Semantic HTML5 structure  
✓ Alt text for all images (using keywords)  
✓ Proper heading hierarchy (H1, H2, H3)  
✓ Mobile-friendly (responsive design)  

## 🎯 Performance
- **Fast loading**: No external libraries
- **Optimized**: Debounced scroll/resize events
- **Smooth**: 60fps animations with CSS transforms
- **Lazy loading**: Error handling for images

## 📝 Customization Tips

### Change Colors
Edit CSS variables in `style.css` (lines 11-27):
```css
:root {
    --color-primary: #E50914;  /* Your brand color */
    --color-bg-main: #0A0A0A;  /* Background */
    /* etc. */
}
```

### Add More Products
Copy a `.product-card` block in `index.html` and update:
- Image src
- Alt text
- Product title
- Rating and count
- CTA button text/link

### Update Hero Content
Edit `.hero-left` section in `index.html`:
- Change badge text
- Update title
- Modify description
- Change button labels

## 🐛 Troubleshooting

**Images not showing?**
- Verify images are in the `images/` folder
- Check file names match exactly (case-sensitive)
- Ensure image formats are supported (.png, .jpg, .webp)

**Menu not working?**
- Check browser console for errors
- Ensure `script.js` is loaded
- Clear browser cache

**Layout broken on mobile?**
- Ensure viewport meta tag is present
- Check CSS media queries are working
- Test in mobile browser or DevTools

## 📄 License
This is a custom-built website for efajki-jednorazowki.pl.

## 🎉 Credits
- Design: Based on premium streaming service aesthetic
- Development: Custom HTML/CSS/JS implementation
- Fonts: Google Fonts (Inter)
- Icons: Custom SVG icons

---

**Ready to launch!** 🚀

Just add your product images to the `images/` folder and you're good to go!
