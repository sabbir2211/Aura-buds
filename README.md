# Aura Buds | Next-Gen 3D Landing Page

A high-end, immersive landing page for the fictional **Aura Buds**, featuring a real-time 3D environment, smooth scroll-driven animations, and a modern glassmorphism design language.

![Design Language](https://img.shields.io/badge/Design-Glassmorphism-blue)
![Tech Stack](https://img.shields.io/badge/Tech-Three.js%20%7C%20GSAP%20%7C%20Tailwind-green)
![Responsiveness](https://img.shields.io/badge/Mobile-Friendly-brightgreen)

---

## Key Features

* **3D Interactive Scene**: Powered by **Three.js**, featuring a procedurally generated earbud model with realistic physical materials (metallic, clear-coat, and matte).
* **Scroll-Triggered Storytelling**: Using **GSAP (GreenSock)**, the 3D model gracefully glides and rotates into position as the user scrolls through product features.
* **Glassmorphic UI**: High-end frosted glass effects created with Tailwind CSS and backdrop-filter blurs.
* **Performance Focused**: Optimized 3D rendering with hardware-accelerated animations and responsive viewport handling.
* **Zero Dependencies**: Everything is contained in a single fileâ€”just open `index.html` in your browser.

---

## Tech Stack

-   **Three.js**: For the WebGL 3D rendering and scene management.
-   **GSAP & ScrollTrigger**: For the complex, time-linked scroll animations.
-   **Tailwind CSS**: For the responsive layout, typography, and glassmorphism styling.
-   **HTML5/JavaScript**: Core structure and logic.

---

## Quick Start

1.  **Clone the project** or copy the `index.html` source code.
2.  **Open the file**: Double-click `index.html` to view it in any modern web browser.
3.  **No Server Required**: Because it uses CDN-hosted libraries, you can run it directly from your local filesystem (though a local server like Live Server is recommended for best performance).

---

## Component Breakdown

### 1. The Hero Section
Captures attention with a bold, high-contrast headline and a 360Â° floating view of the product.

### 2. Feature: Hybrid ANC
As you scroll, the earbud moves to the right, highlighting the sleek industrial design while technical specs appear in a blurred glass card.

### 3. Feature: Battery Life
The model rotates to showcase the charging interface and internal components, paired with a grid-based feature layout.

### 4. Call to Action
A cinematic zoom-in effect on the 3D model leads the user to a sleek email capture form.

---

## Customization

To modify the look and feel:

* **Colors**: Search for `0x111111` (Earbud Body) or `0x0066ff` (Accent Light) in the `<script>` tag to change the brand palette.
* **Animations**: Adjust the `scrub: 1` values in the GSAP section to make the scroll transition smoother or more immediate.
* **Materials**: Tweak `metalness` and `roughness` in the `MeshPhysicalMaterial` section to change the product's finish from matte to high-gloss chrome.

---

## License

This project is licensed under the MIT License - feel free to use it for your own product launches or portfolios!

---

*Designed with â¤ï¸ for Aura Audio Labs.*
