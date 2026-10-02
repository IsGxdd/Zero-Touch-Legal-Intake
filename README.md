# ⚖️ AI-Powered Legal Intake Automation: Interactive Pitch Deck

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Here-0071e3?style=for-the-badge)](https://stalwart-alfajores-bc2a9e.netlify.app/)
[![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20Tailwind%20%7C%20GSAP-111111?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Roadmap_Proposal-ffb829?style=for-the-badge)](#)

This repository contains the source code for an interactive, cinematic "scrollytelling" web presentation. It was engineered to pitch a **Zero-Touch Legal Intake Automation Engine** to the management team at a personal injury and property damage law firm.

## 📖 Project Overview

The objective of this presentation is to visually demonstrate the ROI and architectural flow of replacing manual legal data entry with an AI-driven n8n pipeline. 

Instead of a static PowerPoint, this project utilizes a custom **"Dala Void" design system**—featuring absolute black canvases, ambient glassmorphism, aggressive typography, and GSAP ScrollTrigger physics—to make the executives *feel* the speed, precision, and modernity of the proposed software.

## 🎯 Intention & Roadmap Strategy

This presentation serves as Step 1 in the automation deployment roadmap:
1. **The Pitch (Current Stage):** Secure stakeholder approval and demonstrate the precise technical architecture to management.
2. **The Ask:** Obtain authorization from the Filevine Tenant Admin to provision an Integration Service Account and generate a Personal Access Token (PAT).
3. **Sandbox Testing:** Connect the Filevine API to the n8n staging environment to test API cascade logic with dummy data.
4. **Live Deployment:** Connect the Outlook intake trigger to process historical, real-world Driver Exchanges and Crash Reports.

## 🏢 Area of Usage & Applications

*   **Industry:** Legal Tech, Personal Injury, Property Damage Claims.
*   **Operational Area:** Pre-claim verification, client intake, and data entry.
*   **Primary Application:** Transforming unstructured emails and OCR'd Police Reports into structured, perfectly mapped variables inside **Filevine (v2)** and **Notion** databases.

## 🛠️ Languages & Tech Stack

### 1. The Presentation Codebase (This Repository)
*   **HTML5 / JavaScript (ES6)**
*   **Tailwind CSS (v3 via CDN):** Customized with specific design tokens (Void `#000000`, Electric Iris `#8052ff`, Saffron Spark `#ffb829`).
*   **GSAP & ScrollTrigger:** For scroll-bound physics, pinned sections, and dynamic timeline scrubbing.
*   **Typography:** Google Fonts (`Plus Jakarta Sans` for display, `Inter` for technical body text).
*   **Hosting:** Netlify.

### 2. The Proposed Automation Engine
*   **n8n:** Workflow orchestration, webhook listeners, and HTTP routing.
*   **Google Gemini AI:** LLM parsing unstructured OCR data with strict "Zero-Hallucination" prompt guardrails.
*   **Filevine API (v2):** `POST /v2/Projects`, `POST /v2/Documents` (via S3 Presigned URLs), `PATCH /v2/Projects/{id}/Form`.
*   **Notion API:** Relational database synchronization for high-level team visibility.

## 📂 Project Organization & Structure

The single-page application is structured into 5 distinct narrative phases, tied to the user's scroll position:

```text
├── Hero Section             # The Hook: "Zero-Touch Intake" (< 60 Sec metric)
├── The Vision               # The current manual process vs. the automated future
├── The Pipeline (GSAP)      # Pinned Scrollytelling: Ingestion -> AI -> Provisioning -> Sync
├── Zero-Hallucination       # Split-screen UI demonstrating the strict "Pending" logic
├── Business Impact          # ROI (Data Integrity, Risk Mitigation, Scalability)
└── Action Required          # Footer Call-to-Action for Tenant Admin (PAT Generation)
```

## 📚 Purposed Documentation & References

*   [Filevine API v2 Documentation](https://developer.filevine.io/) - Core endpoints used for matter creation and form patching.
*   [n8n Documentation](https://docs.n8n.io/) - Node-based workflow automation logic.
*   [GSAP ScrollTrigger Docs](https://greensock.com/docs/v3/Plugins/ScrollTrigger) - Scrollytelling physics used in the presentation UI.

*Designed & Engineered for The Law Office of Raphael A. Sanchez.*
