# 📸 Lumora Studios

A modern, fully responsive photography studio website built with vanilla **HTML, CSS, and JavaScript**. Lumora Studios showcases a photography brand's services, portfolio, and contact information through a clean, elegant, single-page design with smooth scroll animations.

---

## 🌐 Live Preview

https://alishbaaazmat.github.io/Lumora-Studios-Website/


## ✨ Features

- **Fully Responsive Design** — Optimized layouts for desktop, tablet, and mobile screens using CSS media queries.
- **Animated Mobile Navigation** — A slide-in menu with an animated hamburger/close icon toggle.
- **Scroll Spy Navigation** — Active nav link automatically updates based on the section in view (powered by `IntersectionObserver`).
- **Scroll Reveal Animations** — Smooth fade/slide-in animations for the hero section using [ScrollReveal.js](https://scrollrevealjs.org/).
- **Dynamic Portfolio Grid** — A masonry-style image grid with hover overlays displaying category labels.
- **Services Showcase** — A clean, numbered list layout highlighting core photography services.
- **Contact Form Validation** — Client-side validation with user feedback via alerts, plus automatic form reset on submission.
- **Custom Iconography** — Icons powered by [RemixIcon](https://remixicon.com/).

---

## 🗂️ Project Structure

```
lumora-studios/
├── index.html          # Main HTML markup
├── style.css            # Stylesheet (responsive layout, theming, animations)
├── main.js               # JavaScript (navigation, scroll reveal, form handling)
└── assets/
    ├── white-logo.png
    ├── purple-logo.png
    ├── photography.jpg
    ├── portrait.jpg
    ├── wedding.jpg
    ├── event.jpg
    ├── fashion.jpg
    ├── portfolio-wedding.jpg
    ├── portfolio-portrait.jpg
    ├── portfolio-birthday.jpg
    ├── portfolio-fashion.jpg
    ├── portfolio-event.jpg
    └── portfolio-couple.jpg
```

---

## 📄 Sections Overview

| Section | Description |
|---|---|
| **Home** | Hero section with headline, call-to-action buttons, stats (sessions, clients, experience), and social links. |
| **Services** | Grid list of core offerings: Portrait, Wedding, Event, and Fashion & Editorial photography. |
| **Portfolio** | A responsive image gallery with hover overlays linking to categories like Weddings, Portraits, Birthdays, Fashion, Events, and Couples. |
| **About** | Brand story and studio statistics. |
| **Contact** | Contact details (email, LinkedIn) alongside a validated inquiry form. |

---

## 🛠️ Built With

- **HTML5** — Semantic markup
- **CSS3** — Custom properties (CSS variables), Flexbox, CSS Grid, media queries
- **JavaScript (Vanilla)** — DOM manipulation, event delegation, `IntersectionObserver` API
- **[ScrollReveal.js](https://scrollrevealjs.org/)** — Scroll-triggered animation library (via CDN)
- **[RemixIcon](https://remixicon.com/)** — Icon library (via CDN)
- **[Google Fonts](https://fonts.google.com/)** — Montserrat font family

---

## 🚀 Getting Started

No build tools or dependencies required — this is a static website.

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- (Optional) [VS Code](https://code.visualstudio.com/) with the **Live Server** extension for local development

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/alishbaaazmat/Lumora-Studios-Website.git
   ```
2. **Navigate into the project folder**
   ```bash
   cd Lumora-Studios
   ```
3. **Open the project**
   - Double-click `index.html` to open it directly in your browser, **or**
   - Use the Live Server extension in VS Code for hot-reloading during development.

---

## 📱 Responsiveness

The layout adapts across three primary breakpoints:

- **Desktop** (`width > 768px`) — Multi-column layouts, horizontal navigation bar, side-by-side hero/about/contact sections.
- **Mobile** (`width ≤ 768px`) — Collapsible hamburger navigation, stacked layouts, always-visible portfolio overlays, and adjusted typography/spacing.

---

## 👤 Author

**Alishba Azmat**

---

## 🙌 Acknowledgements

- [ScrollReveal.js](https://scrollrevealjs.org/) for scroll animations
- [RemixIcon](https://remixicon.com/) for the icon set
- [Google Fonts](https://fonts.google.com/specimen/Montserrat) for typography
