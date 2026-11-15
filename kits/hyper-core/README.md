# HyperCore — Terminal Brutalist Kit

A dark, high-contrast, terminal-inspired design system. Best suited for developer tools, infrastructure platforms, security dashboards, and API products.

Built with pure HTML and CSS. No JavaScript, no frameworks, no build steps.

## Pages

| Page | File | Purpose |
|------|------|---------|
| Landing | `index.html` | Hero, animated grid background, feature grid |
| Dashboard | `dashboard.html` | Sidebar layout, stats cards, and a data table |
| Docs | `docs.html` | API reference layout with code blocks and method badges |
| Pricing | `pricing.html` | 3 tiers with highlighted "Production" plan |
| Auth | `auth.html` | Minimalist login form with monospace inputs |
| 404 | `404.html` | Terminal snippet with massive glowing error code |
| Changelog | `changelog.html` | Vertical timeline with semantic tags (Added/Fixed) |

## Design System

The aesthetics rely on monospace typography (`IBM Plex Mono`), deep blacks, and thin borders. You can re-theme the entire kit in `assets/styles.css` by modifying the `:root` variables:

```css
--bg: #0a0a0b;
--accent: #7b9dff;
--border: rgba(255,255,255,0.07);
