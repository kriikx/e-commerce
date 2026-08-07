# 🛒 E-Commerce Frontend

A fully responsive Amazon-inspired e-commerce frontend built with **HTML**, **CSS**, and **JavaScript**.

## Features

✨ **Modern Navigation Bar** - Sticky navbar with logo, search bar, and account options  
🎠 **Hero Image Carousel** - Auto-rotating banner with manual navigation controls  
🛍️ **Product Showcase Cards** - Dynamic product grid with ratings and pricing  
🛒 **Dynamic Cart Counter** - Real-time cart item tracking  
⭐ **Ratings System** - Star ratings and review counts for products  
📱 **Fully Responsive** - Optimized for all screen sizes  
🔗 **Amazon-Style Footer** - Complete footer with multiple link sections  

## Project Structure

```
e-commerce/
├── index.html           # Main HTML file
├── style.css            # Stylesheet
├── images/              # Organized image assets
│   ├── hero/            # Carousel images
│   ├── products/        # Product card images
│   └── logo/            # Logo assets
├── .gitignore           # Git ignore rules
└── README.md            # This file
```

## Image Organization

All images have been organized into subdirectories for better maintainability:

- **`images/hero/`** - Carousel banner images
  - nuts.jpg
  - electro.jpg
  - hero_img_.jpg

- **`images/products/`** - Product card images
  - Fuji_Gaming.jpg
  - box4_image.jpg through box16.jpg
  - box8_image.jpg, box5_image.jpg, box7_image.jpg, box9.jpg
  - box10.webp, box11.webp

- **`images/logo/`** - Branding assets
  - amazon_logo.png

## How to Use

1. **Move images to their respective directories** according to the structure above
2. All HTML and CSS files are already configured with correct paths
3. Open `index.html` in your browser to view the e-commerce site

## JavaScript Features

### Cart Counter
Click the "Add to Cart" button on any product to increment the cart counter. The button provides visual feedback and temporarily disables to prevent accidental double-clicks.

### Hero Carousel
- **Auto-rotate** every 4 seconds
- **Manual navigation** using left/right arrow buttons
- **Dot indicators** to jump to specific slides

## Browser Compatibility

✅ Chrome  
✅ Firefox  
✅ Safari  
✅ Edge  
✅ Mobile browsers  

## Development Tips

- Update image URLs by modifying the `style="background-image: url('images/...')"` attributes in HTML
- Customize colors in `style.css` for brand alignment
- Extend functionality by adding JavaScript event listeners

## Future Enhancements

- Add product filtering and sorting
- Implement shopping cart checkout flow
- Add product detail pages
- Integrate with backend API
- Add user authentication

## License

This project is open source and available under the MIT License.
