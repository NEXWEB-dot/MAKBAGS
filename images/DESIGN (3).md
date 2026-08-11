---
version: alpha
name: GulAhmed Accessories & Bags Collection
description: A sophisticated fashion retail interface specializing in handbags and accessories with a focus on product-first visual storytelling and high-density grid layouts.
colors:
  primary: "#232323"
  accent: "#d12442"
  background: "#ffffff"
  secondary-bg: "#f6f8f9"
  border: "#e6e6e6"
  sale-badge: "#d12442"
  new-badge: "#8cc63f"
  hot-badge: "#ff8b21"
typography:
  family: "Assistant, sans-serif"
  heading-lg: "900 20px/1.2 Assistant"
  body-md: "400 14px/1.5 Assistant"
  price-sm: "600 14px Assistant"
  label-xs: "700 12px Assistant"
spacing:
  container: "1770px"
  grid-gap: "20px"
  section-padding: "40px"
rounded:
  default: "0px"
  badge: "4px"
  button: "0px"
components:
  product-card:
    background: "{colors.background}"
    border: "1px solid {colors.border}"
    padding: "15px"
  primary-button:
    background: "{colors.primary}"
    color: "#ffffff"
    padding: "10px 20px"
  sale-price:
    color: "{colors.accent}"
    weight: "bold"
---

## Overview
The GulAhmed Ideas collection page presents a premium e-commerce environment characterized by high-density product grids and a clean, minimalist aesthetic. The personality is professional and retail-focused, utilizing a strict monochromatic base (white and charcoal) to allow the vibrant product photography to serve as the primary visual driver. Motion is subtle, primarily used for hover states and image carousels, while the overall layout emphasizes efficiency and structured browsing.

## Colors
The palette is primarily functional. {colors.primary} (#232323) is used for all primary text and iconography to ensure high contrast against the {colors.background} (#ffffff). Semantic colors are reserved for urgency and categorization: {colors.accent} (#d12442) identifies sale items and discounts, while green (#8cc63f) and orange (#ff8b21) signify 'New' and 'Hot' statuses respectively. Neutral greys like #f6f8f9 provide soft structural differentiation in drawers and secondary sections.

## Typography
The typography is modern and highly legible, dominated by the Assistant sans-serif family. A strict hierarchy is maintained: large uppercase weights for branding and headings, standard weights for product titles, and bold, condensed styles for pricing. Letter spacing is tight but consistent, favoring a dense, editorial feel. Product titles utilize an ellipsis for overflow, maintaining grid alignment.

## Layout
The layout follows a high-density grid system within a massive 1770px max-width container. Navigation is tiered, featuring a persistent sticky header with category tabs and a utility bar. Product cards are arranged in a multi-column responsive grid (typically 4 columns on desktop, 2 on mobile). Spacing is disciplined, using consistent 20px gaps to create a rhythmic, structured flow that maximizes screen real estate for product display.

## Elevation & Depth
Visual depth is achieved through layering rather than heavy shadows. The interface is predominantly flat, relying on 1px borders and subtle background color shifts to define areas. Elements like the search modal and 'Quick View' drawers use high-index layering and semi-transparent overlays (rgba 35,35,35, 0.8) to separate focused tasks from the background grid. Floating action buttons (like Wishlist) use subtle white-on-white layering.

## Shapes
The design language is sharply geometric. Rectangular shapes with zero border-radius define the buttons, inputs, and product containers, reinforcing a high-fashion, architectural feel. The only exceptions are the status badges and small utility icons which feature a 4px softened corner or circular housing, providing a minor organic counterpoint to the rigid grid.

## Components
### Header
A complex multi-part component containing a category tab switcher, a primary navigation menu with mega-menu capabilities, and a utility area for search and account management.
### Product Card
A sophisticated unit featuring a multi-image carousel (PCS), hover-activated overlays for wishlist and quick-shop, and a clear price-strike-through hierarchy for sale items.
### Search Modal
A full-screen or slide-out predictive search interface that displays trending products and live results in a condensed list format.
### Badge
Small rectangular labels applied to product images that use high-saturation background colors to communicate item status (e.g., -25% Sale).

## Do's and Don'ts
### Do's
- Use high-resolution vertical aspect ratio (2:3) product photography.
- Maintain a strict monochromatic text hierarchy.
- Ensure the sticky header transition is smooth and reduces in height upon scroll.
- Use bold red for all sale-related pricing and labels.

### Don'ts
- Do not use rounded corners on primary action buttons or product images.
- Do not use drop shadows on product cards or grid elements.
- Do not introduce non-sans-serif fonts into the primary UI.
- Do not clutter the product card with excessive metadata; keep the focus on title and price.

## Accessibility
Accessibility is addressed through high-contrast text ({colors.primary} on white) and clearly defined focus states for modal elements. The interface includes a 'Skip to Content' link for keyboard users. Interactive elements like the product carousel dots and wishlist buttons feature ARIA labels. Large touch targets are used for mobile navigation, and price information is semantically marked up to ensure clear screen reader interpretation of discounts.

## Assets
- **Tan Handbag Closeup**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-closeup-ideas_940x.jpg?v=1779690840
- **Tan Handbag Front (Small)**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-front1-ideas_450x.jpg?v=1779690840
- **Tan Handbag Front (Medium)**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-front1-ideas_600x.jpg?v=1779690840
- **Tan Handbag Front (Large)**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-front1-ideas_750x.jpg?v=1779690840
- **Tan Handbag Front (XL)**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-front1-ideas_940x.jpg?v=1779690840
- **Tan Handbag Front 2**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-front2-ideas_940x.jpg?v=1779690840
- **Tan Handbag Side**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-side-ideas_940x.jpg?v=1779690840
- **Tan Handbag Top 1**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-top1-ideas_940x.jpg?v=1779690840
- **Tan Handbag Top 2**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-top2-ideas_940x.jpg?v=1779690840
- **Tan Handbag Top 3**: https://www.gulahmedshop.com/cdn/shop/files/474465-tan-handbag-top3-ideas_940x.jpg?v=1779690840
- **Favicon SVG 16**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg_16x16.svg?v=1780559853
- **Apple Touch Icon**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg_180x180.svg?v=1780559853
- **Favicon SVG 192**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg_192x192.svg?v=1780559853
- **Favicon SVG 32**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg_32x32.svg?v=1780559853
- **Favicon SVG 48**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg_48x48.svg?v=1780559853
- **Favicon SVG 512**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg_512x512.svg?v=1780559853
- **Favicon SVG 96**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg_96x96.svg?v=1780559853
- **Base Favicon**: https://www.gulahmedshop.com/cdn/shop/files/favicon-svg.svg?v=1780559853
- **Globe Icon**: https://www.gulahmedshop.com/cdn/shop/files/globe-icon.svg?v=1758026467
- **Heart Icon**: https://www.gulahmedshop.com/cdn/shop/files/heart-icon.svg?v=1758026468
- **Ideas Logo (150x)**: https://www.gulahmedshop.com/cdn/shop/files/ideas_logo_150x.webp?v=1758102474
- **Ideas Logo (300x)**: https://www.gulahmedshop.com/cdn/shop/files/ideas_logo_300x.webp?v=1758102474
- **Loading Logo**: https://www.gulahmedshop.com/cdn/shop/files/ideas_logo.webp?v=1758102474&width=600
- **Limited Edition Badge**: https://www.gulahmedshop.com/cdn/shop/files/limited-edition.png?v=1766050742&width=150
- **Lookbook Icon**: https://www.gulahmedshop.com/cdn/shop/files/lookbook-icon.svg?v=1758026467
- **PK Flag Icon**: https://www.gulahmedshop.com/cdn/shop/files/pk-flag-icon.svg?v=1758613809
- **Profile Icon**: https://www.gulahmedshop.com/cdn/shop/files/profile-icon.svg?v=1758026467
- **Rewards Icon**: https://www.gulahmedshop.com/cdn/shop/files/rewards-icon.svg?v=1758026467
- **Animated CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/animated.css?v=91884483947907798981758022209
- **Slideshow CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/base-slideshow.min.css?v=29059834094819355641786188858
- **Badge Component CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-badge.css?v=112426363488949229811780895919
- **Card Component CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-card.css?v=132527987044253393461784806365
- **Social List CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-list-social.css?v=160160302884525886651758022210
- **Loading Banner CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-loading-banner.css?v=3915546272529853611758022210
- **Loading Overlay CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-loading-overlay.css?v=18073828481037188521775620558
- **Newsletter Component CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-newsletter.css?v=117381748585997439661778828448
- **Predictive Search CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-predictive-search.css?v=171622479274651275511784373565
- **Price Component CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-price.css?v=183607838197847274831758022210
- **Product Form CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-product-form.css?v=4572955477144245621784806364
- **Quick Cart CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-quick-cart.css?v=98636131316705162861763537471
- **RTE Component CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-rte.css?v=111654073890783685521758351837
- **Share Component CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-share.css?v=175502223978466257561762862236
- **Slider Component CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/component-slider.css?v=18320497342874123791758022210
- **Custom Menu CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/custom-menu.css?v=26408877076512528751775648877
- **Fade Animation CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/fade-up-animation.css?v=148448505227430981271758022211
- **Vendor Bundle CSS**: https://www.gulahmedshop.com/cdn/shop/t/2/assets/vendor.css?v=61888327179989329541758022212",
  "notes": "The GulAhmed collection page was distilled into a DESIGN.md output by identifying its core grid-based structure, high-contrast retail-focused color palette, and specifically documented component logic such as the multi-image product carousels."
}