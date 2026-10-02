# Zero-Touch Legal Intake Engine

A cinematic, interactive frontend presentation designed to pitch an automated legal intake pipeline to executive management. 

This project abandons standard presentation formats in favor of a "Scrollytelling" experience. It utilizes the premium **Dala Void** design system, high-end GSAP scroll physics, and interactive data visualization to prove the technical competence of an n8n-to-Filevine automation pipeline.

---

## 🚀 Project Overview

The goal of this presentation is to visually explain a complex backend API architecture (Email parsing -> AI Extraction -> Filevine Provisioning -> Notion Sync) using zero technical jargon. It translates backend operations into a buttery-smooth, interactive pipeline that executives can physically "scroll through."

### Key Features
*   **The Dala Void Aesthetic:** A deep, saturated dark mode utilizing pure black (`#000000`) backgrounds, fixed ambient glowing orbs (`blur-[120px]`), and frosted glassmorphism overlays.
*   **GSAP Scrollytelling:** A 4-step pipeline timeline perfectly synced to the user's scrollbar. As the user scrolls, the active nodes ignite with `electricIris` glows while the descriptive text swaps using slide-and-blur physics.
*   **Zero-Hallucination Demo:** A split-screen interaction that simulates an AI processing a blurry unstructured police report into structured JSON in real-time.
*   **3D Hover Physics:** Business impact cards that calculate cursor position to dynamically tilt on the X and Y axes while dragging a simulated radial glare across the card surface.
*   **Production Ready:** Fully hardened with SEO metadata, Open Graph social preview tags, inline SVG favicons, mobile responsiveness, and cookie consent compliance.

---

## 🛠️ Technology & Languages

This project was built to be completely serverless and dependency-free for instant, zero-build deployment.

*   **Markup:** HTML5
*   **Styling:** Tailwind CSS (via CDN with custom config tokens)
*   **Animation Engine:** GSAP (GreenSock Animation Platform) + ScrollTrigger
*   **Interactivity:** Vanilla JavaScript (ES6)
*   **Typography:** Plus Jakarta Sans (Display) & Inter (Body)

---

## 📂 Organization & Architecture

```text
├── index.html       # The core scrollytelling presentation and GSAP logic
├── 404.html         # Custom Dala-themed error page with ambient void glows
├── robots.txt       # SEO crawler indexing rules
└── sitemap.xml      # Root sitemap for search engines
```

---

## 🎯 Area of Usage & Applications

This frontend architecture is designed for:
1.  **Executive Buy-In:** Pitching highly technical backend workflows (like n8n, Zapier, or Make.com automations) to non-technical stakeholders or law firm partners.
2.  **Product Landing Pages:** Serving as a high-conversion marketing page for LegalTech SaaS products.
3.  **Interactive Portfolios:** Showcasing a developer's ability to combine complex API architecture with world-class, premium UI/UX.

---

## 💻 Usage & Deployment

### Local Development
Because the project uses CDNs for its libraries, no package manager (`npm` or `yarn`) is required. 
Simply double-click `index.html` to open it in any modern web browser.

### Global Deployment
This project is optimized for static hosting platforms. It requires **zero build steps**.

1. **Netlify Drop (Fastest):** Drag and drop the project folder into [Netlify Drop](https://app.netlify.com/drop) to receive an instant live URL.
2. **Vercel / GitHub Pages:** Push this repository to GitHub and connect it to Vercel. Vercel will instantly detect the `index.html` and deploy it to a global CDN, automatically forcing HTTPS and optimizing page load speeds.

---

## 🎨 Design Tokens (Dala Void)

For developers wishing to extend this project, the core Tailwind configuration relies on the following custom tokens:
*   `void`: `#000000` (Backgrounds)
*   `boneWhite`: `#ffffff` (Primary text)
*   `electricIris`: `#8052ff` (Primary actions, glows, active states)
*   `saffronSpark`: `#ffb829` (Warnings, badges)
*   `deepVerdant`: `#15846e` (Ambient background gradients)
