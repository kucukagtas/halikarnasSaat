# ⌚ Halikarnas Saat — E-Commerce & Luxury Watch Boutique

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live_Demo-kucukagtas.github.io%2FhalikarnasSaat-519d79?style=for-the-badge&logo=githubpages&logoColor=white)](https://kucukagtas.github.io/halikarnasSaat/)
[![Language: Turkish](https://img.shields.io/badge/Language-Turkish_%28T%C3%BCrk%C3%A7e%29-E30A17?style=for-the-badge&logo=googletranslate&logoColor=white)](https://kucukagtas.github.io/halikarnasSaat/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5.3.8-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome_7-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)](https://fontawesome.com/)

<p align="center">
  <strong>A modern, responsive e-commerce storefront for classic, luxury, and automatic timepieces — published in Turkish.</strong>
</p>

[🌐 Visit Live Website](https://kucukagtas.github.io/halikarnasSaat/) • [✨ Key Features](#-key-features) • [🛠️ Tech Stack](#️-tech-stack) • [📁 Project Structure](#-project-structure) • [🚀 Getting Started](#-getting-started) • [🌐 Deployment](#-deployment) • [📄 License](#-license)

---

</div>

## 📖 Overview

**Halikarnas Saat** is an elegant, multi-page e-commerce web platform designed for showcasing and retailing fine wristwatches, chronographs, automatic mechanisms, and wearable technology. The project combines modern visual design, intuitive product browsing, responsive layouts, and interactive shopping cart functionality.

🇹🇷 **Dil Notu:** Web sitesi arayüzü, gezinme menüleri, ürün katalogları, teknik özellik tabloları ve sepet adımları tamamen **Türkçe** olarak hazırlanmıştır (*"Halikarnas Saat - Kaliteli ve Güvenilir Saatler"*).

Built with semantic **HTML5**, **Bootstrap 5.3.8**, custom **CSS3**, and vanilla **JavaScript (ES6+)**, the platform ensures fluid responsiveness across all device form factors — from 320px ultra-compact smartphone screens to high-resolution desktop monitors.

🔗 **Live Deployment:** [https://kucukagtas.github.io/halikarnasSaat/](https://kucukagtas.github.io/halikarnasSaat/)

---

## ✨ Key Features

- **📱 Pixel-Perfect Responsive Layout:** Seamlessly scales from 320px mobile screens (iPhone SE) up to 4K displays using Bootstrap's responsive grid, clamp-based typography scaling, and tailored CSS media queries.
- **🧭 Multi-Category Mega Dropdown Navigation:**
  - Responsive navbar with collapsible toggle for mobile devices.
  - Six rich category dropdown menus:
    - **Erkek Saat:** Klasik Saatler, Spor & Kronograf, Otomatik Modeller, Dalış Saatleri (Diver)
    - **Kadın Saat:** Klasik & Şık, Rose Gold Modeller, Deri Kordonlu, Taşlı & Mücevher Saatler
    - **Mekanizmalar:** Otomatik Mekanizma, Kurmalı (Manuel), Quartz (Pilli), Solar & Kinetik
    - **Giyilebilir Teknoloji:** Akıllı Saatler, Spor & Nabız Takip, Hibrit Modeller, Akıllı Bileklikler
    - **Özel Saatler:** Sınırlı Üretim (Limited Edition), Vintage & Retro Koleksiyon, İsviçre Yapımı (Swiss Made), Titanyum Kasa Saatler
    - **Markalar:** Citizen, Tissot, Hamilton, Casio
- **🏠 Dynamic Homepage (`index.html`):**
  - **Top Bar:** Search input, branding with clock icon, and quick-action user buttons (*Hesabım*, *Listem*, *Sepetim*).
  - **Hero Slider (`#slider`):** Multi-slide carousel banner showcasing flagship watches with auto-rotation controls.
  - **İndirim Vitrini (Product Showcase Grid):** 8 featured timepieces in a balanced responsive grid (`row-cols-2 row-cols-md-3 row-cols-lg-4`) with interactive wishlist buttons, discount badges, and price strike-throughs.
- **🔍 Interactive Product Details (`details.html`):**
  - **FsLightbox Gallery:** High-resolution zoomable image lightbox triggered on click.
  - **Multi-Angle Thumbnails:** 4 thumbnail angles with responsive sizing and zoom preview.
  - **Product Specifications Table:** Clean definition list (`dl.row`) covering mechanism, case diameter, sapphire crystal type, water resistance (10 Bar), and 316L stainless steel build.
  - **Variation Selectors:** Dropdown controls for case diameter (40mm / 35mm) and dial color (Sunray Blue, Emerald Green, Classic Black).
  - **Call to Action:** Prominent *"Sepete Ekle"* and *"Listeme Ekle"* buttons adapting smoothly from full-width mobile stacks to inline desktop layouts.
  - **Similar Products Recommendation:** Dynamic 4-item grid highlighting related watch models.
- **🛒 Complete Shopping Cart (`shopping-cart.html`):**
  - **Order Items List:** Product thumbnails, titles, color/size specs, quantity selectors (1-3 Adet), and quick-remove buttons.
  - **Free Shipping Incentive:** Interactive alert notifying users of free shipping qualification.
  - **Cart Action Controls:** Responsive footer buttons for continuing shopping or clearing the cart.
  - **Order Summary Card (`sticky-lg-top`):** Subtotal, shipping, VAT breakdown, total calculation, and direct checkout CTA.
  - **Trust & Security Badges:** 256-Bit SSL encryption, 14-day returns (*14 Gün İade*), and 100% original product guarantee (*%100 Orijinal*).
- **🔝 Floating Scroll-to-Top Button:** Dynamic floating button (`#btnScrollTop`) that fades in smoothly after scrolling 280px down the page and provides instant smooth scrolling back to the top.
- **🎨 Curated Luxury Brand Palette:**
  - Primary Forest Emerald: `#519d79`
  - Dark Emerald (Hover/Active): `#3f7b5f`
  - Light Emerald Surface: `#eef7f2`
  - Accent Warning Gold: `#ffc107`
  - Deep Neutral Slate: `#2b3035`
- **⚡ High Performance & Lightweight Assets:** Modern AVIF image formats, zero bloated runtime frameworks, zero external build dependencies.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic web structure across all pages (`header`, `nav`, `main`, `article`, `footer`, forms, meta tags) |
| **CSS3** | Custom design system (`style.css`), design tokens, fluid typography (`clamp()`), and responsive media queries |
| **Bootstrap 5.3.8** | Responsive layout grid, dropdown collapse, carousel slider, and UI components |
| **JavaScript (ES6+)** | Dynamic scroll-to-top interaction and DOM events (`main.js`) |
| **FsLightbox** | Vanilla JavaScript modal lightbox library for image zooming (`fslightbox.js`) |
| **Font Awesome 7** | Vector icons for clocks, user profiles, shopping carts, stars, hearts, and social media links |
| **Google Fonts (Inter)** | Modern, clean typography tailored for digital readability |
| **GitHub Pages** | Continuous deployment, automated Git integration, and global CDN hosting |

---

## 📁 Project Structure

```text
halikarnasSaat/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions workflow for automatic GitHub Pages deployment
├── bootstrap-5.3.8/
│   ├── css/
│   │   └── bootstrap.css       # Bootstrap 5.3.8 core stylesheet
│   └── js/
│       └── bootstrap.bundle.js # Bootstrap 5.3.8 JavaScript bundle (with Popper)
├── css/
│   └── style.css               # Custom styles, design tokens & responsive media queries
├── img/
│   ├── 1.avif                  # Tissot PRX 40mm Automatic Powermatic 80
│   ├── 2.avif                  # Citizen Tsuyosa NJ0150-81E
│   ├── 3.avif                  # Tutima M2 Coastline 6150-02
│   ├── 4.avif                  # Hamilton Khaki Field Auto 38mm
│   ├── 5.avif                  # Tissot SRV 30mm
│   ├── 6.avif                  # Doxa SUB 300ß Caribbean
│   ├── 7.avif                  # Longines Hydroconquest
│   ├── 8.avif                  # Casio G-Shock GBX-H5600-2DR
│   ├── slider-1.avif           # Hero Carousel Slide 1
│   ├── slider-2.avif           # Hero Carousel Slide 2
│   ├── slider-3.avif           # Hero Carousel Slide 3
│   ├── tissot2.avif            # Product Detail Thumbnail Angle 2
│   ├── tissot3.avif            # Product Detail Thumbnail Angle 3
│   └── tissot4.avif            # Product Detail Thumbnail Angle 4
├── js/
│   ├── fslightbox.js           # FsLightbox lightbox & modal zoom library
│   └── main.js                 # Floating scroll-to-top interaction
├── .gitignore                  # Git ignore rules (.DS_Store, IDE files)
├── details.html                # Product detail page with interactive gallery & specs
├── index.html                  # Store homepage with hero slider & discount showcase
├── LICENSE                     # MIT License
├── README.md                   # Comprehensive project documentation
└── shopping-cart.html          # Shopping cart with summary & trust badges
```

---

## 🚀 Getting Started

To view or develop this project locally on your machine:

### 1. Clone the Repository

```bash
git clone https://github.com/kucukagtas/halikarnasSaat.git
```

### 2. Navigate to the Project Directory

```bash
cd halikarnasSaat
```

### 3. Run Locally

Since this is a pure static web application, no compilation or build steps are required:

* **Directly in Browser:** Double-click `index.html` or drag it into any modern web browser (Chrome, Safari, Firefox, Edge).
* **VS Code Live Server:** Right-click `index.html` and select **"Open with Live Server"**.
* **Via Node.js `serve`:**
  ```bash
  npx serve .
  ```
* **Via Python HTTP Server:**
  ```bash
  python3 -m http.server 8000
  ```

---

## 🌐 Deployment

The live version of **Halikarnas Saat** is deployed on **GitHub Pages**:

👉 **[https://kucukagtas.github.io/halikarnasSaat/](https://kucukagtas.github.io/halikarnasSaat/)**

### Deployment Steps:

1. **Automatic Deployment via GitHub Actions (Recommended):**
   - The included workflow file [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) triggers automatically on every push to the `main` branch.
   - In your GitHub repository:
     1. Go to **Settings** → **Pages**.
     2. Under **Build and deployment** → **Source**, select **GitHub Actions**.
     3. Push changes to `main`; the workflow will build and publish your site in seconds.

2. **Manual Branch Deployment (Alternative):**
   - In your GitHub repository:
     1. Go to **Settings** → **Pages**.
     2. Under **Build and deployment** → **Source**, select **Deploy from a branch**.
     3. Choose **Branch: `main`** and **Folder: `/(root)`**.
     4. Click **Save**.

---

## 📄 License

This project is open-source and licensed under the [MIT License](LICENSE) — see the [LICENSE](LICENSE) file for details.

Copyright © 2026 [Muhammed Küçükağtaş](https://github.com/kucukagtas). All rights reserved.
