# DigiMart AI

A responsive digital-products marketplace MVP for India + Global creators.

## Included in this MVP
- Responsive marketplace with search, category filters and price sorting
- Demo product catalogue
- Seller listing form with input validation
- Browser-local cart and demo checkout
- Seller dashboard with listing, cart and demo-order metrics
- INR pricing and accessible interface

## Run locally
Open `index.html` in a modern browser, or serve this folder with any static web server.

## Deploy
This is a static site and can be deployed to Vercel by importing this GitHub repository. No build command is required; set the output directory to `.` if prompted.

## Important MVP limitations
- Listings, cart and demo orders use browser `localStorage`; they are not shared between devices or users.
- Checkout is a simulation. No payment is collected and no order is paid.
- Product delivery links are informational only; secure file hosting and access-controlled delivery are not implemented.
- Authentication, seller payouts, taxes, refunds, moderation and admin permissions require a production backend.
- Demo catalogue items are sample listings, not actual purchasable products.

## Suggested production upgrade
Connect a managed database and authentication provider, then integrate a supported payment provider (for example Razorpay for India and Stripe where available) using server-side verified webhooks. Add private object storage and signed, expiring download URLs. Never expose payment secrets in frontend code.

## License
MIT
