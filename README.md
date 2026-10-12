# CakeyTales — Haute Confectionery & Bespoke Cake Artistry

A production-ready personal branding and portfolio website for **CakeyTales**, an independent cake artist.

> **Context:** This is a personal brand website for a cake artist, **not** a commercial bakery or retail shop. There is no storefront, physical shop, commercial inventory, or conventional bakery menu. It is an editorial atelier showcase of the artist's identity, creations, philosophy, creative process, and custom cake commission enquiries.

---

## 🎨 Visual Identity & Design System

- **Palette:** Warm cream (`#FAF6F0`), Ivory (`#FFFDF9`), Pastel Blush Pink (`#FCECEF`), Strawberry Pink (`#E34A6F`), Butter Yellow (`#FDF1CE`), and Deep Chocolate Brown (`#2C1810`).
- **Typography:** Refined editorial serifs (*Cormorant Garamond* & *Playfair Display*) with bold strawberry-pink italic accents paired with modern sans-serif (*Plus Jakarta Sans*).
- **Art Direction:** Asymmetrical editorial compositions, tilted photographic frames, organic butter-yellow backdrops, floating pastry accents, and subtle ambient shadows.

---

## ✨ Features & Architecture

1. **Editorial Hero Section:** Softly rounded warm-cream composition, tilted artisanal cake photograph, butter-yellow circular backing, floating macaron cutouts, and featured creation badge (*The Rosewater Bloom*).
2. **Featured Creations Portfolio (10-Cake Catalogue):**
   - 10 bespoke works across *Wedding Cakes*, *Sculptural Cakes*, *Celebration Cakes*, and *Signature Designs*.
   - Instant client-side category filtering with smooth transitions.
   - Interactive commission dossier modals with medium, flavor, and occasion specs.
3. **Artist Story & Creative Philosophy:** Editorial split layout with artist at work, contrasting deep-chocolate panel, and core philosophy: *“Every cake is a little world of its own.”*
4. **Signature Project Case Study:** Mini editorial case study for *The Empress Whisper* with process photography and craftsmanship breakdown.
5. **Interactive 3D Centerpiece (Three.js):** Isolated WebGL 3D tier study with orbit drag, lighting, and ambient gold dust particles. Lazy-loaded on viewport entry.
6. **4-Stage Creative Process:** *Inspiration & Context → Concept & Architectural Design → Artisanal Craftsmanship → The Finished Creation*.
7. **Deep-Chocolate Artist Statement & Client Reflection:** Client appreciation note and atelier quality pillars.
8. **Commission Enquiries & Direct Channels:** Interactive custom enquiry form with direct redirects to **WhatsApp** and **Instagram**.

---

## 🛠️ Tech Stack

- **Framework:** [Astro](https://astro.build) (Static output, Cloudflare Pages compatible)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com) with custom design tokens
- **3D Graphics:** [Three.js](https://threejs.org) (Lazy-loaded via dynamic import)
- **Icons & Motion:** Semantic SVG & CSS keyframe animations (prefers-reduced-motion supported)

---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview
```
