# HyperCore — Terminal Brutalist Kit

A high-fidelity, dark-themed, terminal-inspired UI kit for infrastructure platforms, developer tools, security dashboards, and API products.

Built with pure HTML and CSS. No JavaScript, no frameworks, no build steps, and zero dependencies.

## 📄 Pages

This kit contains **12 fully designed, responsive pages** that form a complete SaaS MVP.

| Page | File | Purpose |
|------|------|---------|
| **Landing** | `index.html` | Hero section with animated grid background and feature grid. |
| **Dashboard** | `dashboard.html` | Sidebar layout, real-time metric cards, and a deployment data table. |
| **Docs** | `docs.html` | API reference layout with sticky sidebar and pure CSS syntax highlighting. |
| **Pricing** | `pricing.html` | 3-tier pricing table with a highlighted "Production" plan. |
| **Auth** | `auth.html` | Minimalist login form with monospace inputs and focus glow. |
| **404** | `404.html` | Terminal snippet with a massive glowing error code. |
| **Changelog** | `changelog.html` | System-log style vertical timeline with `[ADD]`, `[FIX]`, `[MOD]` tags. |
| **Security** | `security.html` | Compliance badges (SOC2, HIPAA) and a mock audit log terminal. |
| **Blog** | `blog.html` | Clean, text-focused engineering blog index. |
| **Settings** | `settings.html` | Account configuration with pure CSS toggle switches and danger zone. |
| **Status** | `status.html` | System health dashboard with uptime bars and incident history. |
| **Terms** | `terms.html` | Legal document layout with a sticky table of contents. |

## 🎨 Design System

The visual language is strictly "Terminal Brutalist": deep blacks, thin borders, monospace typography, and high-contrast accents. 

You can re-theme the entire 12-page kit by modifying the CSS variables in `assets/styles.css`:

```css
:root {
  --bg:          #0a0a0b;
  --bg-raised:   #0f0f12;
  --surface:     #141417;
  --surface-2:   #1b1b1f;
  --border:      rgba(255,255,255,0.07);
  --border-hi:   rgba(255,255,255,0.14);
  --text:        #f2f2f3;
  --text-2:      #a0a0a6;
  --accent:      #7b9dff;
  --accent-2:    #9bb5ff;
  --success:     #79c88b;
  --danger:      #d97777;
  --font-mono:   'IBM Plex Mono', ui-monospace, monospace;
}
