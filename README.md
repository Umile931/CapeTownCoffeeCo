# Cape Town Coffee Co - WEDE5020
Student: Umile Mbombela ST10524342
Module: WEDE5020 - Portfolio of Evidence (Final PoE)

Live Site: https://capetowncoffeeco-a730cf.netlify.app
GitHub Repo: https://github.com/Umile931/CapeTownCoffeeCo

## Project Overview
A responsive website for Cape Town Coffee Co featuring Home, About, Menu, Order, and Contact pages. Built with HTML5, CSS3, and JavaScript. The site showcases specialty coffee on Long Street, Cape Town with online ordering.

## Changelog (REQUIRED FOR PART 3)

### Part 1 -> Final PoE Fixes (Feedback from Formative 1)
- Fixed navigation bar - made consistent across all 5 pages
- Changed image file names from generic to descriptive SEO names: e.g. coffee-small.jpg -> cape-town-flat-white-specialty-coffee.jpg
- Added alt text to all images for accessibility: e.g. alt="Flat White coffee - Cape Town Coffee Co Long Street"
- Added semantic HTML5 tags: header, main, nav, footer, section

### Part 2 -> Final PoE Fixes (Feedback from Formative 2)
- Changed all font sizes from px to rem units (e.g. 16px -> 1rem) for responsiveness
- Fixed responsive layout - added media query @media (max-width: 768px) - menu now stacks on mobile
- Compressed all images to under 200KB for page speed optimization
- Added hover states and focus states to buttons and links
- Fixed colour contrast for accessibility

### Part 3 - New Implementation (WEDE5020 Part 3 Requirements)
- JavaScript: Added interactive accordion for FAQ, tabs for Our Story, modal for ordering
- JavaScript: Implemented Leaflet.js interactive map on contact.html showing 123 Long Street location
- JavaScript: Gallery lightbox with CSS transitions when clicking menu images
- JavaScript: Dynamic loading of menu items from JS array (menuData) - not hardcoded HTML
- JavaScript: Search and filter functionality - search menu, filter by coffee/food category
- SEO: Added title tags and meta descriptions to all pages, H1-H3 hierarchy, image alt text
- SEO: Created robots.txt and sitemap.xml in root folder
- SEO: Added local SEO - Cape Town address, keywords: coffee Cape Town, cafe Long Street
- SEO: Clean URL structure, internal linking, page speed optimized
- Security: Form input sanitization, HTTPS deployment via Netlify
- Forms: Added JS validation, HTML5 validation, error handling, AJAX fetch submission
- GitHub: Regular commits with meaningful messages

## Folder Structure
CapeTownCoffeeCo/
├── index.html
├── about.html
├── menu.html
├── order.html
├── contact.html
├── README.md
├── robots.txt
├── sitemap.xml
├── css/
│ └── style.css
├── js/
│ └── script.js
└── images/
├── coffee-small.jpg
