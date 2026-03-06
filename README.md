# Prizmox Product Manual Portal

Static manual portal for U.S. ecommerce sales and post-purchase support.

## Live URLs

- Home: `https://prizmox.github.io/Product-manual/`
- Manual PDF: `https://prizmox.github.io/Product-manual/pdfs/Prizmox_B221H00_Quick_User_Guide.pdf`

## Brand and Contact

- Brand logo file: `brand-logo.png`
- Product image file: `assets/images/B221H00.jpg`
- Customer support email: `Prizmoxcs@outlook.com`
- Amazon store: `https://www.amazon.com/s?me=A134988YS0XGQ4&marketplaceID=A2EUQ1WTGCTBG2`
- Amazon product detail page: `https://www.amazon.com/dp/B0FPLSQYFS`

## Page Features

- Search bar with keyword filtering for manual cards.
- Product card with image, manual link, and Amazon detail link.
- Warranty and support contact section.

## Repository Structure

```text
Product-manual/
├─ assets/
│  └─ images/
│     └─ B221H00.jpg
├─ brand-logo.png
├─ index.html
├─ pdfs/
│  └─ Prizmox_B221H00_Quick_User_Guide.pdf
├─ .gitignore
└─ README.md
```

## GitHub Pages Setup

1. Open repository `Settings`.
2. Open `Pages`.
3. Set `Source` to `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save and wait for deployment.

## Maintenance

### Add a new manual PDF

1. Put the PDF file into `pdfs/`.
2. Add a new manual card/link in `index.html` and include search keywords in `data-search-text`.
3. Commit and push to `main`.

### Add or update product images

1. Put product images into `assets/images/`.
2. Update the corresponding image path in `index.html`.

### Update contact or store links

1. Edit contact links in `index.html`.
2. Keep this `README.md` in sync.
