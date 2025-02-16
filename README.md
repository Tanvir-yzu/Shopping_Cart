# China Marts - Shopping Cart Demo

A responsive e-commerce shopping cart demo built with HTML, JavaScript, and Bootstrap 5. This project demonstrates a modern shopping experience with product filtering, cart management, promo code functionality, and a checkout process.

![China Marts Demo](screenshot.png)

## Features

### Product Catalog
- Dynamic product loading from Fake Store API
- Category filtering
- Product cards with:
  - Product images
  - Titles and descriptions
  - Prices
  - Ratings with star display
  - Category badges
  - Add to cart buttons
- Responsive grid layout

### Shopping Cart
- Sliding cart sidebar
- Real-time cart management:
  - Add/remove products
  - Quantity adjustment
  - Dynamic total calculation
- Cart persistence using localStorage
- Clear cart functionality

### Promo Code System
- Built-in promo codes:
  - `ostad10`: 10% discount
  - `ostad5`: 5% discount
- Real-time discount calculation
- Validation features:
  - Prevents duplicate code usage
  - Invalid code detection
  - Empty input validation
- Persistent discount across page refreshes
- Clear success/error messages

### Checkout Process
- Comprehensive order summary
- Detailed price breakdown:
  - Subtotal
  - Applied discount
  - Shipping cost
  - Final total
- Shipping information form
- Payment details with validation:
  - Card number formatting (4-digit groups)
  - Expiry date (MM/YY format)
  - CVV validation
- Form validation with error messages
- Loading states and animations
- Success/error notifications

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5.3
- Bootstrap Icons
- Fake Store API

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Tanvir-yzu/Shopping_Cart.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Shopping_Cart
   ```

3. Open the project:
   - Use a local development server (recommended)
   - Or simply open `index.html` in your web browser

## Usage Guide

### Shopping
1. Browse products on the main page
2. Filter products by category using the dropdown menu
3. Add products to cart by clicking "Add to Cart"
4. View cart by clicking the cart icon
5. Adjust quantities using +/- buttons

### Using Promo Codes
1. Open the cart sidebar
2. Enter one of the valid promo codes:
   - `ostad10` for 10% off
   - `ostad5` for 5% off
3. Click "Apply"
4. Discount will be immediately applied to the total

### Checkout Process
1. Review cart and applied discounts
2. Click "Checkout" to proceed
3. Fill in shipping information
4. Enter payment details
5. Review final order summary
6. Complete purchase

## Project Structure

```
Shopping_Cart/
│
├── index.html          # Main shopping page with cart
├── checkout.html       # Checkout process page
└── README.md          # Project documentation
```

## Features in Detail

### Cart Functionality
- Real-time total calculation
- Quantity adjustment controls
- Remove items functionality
- Clear cart option
- Persistent cart data

### Promo Code System
- Input validation
- Real-time discount calculation
- Persistent discount across pages
- Clear feedback messages
- Prevention of duplicate applications

### Form Validation
- Required field validation
- Card number format checking
- Expiry date format validation
- CVV number validation
- Immediate feedback on errors

## Browser Support

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

## Acknowledgments

- [Bootstrap](https://getbootstrap.com/)
- [Fake Store API](https://fakestoreapi.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)

## Contact

Tanvir Islam - [@tanvir](https://github.com/Tanvir-yzu)

Project Link: [https://github.com/Tanvir-yzu/Shopping_Cart](https://github.com/Tanvir-yzu/Shopping_Cart) 