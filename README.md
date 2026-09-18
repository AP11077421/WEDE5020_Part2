
# FORMEZ
ST10515197 Maje Kgothatso Mohlamonyane

## Project Overview
This project is the development of a responsive, functional website for
FORMEZ, a South African fashion and clothing retailer founded in 2019.
The website showcases FORMEZ's brand identity, product range, and
customer engagement channels.

# Website GOALS and Objectives
- Promote FORMEZ's brand identity and product range.
- Provide an easy-to-navigate, informative and engaging user experience.
- Drive customer engagement through enquiries and contact channels.
- Support FORMEZ's goals around sustainability and innovation.

## Sitemap
```
FORMEZ Website
|
|-- Home (index.html)
|-- About Us (about.html)
|-- Products (services.html)
|     |-- Classic Oval Logo Tee (product_classic_oval-tee.html)
|     |-- Wordmark Tee (product_wordmark-tee.html)
|     |-- Sunset Oval Tee (product_sunset_oval-tee.html)
|     |-- Oval Logo 5-Panel Cap (product_oval_cap.html)
|     `-- Oval Logo Beanie (product_oval_beanie.html)
|-- Cart (cart.html)
|-- Checkout (checkout.html)
|-- Enquiries (inquiries.html)
`-- Contact (contact.html)
```

## Part 2 Additions
Part 2 builds on the Part 1 structure and content with a full visual
design and responsive layout:
- Added a single stylesheet (`formez/css_assets/stlyle.css`), linked
  from every page, covering the header/navigation, hero, product
  grid, product detail layout, forms, tables and footer.
- Made the site responsive across three breakpoints: smartphones
  (base styles), tablets (600px and up), and laptops/bigger screens
  (1024px and up). Layout, images and text sizing all adjust at
  each stage — e.g. the navigation stacks on mobile and becomes a
  horizontal row from tablet size up, and the product grid shows 1,
  2 or 3 cards per row depending on screen width.
- All images use responsive sizing so they scale within their
  containers on any device.

## Folder Structure
```
formez/
|-- index.html, about.html, services.html, contact.html,
|   inquiries.html, cart.html, checkout.html
|-- product_*.html (individual product detail pages)
|-- css_assets/stlyle.css
|-- js_assets/
|-- _images/
`-- private/




## Changelog

### Part 2
- Added `formez/css_assets/stlyle.css` and linked it from every page.
- Built a mobile-first responsive layout with breakpoints at 600px
  (tablet) and 1024px (desktop).
- Made all images responsive (`max-width: 100%; height: auto;`) so
  they scale within their containers on any device.
- Made navigation change layout by screen size: stacked column on
  mobile, horizontal row from tablet size up.
- Made heading and hero text sizes scale up on tablet and desktop.
- Fixed a stray closing `</div>` in `index.html` that was breaking
  the hero section markup.
- Added the missing header logo image to
  `product_sunset_oval-tee.html` for consistency with the other pages.
- Added this README's Folder Structure, Screenshot Evidence,
  Changelog and References sections.




