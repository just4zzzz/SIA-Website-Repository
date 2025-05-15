# Scent Haven - Premium Fragrance Store

A modern, responsive e-commerce website for luxury fragrances. This website showcases various premium perfume brands and provides a seamless shopping experience for fragrance enthusiasts.

## Features

- Responsive design that works on all devices
- Modern and elegant user interface
- Featured brands showcase
- New arrivals section
- Newsletter subscription
- Shopping cart functionality
- Search functionality
- Smooth scrolling navigation
- Interactive product cards
- Social media integration

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome for icons
- Google Fonts (Playfair Display, Poppins)

## Project Structure

```
.
├── index.html
├── styles/
│   └── main.css
├── js/
│   └── main.js
├── images/
│   ├── hero-bg.jpg
│   ├── chanel.jpg
│   ├── dior.jpg
│   ├── tom-ford.jpg
│   ├── jo-malone.jpg
│   ├── product1.jpg
│   ├── product2.jpg
│   └── product3.jpg
└── README.md
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Navigate to the project directory:
   ```bash
   cd scent-haven
   ```

3. Open `index.html` in your web browser to view the website.

## Image Requirements

Before running the website, make sure to add the following images to the `images` directory:

- `hero-bg.jpg` - Hero section background image
- `chanel.jpg` - Chanel brand logo/image
- `dior.jpg` - Dior brand logo/image
- `tom-ford.jpg` - Tom Ford brand logo/image
- `jo-malone.jpg` - Jo Malone brand logo/image
- `product1.jpg` - Chanel N°5 product image
- `product2.jpg` - Miss Dior product image
- `product3.jpg` - Black Orchid product image

## Customization

### Adding New Products

To add new products, add the following HTML structure in the product grid section of `index.html`:

```html
<div class="product-card">
    <img src="images/your-product-image.jpg" alt="Product Name">
    <h3>Product Name</h3>
    <p>Product Description</p>
    <span class="price">$XX.XX</span>
    <button class="add-to-cart">Add to Cart</button>
</div>
```

### Modifying Styles

The main styles are located in `styles/main.css`. You can modify:

- Color scheme
- Typography
- Layout
- Animations
- Responsive breakpoints

## Browser Support

The website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or support, please contact:
- Email: info@scenthaven.com
- Website: www.scenthaven.com

## Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- All featured brands for inspiration
