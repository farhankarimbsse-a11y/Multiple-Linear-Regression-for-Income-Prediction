# GB Dry Fruit — Mobile-friendly online store

A responsive storefront built with HTML, CSS and JavaScript. It works on laptop, tablet and mobile screens and includes product search, categories, price filtering, sorting, a shopping cart, and WhatsApp order-message generation.

## Files

- `index.html` — website structure
- `style.css` — desktop and mobile styling
- `script.js` — product list, search, filters, cart and WhatsApp order flow
- `images/` — local product images used by the catalogue

## Open locally

Open `index.html` in a browser, or open the folder in VS Code and use Live Server.

## Important: before accepting orders

1. Open `script.js`.
2. At the top, replace the empty `WHATSAPP_NUMBER` value with your business WhatsApp number in international format, digits only. For a Pakistan number, use `92` followed by the mobile number, without `+`, spaces or dashes. Example format: `923001234567`.
3. Update each product's `name`, `weight`, and `price` in the `products` array with your actual catalogue information. The current products and prices are sample display data only. The website also displays a note telling customers to confirm current prices.
4. Keep the `images` folder in the repository root along with `index.html`, `style.css` and `script.js`.

## Update the existing GitHub Pages website

Upload and replace the contents of the `GB-Dry-Fruit` folder in your existing repository. Upload the four main files and the complete `images` folder. Do not upload only the ZIP, and do not put the files inside an extra nested folder. Commit the changes. GitHub Pages will redeploy from `main` / `(root)`.

## Scope

This is a front-end demo store. It does not yet include online card payments, customer accounts, inventory syncing, or a database/admin panel. WhatsApp checkout remains disabled until you add your real business number.
