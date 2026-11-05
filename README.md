# Brown Ocean Coffee — Premium Storefront Prototype

A responsive, premium coffee storefront based on the approved Brown Ocean Coffee concept board. Built with plain HTML, CSS and JavaScript; no build step or package installation is required.

## Run locally

1. Download and extract `brown-ocean-coffee-website.zip`.
2. Open `brown-ocean-coffee/index.html` in a browser, or run a local static server from the project folder:

   ```bash
   python -m http.server 8080
   ```

3. Visit `http://localhost:8080`.

## Included

- Espresso-brown, cream and caramel visual system
- Responsive homepage, story, ritual/category sections and footer
- 12 sample products across Instant Coffee, Roasted Coffee Beans and Brewing Bags
- Category filtering and product search
- Product quick-view modal with selectable pack sizes and prices
- Cart drawer with quantity changes, remove item, subtotal and local browser persistence
- Newsletter interaction placeholder, mobile navigation and scroll-reveal animations

## Important before launch

This is a frontend prototype, not a production e-commerce system. Product names, prices, sizes, descriptions and photos are placeholders and must be confirmed by the business. Photos load from Unsplash and require an internet connection. The cart is stored in the current browser only. Newsletter submission and checkout are demonstration interactions.

For a real store, connect a backend/database, stock management, customer accounts, shipping/tax rules, email service and payment provider such as Razorpay. Create payment orders and verify payment signatures/webhooks on the backend; never put payment secret keys in frontend code. Confirm all prices, product claims, legal pages and shipping/return policies before launch.
