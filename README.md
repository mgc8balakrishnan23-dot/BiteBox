# BiteBox — Food Ordering Demo

A responsive static food-ordering website built with HTML, CSS and vanilla JavaScript.

## Run locally
Open `index.html` in a browser, or use VS Code Live Server.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload all files and folders from this project (keep the `images/` and `media/` folders).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Your site will be published at the GitHub Pages URL shown there. The first page is `index.html` (login).

## Included features
- Login and sign-up demo flows
- Product menu, search and category filter
- Add to cart, quantity controls and remove item
- Cart subtotal, delivery fee and total calculation
- Coupon codes: `WELCOME50`, `BOX100`, `FREEDEL`
- Checkout with address and payment-method selection (demo only)
- Order confirmation and order history
- Responsive layout for mobile and desktop

## Important demo limitation
This is a front-end-only project. User accounts, cart and orders are stored in the browser's `localStorage`; passwords are not securely protected and there is no real server, payment gateway, restaurant dispatch or order delivery. Do not use real passwords or payment details. A production app needs a backend, secure authentication and a payment provider.
