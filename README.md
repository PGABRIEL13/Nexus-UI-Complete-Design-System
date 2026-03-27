# Nexus UI — Design System

> A production-ready component library built with pure HTML, CSS, and JavaScript. Zero dependencies. Zero frameworks.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## Overview

Nexus UI is a dark-first design system that provides a complete set of UI components for building modern web applications. Every component is crafted with CSS custom properties, enabling seamless theming without any build tools or dependencies.

## Components

| Component | Variants |
|-----------|----------|
| **Buttons** | Primary, Secondary, Danger, Ghost — SM / MD / LG |
| **Badges** | Purple, Pink, Green, Neutral — with dot indicator |
| **Cards** | Hover animations, icon slot, description |
| **Inputs** | Default, Focus, Error states with hints |
| **Toggles** | Animated checkbox switches |
| **Alerts** | Info, Success, Danger with left border accent |
| **Avatars** | Single + stacked group with overflow count |
| **Progress Bars** | Gradient fill, label, percentage display |
| **Modal** | Backdrop blur + spring scale animation |
| **Grid** | 8px spacing scale, CSS Grid utilities |

## Design Tokens

```css
--accent:  #7c6af7   /* Primary purple */
--accent2: #f76a8a   /* Pink / danger  */
--accent3: #6af7c8   /* Cyan / success */
--bg:      #0a0a0f   /* Page background */
--surface: #12121a   /* Card surface    */
--border:  #1e1e2e   /* Border color    */
```

## Typography

- **Display / UI font**: Syne (800 weight for headings, 400 for body)
- **Monospace font**: DM Mono (code snippets, labels)

## Getting Started

```bash
git clone https://github.com/YOUR_USERNAME/nexus-ui.git
cd nexus-ui
open index.html
```

No build step required. Open `index.html` directly in any modern browser.

## File Structure

```
nexus-ui/
├── index.html   # Full design system showcase
└── README.md
```

## Browser Support

Chrome 90+, Firefox 90+, Safari 15+, Edge 90+

## Roadmap

- [ ] Dark / Light theme toggle
- [ ] CSS variables export
- [ ] Copy-to-clipboard for each component
- [ ] Figma design file
- [ ] npm package

## License

MIT
