# GaavMart Free MVP Demo

## What this is
A starter PWA prototype for the GaavMart village marketplace. It includes:
- Customer browsing, village selection, cart and demo checkout
- Seller registration and demo seller product management
- Admin demo approval and order status management
- Proposed delivery charges for the 9 selected villages

## Important limitations
This is a **front-end demo only**. Data is stored in the browser's localStorage on the device where it is used.
It is NOT yet a real multi-user marketplace:
- Customer orders will not appear on another person's phone.
- Seller/admin data is not shared across devices.
- There is no secure production login or cloud database.
- UPI is a manual payment option; no automatic payment verification.
- The demo Admin PIN is 2468. Never use this PIN for a live service.

## Run locally
Open `index.html` in a modern browser. For PWA install/service worker testing, host it on HTTPS.

## Free online publishing
1. Create a GitHub account.
2. Create a public repository named `gaavmart`.
3. Upload `index.html`, `manifest.json`, and `sw.js` to the repository root.
4. In repository Settings -> Pages, publish from the `main` branch and `/ (root)`.
5. Open the GitHub Pages URL on Android Chrome -> menu -> Add to Home screen.

## Next step for a real launch
Create a Supabase project under the owner's own email, then add Supabase Auth, PostgreSQL tables, Storage, and Row Level Security. Replace localStorage demo functions with database operations. Add secure admin role provisioning and real seller/customer sessions before accepting real customer data or orders.

## Proposed villages and demo delivery charges
- Uttur ₹15
- Dhamane ₹20
- Bahirewadi ₹25
- Halewadi ₹25
- Mumewadi ₹25
- Chavanwadi ₹30
- Pimpalgaon ₹30
- Kallamma Belewadi ₹30
- Bamane ₹35

Charges and PIN coverage are placeholders to be verified before launch.
