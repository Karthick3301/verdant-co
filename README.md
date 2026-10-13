# Verdant & Co.

Plant nursery website prototype (frontend only, no backend).

## Live Demo

https://verdant-plant-nursery.netlify.app

## Features

- Video hero carousel on the home page: one video slide (`videos/hero.mp4`) plus three photo slides, with previous/next arrows, clickable dots, touch swipe support, and timed auto-advance.
- Shop by type section with category cards (Trees, Perennials, Houseplants, Seeds and bulbs) linking to the shop.
- Featured plants section with seasonal picks, ratings, prices, wishlist buttons, and add-to-cart buttons.
- Shop catalog with category pill filters, sidebar filters (light requirements, watering schedule, pet-friendly toggle, planter diameter, price range), sort dropdown, and product grid.
- Plant match quiz modal on the shop page, opened from the "Take Plant Match Quiz" button.
- Product page for Monstera Deliciosa with photo gallery and thumbnails, specimen size and planter selection, quantity stepper, care matrix, grower spotlight, reviews, and FAQ accordion.
- Cart page with reserved items and quantity controls, dispatch date options, eco packaging options, order summary with coupon field, and checkout button.
- Plant care clinic page with symptom checker cards and diagnosis panel, seasonal care checklist, workshop listings, video consultation booking form with date and time selection, and resource library.
- Responsive layout with a mobile menu toggled from the header on small screens.

## Pages

| File | Description |
| --- | --- |
| `index.html` | Home page: hero carousel, shop by type, featured plants, plant finder banner, visit section, and footer. |
| `shop.html` | Shop catalog: category pills, filter sidebar, product grid, plant match quiz modal, and promotional sections. |
| `product.html` | Product detail page for Monstera Deliciosa: gallery, size and planter options, care matrix, reviews, and FAQs. |
| `cart.html` | Cart page: selected items, dispatch scheduling, packaging options, order summary, and checkout. |
| `clinic.html` | Plant care clinic page: symptom checker, seasonal care tasks, workshops, consultation booking, and guides. |

## Tech Stack

- HTML
- Tailwind CSS via CDN
- Vanilla JavaScript (inline scripts, no framework)
- Google Fonts: Playfair Display and Plus Jakarta Sans
- Material Symbols icons
- Deployed on Netlify from GitHub

## Project Structure

```text
.
├── index.html
├── shop.html
├── product.html
├── cart.html
├── clinic.html
├── README.md
└── videos/
    ├── hero.mp4
    └── hero-poster.png
```

## Run Locally

No build step needed. Open `index.html` in a browser.

```text
index.html
```

## Deployment

1. Push the repo to GitHub.
2. Import the repo in Netlify.
3. Leave the build command and publish directory empty.

## Notes

- This is a prototype; there is no backend or real checkout.
- Prices, cart contents, footer address, hours, phone, and email are placeholders.
- Images are loaded from external URLs.
- The hero video is `videos/hero.mp4`.
