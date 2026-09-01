# Sarika Theme — Custom Shopify E-commerce Theme

A custom, conversion-focused Shopify theme built from scratch to demonstrate
UI/UX design and front-end development for e-commerce. Covers the full customer
journey — landing, product discovery, product detail, and enquiry — with a
consistent visual identity and a fully responsive layout across desktop,
tablet, and mobile.

> **Live preview:** https://sarika-dev-store.myshopify.com
> _(development store — password protected; available on request)_

---

## Highlights

- **Design system** — reusable design tokens (colour, typography scale,
  spacing, radius, shadows) exposed as merchant-editable theme settings.
- **Conversion-focused homepage** — full-width hero with dual CTAs,
  announcement bar, featured products grid, and promotional banner.
- **High-intent product page** — image gallery with thumbnail switching,
  variant selector, quantity stepper, trust badges, mobile sticky add-to-cart,
  and expandable detail accordions.
- **Usable collection browsing** — breadcrumb, product count, native sort,
  responsive grid with hover quick-add, and styled pagination.
- **Contact form** — built on Shopify's native form handling with required
  fields and success/error states.
- **Fully responsive** — mobile-first layouts with consistent container widths
  across all sections.

---

## Tech

- **Shopify Liquid** — sections, snippets, blocks, JSON templates
- **HTML5 / CSS3** — CSS custom properties (design tokens), Grid, Flexbox
- **JavaScript** — gallery switcher, mobile sticky add-to-cart (IntersectionObserver)
- **Shopify CLI** — local development and deployment

---

## Project Structure

```
sarika-theme/
├── assets/        # critical.css, icons
├── blocks/        # reusable nestable components
├── config/        # theme settings (design tokens) + schema
├── layout/        # theme.liquid wrapper
├── locales/       # translation strings
├── sections/      # hero, product, collection, contact-form, footer, etc.
├── snippets/      # product-card, css-variables, image, meta-tags
└── templates/     # JSON page templates
```

---

## Key Files

| Area | File |
|------|------|
| Design tokens | `snippets/css-variables.liquid`, `config/settings_schema.json` |
| Global styles | `assets/critical.css` |
| Hero | `sections/hero.liquid` |
| Product page | `sections/product.liquid` |
| Collection page | `sections/collection.liquid` |
| Product card | `snippets/product-card.liquid` |
| Contact form | `sections/contact-form.liquid` |
| Footer | `sections/footer.liquid` |

---

## Running Locally

Requires the [Shopify CLI](https://shopify.dev/docs/api/shopify-cli).

```bash
cd sarika-theme
shopify theme dev --store your-store.myshopify.com
```

---

## Case Study

A full write-up of the problem, approach, and result is in
[`sarika-theme/CASE_STUDY.md`](./sarika-theme/CASE_STUDY.md).

---

## Screenshots

_Desktop and mobile screenshots for the homepage, product page, collection page,
and contact form._

| Page | Desktop | Mobile |
|------|---------|--------|
| Homepage | _add_ | _add_ |
| Product | _add_ | _add_ |
| Collection | _add_ | _add_ |
| Contact | _add_ | _add_ |

---

## Author

**Sarika Yadav** — UI/UX & Web Design · Front-End Development
[GitHub](https://github.com/sarikayadav24) · [LinkedIn](https://www.linkedin.com/in/yadavsarika/)
