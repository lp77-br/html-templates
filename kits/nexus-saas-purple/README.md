# Nexus — SaaS Kit (Purple Aurora)

A cohesive, high-fidelity 4-page SaaS starter kit. Featuring a dark theme, an animated aurora background, purple gradient accents, and crisp Inter typography.

Built with pure HTML and CSS. No build steps, no dependencies, no comments in the source — just clean, copy-pasteable code.

## 📄 Pages

| Page | File | Purpose |
|------|------|---------|
| **Landing** | `index.html` | Hero section, call-to-actions, and a responsive bento-grid feature section. |
| **Pricing** | `pricing.html` | 3-tier pricing table with a monthly/yearly toggle and a featured "Pro" card. |
| **Auth** | `auth.html` | Centered glassmorphic sign-in form with social login placeholders. |
| **404** | `404.html` | Playful floating error page with a smooth gradient text effect. |

## 🎨 Design System

The entire visual language is driven by CSS variables located in `assets/styles.css`. To re-skin the entire kit, you only need to change a few hex codes in the `:root` block:

```css
:root {
  --bg: #08080c;          /* Deep space black */
  --accent: #6366f1;      /* Primary purple */
  --accent-2: #a855f7;    /* Gradient end (violet) */
  --fg: #f0f0f5;          /* Off-white text */
  --muted: #8888a0;       /* Secondary text */
}
