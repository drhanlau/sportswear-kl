# APEX Athletics — Sportswear Shop Landing Page

A modern, dark-themed sportswear e-commerce website for a fictional premium athletic store in Kuala Lumpur, Malaysia.

🔗 **Live Site:** https://drhanlau.github.io/sportswear-kl/

---

## Pages

| Page | URL | Description |
|------|-----|-------------|
| Landing | [index.html](https://drhanlau.github.io/sportswear-kl/) | Hero, categories, about, testimonials, contact |
| Catalog | [catalog.html](https://drhanlau.github.io/sportswear-kl/catalog.html) | 12 products with sidebar filters, sorting, pagination |
| Product | [product.html](https://drhanlau.github.io/sportswear-kl/product.html) | Image gallery, size/color picker, tabs, reviews |
| Dashboard | [dashboard.html](https://drhanlau.github.io/sportswear-kl/dashboard.html) | KPIs, revenue/category/order charts, recent orders |
| CRM | [crm.html](https://drhanlau.github.io/sportswear-kl/crm.html) | RFM customer segmentation, segment charts, customer list |

---

## Features

### Customer-Facing
- Responsive dark UI with orange (#ff4d00) accent
- Bebas Neue display + Inter body font pairing
- Real Unsplash photography throughout
- Interactive category cards with hover zoom
- Product filtering by category, price, brand, size
- Image gallery with thumbnail switching
- Color/size selectors with stock status
- Animated add-to-cart button
- Tabbed product details with reviews
- Customer testimonials with local Malaysian names

### Admin
- Sidebar navigation with active states
- KPI cards with trend indicators (revenue, orders, customers, AOV)
- Chart.js powered charts (line, bar, doughnut)
- Orders table with status badges
- Top selling products with images
- Traffic sources and customer locations

### CRM (RFM Segmentation)
- 8 customer segments based on Recency, Frequency, Monetary
- Segment cards with click-to-filter
- Individual R/F/M scores (1-5) per customer
- Revenue contribution by segment
- Recommended actions per segment

---

## Tech Stack

- **HTML5** — Single-file pages, no build step
- **Tailwind CSS** — Via CDN
- **Chart.js** — Dashboard & CRM charts
- **Google Fonts** — Bebas Neue + Inter
- **Unsplash** — Product & lifestyle photography

---

## Local Development

```bash
# Clone the repo
git clone https://github.com/drhanlau/sportswear-kl.git

# Open in browser
open index.html
```

No build tools, bundlers, or dependencies required. Each `.html` file is self-contained.

---

## Project Structure

```
sportswear-kl/
├── index.html        # Landing page
├── catalog.html      # Product catalog
├── product.html      # Product detail
├── dashboard.html    # Admin dashboard
├── crm.html          # Customer segments (RFM)
└── README.md
```

---

## Stats

- **3,406** lines of code
- **5** HTML pages
- **10+** Unsplash images
- **4** Chart.js charts
- **8** RFM customer segments
- **12** product listings
- **0** dependencies to install

---

## License

MIT
