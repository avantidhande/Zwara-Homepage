# Zwara-Homepage

1. Overview

This is a fully responsive food delivery website for Zwara, showcasing restaurants, food categories, offers, influencers, and a mobile app section. The project is built using HTML5, CSS3, and includes responsive design techniques to ensure optimal experience on desktop, tablet, and mobile devices.

2. Project Structure

index.html – Main HTML file containing all sections of the website.

assets/ – Folder containing:

images/ – All images used in the project.

icons/ – SVG icons used in navigation, offers, and other UI elements.

css/ – Stylesheets (including responsive styles).

3. Sections Overview

Hero Section – Logo, navigation, hamburger menu, search bar, and featured food images.

Welcome Section – Brand slider highlighting partner restaurants.

Category Section – Quick links to various food categories (Offers, Newly Added, Delivery, etc.).

Food Categories Section – Horizontal scrollable slider for specific food types (Cookies, Donut, Coffee, etc.).

Top Restaurants – Grid of restaurant cards with rating, distance, and offers.

Offer Section – Horizontal slider displaying current offers.

Influencers Section – Grid displaying influencers with horizontal scroll arrows.

Picked For You – Similar layout as Top Restaurants section.

Chocolate Lovers – Featured chocolate brands, similar to restaurants section.

Delicious Deals – Similar layout as restaurants section.

Mobile App Section – App promo with download buttons and phone mockup.

Footer – Multi-column footer with popular items, links, contact, and app download links.

4. Responsiveness Decisions & Improvements

Header & Navigation

Hamburger menu implemented for mobile screens (< 768px).

Nav links hidden behind a checkbox toggle for small devices.

Logo and buttons resized dynamically for smaller screens.

Sign-up button remains visible on mobile for quick access.

Hero Section

Food images positioned absolutely with z-index to allow overlapping.

Food plates scale down and adjust positions on smaller screens.

Search bar layout switches from horizontal to vertical on mobile.

Welcome & Slider Sections

Horizontal brand slider uses overflow scroll on small screens.

Navigation arrows hidden on small screens.

Slider items scaled for readability on devices < 600px.

Category & Food Category Sections

Grid layouts switch to fewer columns for tablets and phones.

Horizontal sliders allow touch scrolling on mobile.

Card sizes and text scaled down to prevent wrapping issues.

Restaurant / Chocolate / Picked Sections

Multi-card rows reduce number of columns on smaller screens (4 → 2 → 1).

Cards maintain image aspect ratio.

Horizontal scroll enabled for tablet view.

Offers Section

Offer slider fully swipeable on mobile.

Navigation arrows adjust size and position for small screens.

Influencers Section

Grid switches from 5-column layout on desktop to 2-column on mobile.

Horizontal arrows hidden on mobile devices.

Mobile App Section

Phone mockup scales down on mobile.

Text content stacked above image for better readability.

Footer

Footer columns stack vertically on mobile.

Reduced padding and font size on smaller devices.

App download buttons stacked vertically instead of horizontal.

5. Tools & Techniques Used

CSS Grid & Flexbox – For responsive layouts and card grids.

Media Queries – For device-specific adjustments.

Overflow & Scroll Snap – For horizontal sliders on mobile.

Relative Units (em, rem, %) – Ensures scalability.

Z-index Management – Keeps overlapping elements visually correct.

Accessible Design – Images have alt attributes; buttons clickable on mobile.

6. Future Improvements

Implement lazy loading for images to improve performance.

Add CSS transitions for smoother slider animations.

Introduce ARIA roles for better accessibility.

Integrate dynamic restaurant and offer data from a backend API.

Author: Avanti Dhande
Year: 2025
Project: Zwara Food Delivery Website – Responsive Frontend