# Capstone Project: Foodly (Food Delivery App)

**Theme:** Food Delivery App  
**Student Name:** Shantanu Pandya 
**Course:** Web Development I - Capstone Project

## Project Description
Foodly is a fully responsive, static web interface for a modern food delivery service. It focuses on clean semantic HTML5 structure and modern CSS3 styling (Flexbox & Grid) to provide a seamless user experience across desktop, tablet, and mobile devices.

## Sections Implemented
1.  **Header / Navigation:** Sticky navbar with brand logo, navigation links, cart icon with badge, and auth buttons.
2.  **Hero Section:** Full-width background with a centered call-to-action and search functionality.
3.  **How It Works:** A 3-column layout explaining the ordering process using icons.
4.  **Popular Categories:** A horizontally scrollable list of food categories (Pizza, Burger, Sushi, etc.).
5.  **Restaurant Grid:** A responsive grid displaying restaurant cards with hover effects, ratings, and delivery time.
6.  **Contact Section:** A dedicated contact area featuring a responsive form and decorative imagery.
7.  **Footer:** A multi-column footer with links, social media icons, and copyright info.

## Technical Details

### Layout Techniques
* **Semantic HTML5:** Used `<header>`, `<nav>`, `<section>`, `<article>`, `<main>`, and `<footer>` for better accessibility and SEO.
* **CSS Flexbox:** Used for the Navigation bar, Hero alignment, Category items, and general component alignment.
* **CSS Grid:** Used for the "Featured Restaurants" section and the Footer layout to create robust 2D layouts.
* **CSS Variables:** Defined in `:root` for consistent color management (Mint Green theme) and easy updates.

### Responsiveness & Breakpoints
The site adapts to different screen sizes using `@media` queries:
* **Desktop (Default):** Full 4-column grids and horizontal layouts.
* **Tablet (max-width: 1024px):**
    * Restaurant grid adjusts to 2 columns.
    * Hero typography scales down.
    * Contact section padding adjusts.
* **Mobile (max-width: 768px):**
    * Navigation links hidden (simulated hamburger menu state).
    * Hero section stacks vertically.
    * Restaurant grid becomes single-column (1fr).
    * Contact form stacks below the title; decorative image is hidden to save space.
    * Footer columns stack vertically for readability.

## Project Structure