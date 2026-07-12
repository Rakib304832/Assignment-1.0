# 🚀 DevConf 2026 — Conference Landing Page

A sleek, fully responsive landing page built for **DevConf 2026**, a premier developer conference bringing together engineers, founders, and builders for three days of talks, workshops, and networking.

![Status](https://img.shields.io/badge/status-active-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## ✨ Overview

This project is a single-page conference website designed to convert visitors into registered attendees. It combines a bold hero section, a clean speaker showcase, transparent pricing tiers, and an FAQ section — all wrapped in a modern, minimal aesthetic.

**Live sections include:**

| Section | Purpose |
|---|---|
| 🧭 Navbar | Sticky navigation with quick links + primary CTA |
| 🎯 Hero | Eye-catching banner with headline & registration button |
| 🎤 Speakers | Grid showcase of featured speakers with role tags |
| 💳 Pricing | Three-tier ticket plans (Standard / Pro / Team) |
| ❓ FAQ | Expandable accordion answering common questions |
| 🦶 Footer | Branding, social links, and copyright |

---

## 🖥️ Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom styling with Flexbox & CSS Grid (no frameworks, no dependencies)
- **Fonts** — `Playfair Display` for headings, `Inter` for body text

No build tools, no npm install, no frameworks — just open and go.

---

## 📁 Project Structure

```
devconf-2026/
├── index.html          # Main page markup
├── style.css            # All styling (layout, colors, typography)
└── assets/
    ├── logo.png              # Main navbar logo
    ├── logo-mini.png          # Compact logo mark
    ├── footer-logo.png        # Footer branding logo
    ├── banner.jpg             # Hero section background image
    ├── andrej.png             # Speaker photo — Andrej Karpathy
    ├── demis.png              # Speaker photo — Demis Hassabis
    ├── gary.png                # Speaker photo — Gary Marcus
    └── mustafa.png            # Speaker photo — Mustafa Suleyman
```

> ⚠️ **Note:** `index.html` references images via `./assets/...`. Make sure all image files are placed inside an `assets/` folder alongside `index.html` and `style.css` for the page to render correctly.

---

## 🎤 Featured Speakers

| Speaker | Focus Area | Role |
|---|---|---|
| Andrej Karpathy | AI / ML | Pretraining Team, Anthropic |
| Demis Hassabis | Cloud & DevOps | Co-founder & CEO, Google DeepMind |
| Gary Marcus | Frontend | Staff Engineer, Vercel |
| Mustafa Suleyman | Security | CEO of Microsoft AI |

---

## 💳 Ticket Tiers

| Plan | Price | Highlights |
|---|---|---|
| **Standard** | $499 | Full 3-day access, 48 talks, 2 workshops, swag bag |
| **Pro** ⭐ | $799 | Everything in Standard + speaker meet & greet, VIP dinner, lifetime recordings, 1:1 mentorship |
| **Team** | $5,999 | Up to 10 seats, dedicated lounge, private workshop booking, logo on event page |

---

## 🚀 Getting Started

1. **Clone or download** this repository.
2. Make sure the folder structure matches the layout above (images inside `assets/`).
3. Open `index.html` directly in your browser — no server required.

```bash
# Optional: run a local server for a smoother dev experience
npx serve .
```

---

## 🎨 Customization

- **Colors & branding** — update the primary blue (`#2b28de`) in `style.css` to match your brand.
- **Speakers** — swap images/text inside `.speaker-card` blocks in `index.html`.
- **Pricing** — edit the `.purchasing-card` and `.Pro-purchasing-card` sections to adjust plans and pricing.
- **FAQ** — add or remove `<details class="faq-item">` blocks; the accordion behavior works automatically via native HTML.

---

## 🐛 Known Issues / TODO

- [ ] Fix minor typos in FAQ copy (e.g. "rgister" → "register", "not-rfundateable" → "non-refundable")
- [ ] Update placeholder contact email/link in the "Contact Us" button
- [ ] Add a real `Tracks` page (currently duplicated nav link)
- [ ] Improve mobile responsiveness for pricing cards on very small screens

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ for developers, by developers.</p>
