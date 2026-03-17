# Raaya Social 🎬

> A modern, fully responsive landing page for a short-form video content agency — built with pure HTML & CSS.

![Raaya Social](https://img.shields.io/badge/Raaya-Social-A657E7?style=for-the-badge&logo=youtube&logoColor=white)

---

## 🌐 Live Demo

**[raaya-social.vercel.app](https://raaya-social-theta.vercel.app/)**

---

## 📖 Project Overview

**Raaya Social** is a static marketing landing page for a short-form video content agency. Built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no build tools.

**What it does:**
The page markets a subscription-based service where businesses get short-form video content (Reels, TikToks, YouTube Shorts) for a flat monthly rate starting at $99. It walks visitors through the value proposition, showcases sample work, displays client reviews, and ends with a contact form.

**Tech choices:**
Pure HTML/CSS was the right call here — it's a single marketing page that needs fast load times and easy Vercel deployment. CSS Grid and Flexbox handle all layouts. Vanilla JS covers just two things: the hamburger menu toggle and video hover play/pause.

**Key design decisions:**
- Purple `#A657E7` as the primary accent color — buttons, hovers, gradients, borders
- `#F5F5F5` alternating section backgrounds to create visual separation without hard borders
- Every interactive element (cards, nav links, buttons, FAQ items) has a consistent hover pattern — lift + purple border + shadow
- Three breakpoints (1024px, 768px, 480px) cover tablet and mobile, with the hamburger menu kicking in at 768px

**Structure:**
One `index.html`, one `styles/index.css`, one `javascript/index.js`, and an `assets/` folder with all images. Everything deploys as-is to Vercel with zero configuration.

---

## ✨ Features

- **Fully Responsive** — optimized for desktop, tablet (1024px), and mobile (768px / 480px)
- **Hamburger Menu** — animated 3-line → X toggle with smooth dropdown on mobile
- **Hover Effects** — cards, nav links, buttons, FAQ items all have smooth purple-themed hover transitions
- **Video Cards** — `<video>` elements with poster thumbnails, play-on-hover, and play button overlay
- **Interactive Service Cards** — radio-style selection with active state
- **FAQ Accordion** — expandable questions with icon toggle
- **Contact Form** — email, phone, textarea with focus states
- **Google Fonts** — Poppins, Nunito, Raleway, Lato

---

## 📁 Project Structure

```
raaya-social/
├── index.html
├── styles/
│   └── index.css
├── javascript/
│   └── index.js
└── assets/
    ├── Logo.png
    ├── Banner .png
    ├── advertisments/
    ├── clientsStories/
    ├── social icon/
    └── videos/
```

---

## 📐 Sections

| Section | Description |
|---|---|
| **Nav** | Logo, links, Login + Book a Demo buttons, hamburger on mobile |
| **Banner** | Hero text, gradient headings, dual banner images, social icons |
| **Clients** | 50+ client count with logo strip |
| **Creative Services** | What We Provide + pricing plan cards |
| **Raw Video** | 3-column process cards with hover lift |
| **Social Channels** | 3-column grid cards with hover |
| **Video Gallery** | 4-column video cards with play overlay |
| **Short Form** | Split layout image + text section |
| **Client Stories** | 6-column photo grid |
| **Reviews** | 2-col + 3-col review cards with hover |
| **FAQ** | Expandable questions with hover |
| **Footer** | 4-column layout with contact form + copyright |

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 1024px` | Full desktop layout |
| `≤ 1024px` | Reduced padding, adjusted grids |
| `≤ 768px` | Hamburger menu, stacked sections |
| `≤ 480px` | Single column, scaled typography |

---

## 🚀 Getting Started

No build tools needed — just open in a browser.

```bash
# Clone the repo
git clone https://github.com/your-username/raaya-social.git

# Open in browser
open index.html
```

Or drag `index.html` into any browser.

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3** — Flexbox, CSS Grid, custom transitions
- **Vanilla JavaScript** — hamburger toggle, video hover play/pause
- **Google Fonts**
- **Vercel** — deployment

---

## 🎨 Color Palette

| Color | Hex | Usage |
|---|---|---|
| Purple | `#A657E7` | Primary accent, buttons, hover |
| Dark Purple | `#2B034D` | Gradient, badges |
| Light Purple | `#B564F7` | Gradient start |
| Gray | `#344054` | Body text |
| Dark | `#101828` | Headings |
| Background | `#F5F5F5` | Section backgrounds |

---

## 📦 Deployment

Deployed on **Vercel** via GitHub integration.

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

---

## 📄 License

© 2024 Raaya Social. All rights reserved.
