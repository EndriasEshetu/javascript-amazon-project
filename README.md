# 🛒 Amazon Clone

A front-end clone of the Amazon shopping experience built with vanilla **HTML**, **CSS**, and **JavaScript**. This project replicates core e-commerce functionality including product browsing, cart management, checkout, order tracking, and delivery options.

## ✨ Features

- **Product Listing** — Browse a catalog of products with images, ratings, and prices
- **Add to Cart** — Add items to a persistent cart (saved in `localStorage`)
- **Checkout Flow** — Review order summary with itemized pricing and delivery options
- **Delivery Options** — Choose between multiple shipping speeds
- **Order Tracking** — View placed orders and track delivery status
- **Responsive Design** — Works across desktop and mobile screen sizes

## 📁 Project Structure

```
javascript-amazon-project/
├── amazon.html          # Main product listing page
├── checkout.html        # Checkout / order review page
├── orders.html          # Order history page
├── tracking.html        # Order tracking page
├── data/                # Data modules (cart, products, delivery options, orders)
├── scripts/             # JavaScript modules & logic
│   ├── amazon.js        # Product page script
│   ├── checkout.js      # Checkout page script
│   ├── checkout/        # Checkout-specific modules
│   └── utils/           # Utility functions
├── styles/              # CSS stylesheets
│   ├── shared/          # Shared styles (header, general)
│   └── pages/           # Page-specific styles
├── images/              # Product images, icons, and assets
├── tests/               # Unit tests
├── backend/             # Backend data (products JSON)
└── variations/          # Product variation experiments
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/EndriasEshetu/javascript-amazon-project.git
   cd javascript-amazon-project
   ```

2. **Open in browser**

   Open `amazon.html` directly in your browser, or use a local server:
   ```bash
   npx serve .
   ```

> No build tools or dependencies required — it's all vanilla HTML, CSS, and JS with ES modules.

## 🛠️ Technologies

- **HTML5** — Semantic markup & responsive meta tags
- **CSS3** — Custom stylesheets with Roboto font (Google Fonts)
- **JavaScript (ES Modules)** — Modular architecture with `import`/`export`
- **localStorage** — Client-side cart persistence
- **Jasmine** — Unit testing

## 📄 License

This project is licensed under the [MIT License](tests/MIT.LICENSE).
