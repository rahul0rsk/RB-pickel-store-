# # RB Pickles — Web Storefront
A single-page e-commerce storefront for authentic homemade Indian pickles, podis, masala powders, and traditional snacks. Built with clean vanilla JavaScript, HTML5, and styled using Tailwind CSS.
---
## Features
* **Dynamic Product Catalog & Filtering:** 35+ items categorized across Pickles, Podis, Powders, Snacks, and Pappads with instant category switching.
* **Weight-Based Dynamic Pricing:** Selectable quantities (e.g., 250g, 500g, 1kg) with real-time price updates per item.
* **Persistent Cart:** Slide-out drawer with quantity modifiers, live totals, and automatic sync via browser `localStorage`.
* **WhatsApp Checkout:** Generates itemized order summaries and dispatches directly via a WhatsApp chat URL.
* **Interactive UI:**
  * Auto-scrolling, touch-draggable product carousel with 3D tilt effects on hover.
  * Live search modal with instant title/category filtering.
  * Glassmorphism navigation bar with responsive mobile menu toggle.
  * Intersection-observer scroll reveal animations.
* **Informational Modals:** Popups for editorial journal stories, return policies, shipping terms, and FAQs.
* **Newsletter Lead Capture:** Subscription form ready for EmailJS integration with consent capture and local backup.
---
## Tech Stack

| Layer | Technologies Used |
| :--- | :--- |
| **Markup & Structure** | Semantic HTML5 |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) (CDN runtime), Custom CSS (Animations, SVG Noise Filter) |
| **Typography** | Google Fonts (*Playfair Display*, *DM Sans*) |
| **Icons** | [Iconify](https://iconify.design/) (`mdi` material design set) |
| **Scripting** | Vanilla JavaScript (ES6+) |
| **Third-Party Integrations** | [EmailJS](https://www.emailjs.com/) for email automation, WhatsApp Click-to-Chat API |

---
## Project Structure
```text
.
├── index.html        # Complete single-file application (Markup, CSS, and JS)
└── README.md         # Project documentation-
