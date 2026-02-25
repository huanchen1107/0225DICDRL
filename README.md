# Huan Chen — Personal Web Page

A single-page personal portfolio website for **Huan Chen**, styled after the modern dark aesthetic of the [Hostinger Adelina template](https://builder.hostinger.com/templates?preview=adelina&hideRating=1).

## 🌐 Live Preview

Open `index.html` in any modern browser to view the page locally.

---

## ✨ Features

- **Dynamic Live Clock** — Displays the current local time, updating every second inside a floating glassmorphism badge
- **Fully Responsive (RWD)** — Fluid layouts across all screen sizes: mobile (xs/sm), tablet (md), and desktop (lg) using `clamp()` and four media query breakpoints
- **Parallax Mouse Effect** — Subtle 3D depth as you move your cursor (automatically disabled on touch devices)
- **Premium Dark Design** — Deep black background with vibrant electric purple accents
- **Layered Typography** — Three font styles creating visual depth:
  - `Syne ExtraBold` — Ultra-chunky display font for the hero name
  - `Playfair Display Italic` — Elegant cursive overlay for contrast
  - `Inter` — Clean sans-serif for UI labels and metadata
- **Animated Entry** — Staggered slide-up animations on page load
- **Glassmorphism UI** — Frosted-glass time badge with hover glow effect
- **Accessibility** — Respects `prefers-reduced-motion` system setting

---

## 📐 Responsive Breakpoints

| Breakpoint | Range         | Behavior |
|------------|---------------|----------|
| `xs`       | < 480px       | Compact header, centered time badge, enlarged font scale |
| `sm`       | 480–767px     | Large phone layout, badge anchored bottom-right |
| `md`       | 768–1023px    | Tablet layout with adjusted spacing and sizing |
| `lg`       | ≥ 1024px      | Full desktop experience (default) |

All font sizes and spacings use **CSS `clamp()`** for smooth, continuous scaling between breakpoints — no sudden jumps.

---

## 🗂️ File Structure

```
L1/
├── index.html   # Semantic page structure
├── style.css    # RWD styles: fluid type, layout, animations, glassmorphism
├── app.js       # Live clock logic + mouse parallax effect
└── README.md    # This file
```

---

## 🎨 Design System

| Element        | Value                        |
|----------------|------------------------------|
| Background     | `#030303` (Near Black)       |
| Primary Text   | `#FFFFFF` (White)            |
| Accent Color   | `#A358FF` (Electric Purple)  |
| Display Font   | Syne ExtraBold               |
| Script Font    | Playfair Display Italic      |
| UI Font        | Inter                        |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic page structure
- **Vanilla CSS3** — Custom properties, `clamp()`, keyframe animations, `backdrop-filter`, RWD media queries
- **Vanilla JavaScript** — No frameworks or build tools required

---

## 🚀 Getting Started

No build step required. Simply open the file in a browser:

```bash
# Clone the repository
git clone https://github.com/huanchen1107/0225DICDRL.git

# Open in browser
start index.html   # Windows
open index.html    # macOS
```

---

*Built with ❤️ — inspired by the Hostinger Adelina template.*
