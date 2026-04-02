# WASABEE - Oriental Cuisine · Kolkata

> *A cinematic, motion-rich restaurant website built for a premium dining experience.*

---

## 🎯 The Vision

Wasabee is not just a restaurant - it's an experience. The website reflects that identity completely. Inspired by the legendary **[Sushi Jiro](https://www.sushi-jiro.jp)** website - one of the most beautiful and minimal restaurant sites in the world - the goal was to build something that feels:

- **Cinematic** - every scroll feels like a film sequence
- **Minimal** - nothing unnecessary, every element earns its place
- **Artwork** - a unified "digital artwork" aesthetic using film noise, frosted glass, and custom interactive cursor
- **Authentic** - rooted in Oriental visual language with Noto Sans JP accents and a sharp, uniform geometric Sans-Serif typography system

The client's brand identity is deeply tied to **red** - a bold, high-contrast palette drawn from traditional Japanese art. This influenced the decision to use a 100% uniform dark theme (`#0a0a0a`) with brand-red accents and cream typography.

---

## 🌐 Live Links

| Platform | Link |
|----------|------|
| **Zomato** | [zoma.to/r/22188](http://zoma.to/r/22188) |
| **Swiggy** | [swiggy.com/.../wasabee](https://www.swiggy.com/city/kolkata/wasabee-kalikapur-ruby-area-rest33209) |
| **Google Maps** | [maps.google](https://share.google/Fpbui7WFzKV8RP00X) |
| **Google Rating** | ⭐ 4.5 / 5 |

---

## 🏗️ Project Architecture

```
wasabee/
├── index.html        # Single-page application - all sections
├── styles.css        # Full design system + luxury components (~2350 lines)
├── script.js         # Interactive cursor, scroll progress, animations
└── images/
    ├── wasabee logo .svg       # Official Wasabee wordmark (SVG)
    ├── slide 1.jpg             # Hero Slider 1
    ├── slide 2.jpg             # Hero Slider 2
    ├── slide. 3.jpg            # Hero Slider 3 (Instagram Grid source)
    ├── whatsapp-logo.svg       # Official WhatsApp brand SVG
    ├── google-maps-2020-icon.svg # Official Google Maps pin SVG
    ├── zomato-1.svg            # Official Zomato brand SVG
    └── swiggy-1.svg            # Official Swiggy brand SVG
```

---

## 🎨 Design System

### Color Palette
| Token | Value | Usage |
|-------|-------|-------|
| `--color-bg` | `#0a0a0a` | Primary background (Deep Black) |
| `--color-surface` | `#141414` | Cards, surfaces |
| `--color-red` | `#c62828` | Primary brand accent (Stars, Progress, Buttons) |
| `--color-cream` | `#f5f0e8` | Primary text (Off-white) |
| `--color-text-dim` | `#5a5650` | Tertiary descriptions |

### Typography (100% Uniform Sans-Serif)
| Font | Role | Source |
|------|------|--------|
| **Inter** | Global headings, body, UI | Google Fonts |
| **Noto Sans JP** | Japanese Kanji accents | Google Fonts |

*Policy: The UI is strictly punctuation-flat. Zero em-dashes and zero hyphens in visible text content to maintain a modern, clean agency-grade aesthetic.*

---

## ✨ Cinematic Features

### 1. Interactive Custom Cursor
A high-performance, 3D-transformed cursor that follows the mouse with a slight easing effect.
- **Magnetic reaction**: Expands and blurs when hovering over interactive elements (buttons, menu items, gallery).

### 2. Pro Frosted Glass Navigation
Fixed header with `backdrop-filter: blur(20px)` and semi-translucent background. Creates a premium layer effect as content scrolls underneath.

### 3. Infinite Reviews Marquee
A horizontally scrolling ticker of real Google Maps reviews, styled as minimal dark cards with brand-red integration.

### 4. "Our World" Instagram Feed
A visual 2x2 grid (mobile) and 4-item list (desktop) pulling from local high-res assets, integrated with social follow CTAs.

### 5. Molecular Pricing Alignment
All menu prices use `font-variant-numeric: tabular-nums` for perfect vertical alignment of digits.

---

## 📄 Page Sections

- `#hero`: Multi-slide cinematic slider with Ken Burns animation and logo reveal.
- `#about`: The Wasabee story with animated stat counters.
- `#menu`: 100+ items across 8 categories with an instant filtering system.
- `#gallery`: High-resolution masonry grid showcasing The Wasabee Identity.
- `#experience`: Editorial feature cards with directional hover interactions.
- `#our-world`: Live-style Instagram grid with direct follow links.
- `#order`: High-contrast ordering platform cards (Zomato, Swiggy, Google).
- `#reservation`: Minimalist CTA for table bookings.
- `#contact`: Location grid with dark-filtered embedded maps and operational hours.

---

## 🚀 Deployment

The site is built with **Pure HTML · CSS · JavaScript** - no frameworks, no dependencies.

### GitHub
Repository: [github.com/souvikdhua/wasabee-website](https://github.com/souvikdhua/wasabee-website)

### Netlify
Auto-deployed on every `git push` to the `main` branch.

---

## 👤 Credits

**Brand & Vision**: Wasabee Oriental Cuisine, Kolkata  
**Inspiration**: [sushi-jiro.jp](https://www.sushi-jiro.jp)  
**Development**: Digital artwork polish by Antigravity AI  

---

*"Good design is as little design as possible."* - Dieter Rams
