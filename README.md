# Prizmox Product Manual Portal

Static manual portal for U.S. ecommerce sales and post-purchase support.

## Live URLs

- Home: `https://prizmox.github.io/Product-manual/`
- Manual PDF: `https://prizmox.github.io/Product-manual/pdfs/Prizmox_B221H00_Quick_User_Guide.pdf`

## Brand and Contact

- Brand logo file: `brand-logo.png`
- Customer support email: `Prizmoxcs@outlook.com`
- Amazon store: `https://www.amazon.com/s?me=A134988YS0XGQ4&marketplaceID=A2EUQ1WTGCTBG2`

## Repository Structure

```text
Product-manual/
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
2. Add a new manual card/link in `index.html`.
3. Commit and push to `main`.

### Update contact or store links

1. Edit contact links in `index.html`.
2. Keep this `README.md` in sync.
