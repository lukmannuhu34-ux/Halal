# Halal Chicken Supply – Website

Modern, mobile-first ordering website for a local Halal chicken butcher/supply business in Kasangombe-mpunga, Wakiso / Kayunga, Uganda.

## Features

- Clean, professional design inspired by leading food delivery platforms (Uber Eats, Glovo, Deliveroo, DoorDash, Just Eat, etc.)
- Prominent **حلال** (Halal) badge throughout
- Menu with categories: All / Roasted / Fresh Unroasted / Parts
- Working shopping cart (persisted in localStorage)
- One-tap WhatsApp checkout with pre-filled order message
- Sticky header + category filters
- Responsive for phone, tablet, desktop
- Fast, lightweight (vanilla HTML/CSS/JS – no frameworks)

## Current settings

**Phone numbers**
- +256 705 789 111 (primary WhatsApp / Call)
- +256 750 447 610
- +256 750 865 712

**Pricing (by weight)**
- 1kg → UGX 14,000
- ½kg → UGX 7,000
- ¼kg → UGX 3,500

## How to use

1. Open `index.html` in any modern browser.
2. Host on any static hosting (Netlify, Vercel, GitHub Pages, cPanel, etc.).

## Customisation tips

- **Prices & items**: Edit the `menuItems` array in `app.js`.
- **WhatsApp number**: Change `WHATSAPP_NUMBER` in `app.js` and the links in `index.html`.
- **Colours**: Change the CSS variables in `:root` in `styles.css`.
- **Images**: Swap the Unsplash URLs for your own photos of roasted/fresh chicken for best results.

Built for the local Google Business listing “Halal chicken supply” in the Kayunga / Wakiso area.
