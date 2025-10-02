# Savory Haven – Restaurant Website

Overview
- A complete, single-category website for a restaurant, built with Tailwind CSS (via CDN).
- Pages: index.html (home with menu teaser), about.html (our story), contact.html (booking form and location).
- Fully responsive, accessible HTML5 structure with semantic tags (header, nav, main, section, article, footer).
- Hero section includes a full-width background image (via data-bg with JS to apply background).
- All images referenced with descriptive alt attributes.
- Simple navigation across pages with internal linking.

Design notes
- Theme: refined, warm, and inviting; typography uses category-appropriate fonts via Tailwind utility classes as described in the spec.
- Colors: Restaurant palette based on warm browns and creams (see header/footer usage in files).
- Animations: Tailwind-based hover and transition effects; lightweight interactivity via a small inline script for mobile menu and hero background image (kept minimal for performance).

File structure
- index.html: Home page with hero, sample menu items, story preview, testimonials, and gallery.
- about.html: About page with our story and team photo.
- contact.html: Booking form, location details, and map placeholder.
- README.md: This file.

How to run
1. Copy the three HTML files and README.md to a local server or open directly in a browser.
2. Ensure you have an internet connection for Tailwind CDN and any external resources.
3. Use the navigation to browse Home, About, and Contact pages.

Notes on content placeholders
- All placeholders for images use the pattern https://images.unsplash.com/photo-1635029783698-5152fbd342ba?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHwxMHx8ZGVzY3JpcHRpb258ZW58MHwwfHx8MTc1OTMyNTcyNXww&ixlib=rb-4.1.0&q=80&w=1080 and are intended to be replaced by real assets in a production deployment.
- Hero uses data-bg attribute to set the background image via a tiny JS snippet included in each HTML file.

Extensibility
- To add more pages (e.g., a full Menu page or a Gallery page), follow the existing pattern and update navigation in all pages.
- To adjust theming per category, modify the color/typography tokens in the respective HTML files (inline or via consistent class naming).
