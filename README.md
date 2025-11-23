# Shopify Theme - Conversion-Optimized Product Pages

This is a Shopify Liquid theme with conversion-optimized product page templates and sections.

## Project Type
**Shopify Liquid Theme** - This is not a Node.js application. The theme files are deployed directly to Shopify.

## Quick Start

1. **View Documentation:**
   - `QUICK-START.md` - How to apply the template to your products
   - `CONVERSION-IMPROVEMENTS.md` - Detailed feature documentation
   - `RAZOR-PRODUCT-CONTENT.md` - Product-specific content reference
   - `CONTENT-SUMMARY.md` - Quick content overview

2. **Apply to Product:**
   - Go to Shopify Admin > Products
   - Select your product (e.g., 3-in-1 Electric Razor)
   - Choose template: "product.conversion-optimized"
   - Save

## Structure

```
├── assets/           # CSS, JS, images
├── config/           # Theme settings
├── layout/           # Theme layouts
├── locales/          # Translations
├── sections/         # Reusable sections (NEW conversion sections here)
├── snippets/         # Reusable components (NEW benefit snippets here)
└── templates/        # Page templates (NEW conversion template here)
```

## New Files

**Templates:**
- `templates/product.conversion-optimized.json` - Main conversion template

**Sections:**
- `sections/product-how-it-works.liquid` - 3-step usage guide
- `sections/product-why-choose.liquid` - Feature highlights
- `sections/product-who-its-for.liquid` - Target personas
- `sections/product-faq.liquid` - FAQ accordion
- `sections/product-reviews-placeholder.liquid` - Reviews integration

**Snippets:**
- `snippets/product-benefits.liquid` - Benefit bullets
- `snippets/product-hero-description.liquid` - Hero description

**Styles:**
- `assets/product-conversion-enhancements.css` - Conversion-focused styles

**Modified:**
- `sections/main-product.liquid` - Added new block types

## Shopify Theme Development

This theme is edited through:
- **Shopify Admin Theme Editor** (recommended for content)
- **Shopify CLI** for local development
- Direct file editing for code changes

No build process is required - this is pure Liquid/HTML/CSS/JS.

## Deployment Notes

The `package.json` file exists only to satisfy deployment system requirements. This is a Shopify theme and doesn't require npm packages or a build process.
