# JJ Shop Solutions & Services — Official Website

![JJ Shop Banner](assets/img/icon-192.png)

**Live URL:** `https://jjshopsolutions.github.io` *(enabled once GitHub Pages is turned on)*

A professional business website for **JJ Shop Solutions & Services** — showcasing ready-made software products and custom development services for Philippine small businesses.

---

## 📄 Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero, dual CTAs, product spotlight, services strip |
| Products | `products.html` | App listings with pricing tiers |
| Services | `services.html` | Custom dev services, process, FAQ |
| About | `about.html` | Brand story, values, timeline |
| Contact | `contact.html` | Inquiry form via Formspree |

---

## 🗂️ File Structure

```
website/
├── index.html
├── products.html
├── services.html
├── about.html
├── contact.html
└── assets/
    ├── style.css          ← Shared design system
    └── img/
        ├── logo.png       ← Official JJ Shop logo
        └── icon-192.png   ← Favicon / PWA icon
```

---

## 🚀 Deployment

This website is deployed via **GitHub Pages**.

### To Enable GitHub Pages:
1. Go to your repo: `github.com/jjshopsolutions/jjshopsolutions.github.io`
2. Click **Settings** → **Pages**
3. Under **Source**, select branch: `main`, folder: `/ (root)`
4. Click **Save**
5. Your site will be live at: `https://jjshopsolutions.github.io`

> ⚠️ Do NOT enable GitHub Pages until you are ready to go public.

---

## 📬 Contact Form Setup (Formspree)

The contact form uses [Formspree](https://formspree.io) to deliver submissions to your email.

### One-time Setup:
1. Go to [formspree.io](https://formspree.io) and sign up (free)
2. Click **New Form** → name it "JJ Shop Contact"
3. Copy your Form ID (e.g., `xabcdefg`)
4. Open `contact.html` and find this line:
   ```html
   <form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
5. Replace `YOUR_FORM_ID` with your actual Formspree ID

Submissions will be forwarded to: `jjshopsolutions04@gmail.com`

---

## 🎨 Design System

- **Colors:** Navy dark background (`#050d1a`), Gold accent (`#d4af37`)
- **Fonts:** Cinzel (headings) + Outfit (body) via Google Fonts
- **Style:** Glassmorphism, gradient gold text, floating particle animations
- **Responsive:** Mobile, tablet, and desktop friendly

---

## ✏️ How to Update Content

| What to Change | Where |
|---|---|
| Product pricing | `products.html` → `.tier-price` elements |
| Add a new product | `products.html` → duplicate a `.product-card` |
| Add a service | `services.html` → duplicate a `.svc-card` |
| Contact email | `contact.html` + `style.css` footer |
| Logo / branding | Replace `assets/img/logo.png` |

---

## 📌 Built With

- Pure HTML5 + CSS3 + Vanilla JavaScript
- Google Fonts (Cinzel, Outfit)
- Formspree (contact form backend)
- GitHub Pages (hosting)

---

© 2026 JJ Shop Solutions & Services. All rights reserved.
