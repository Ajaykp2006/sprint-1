# Prodesk IT - Corporate Landing Page

A fast, responsive, and modern landing page built for **Prodesk IT**, an IT and Engineering Services company. This project was developed entirely from scratch using Vanilla HTML, CSS, and JavaScript—strictly without the use of external CSS frameworks like Bootstrap or Tailwind.

## 🔗 Important Links

- **Live Website:** [sprint-1-black.vercel.app](https://sprint-1-black.vercel.app/)
- **Demo Video:** [Inserted video link here](https://drive.google.com/file/d/1r4BjzBTeCGHkE9T9ZS16zxL1Su5LBaVT/view)

## 📸 Screenshot

![Prodesk IT Landing Page Screenshot]<img width="1896" height="1082" alt="Screenshot 2026-07-13 173504" src="https://github.com/user-attachments/assets/de7a4f25-7d16-4120-8f11-77bb1c0f5836" />


## Tech Stack
* **HTML5:** Structures the content, including a navigation bar, hero section, services grid, and a footer.
* **CSS3:** Handles styling with a focus on responsiveness and theming, utilizing CSS variables defined in a `:root` selector for colors, backgrounds, and shadows.
* **Vanilla JavaScript:** Manages interactive frontend elements, specifically a dark mode toggle and a mobile hamburger menu.

## Key Features
* **Theming (Dark/Light Mode):** The website supports a dynamic dark mode feature. The JavaScript checks `localStorage` for the saved theme upon DOM load and allows users to toggle between modes, appending or removing the `dark-mode` class on the document body. The CSS defines distinct background and text colors for the default light mode and the `.dark-mode` override.
* **Responsive Navigation:** The header contains a navigation menu that adapts to mobile devices. On viewports smaller than 768px, a hamburger menu button (☰) becomes visible. Clicking this button uses JavaScript to toggle an `active` class on the navigation links, transforming them into a dropdown menu.
* **Services Section:** A CSS Grid layout (`grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))`) displays three core service cards: SEO Optimization, Web Development, and Digital Marketing. These cards feature a hover effect that translates them upwards and applies a shadow.
* **Footer:** Contains a copyright notice for 2026 and inline SVG social media icons for Twitter, LinkedIn, and GitHub.

## File Structure
* `index.html`: Contains the main semantic structure, including the `#home` and `#services` sections.
* `style.css`: Contains all visual styling, media queries for mobile responsiveness, and custom CSS theme variables.
* `response.js`: Handles DOM manipulation via event listeners for the `#theme-toggle` button, `#mobile-menu-btn`, and includes demo alert functionality for a `#contact-form` submission.

## 🚀 Features

- **Zero-Dependency Architecture:** Built with pure HTML5, CSS3, and Vanilla JavaScript for maximum performance and full control over the codebase.
- **Dark/Light Mode Theme Toggle:** Integrated theme switching using CSS custom properties (`:root` variables) with user preference persistence via `localStorage`.
- **Fully Responsive Layout:** Utilizes CSS Flexbox and Grid, along with media queries, to ensure seamless adaptation across mobile, tablet, and desktop viewports.
- **Interactive UI Components:** Includes smooth scrolling, hover animations (like the About section image scale), and a mobile-friendly collapsing hamburger navigation menu.
- **Custom Branding:** Integrated custom logo scaling and professional layout structuring for a corporate aesthetic.
