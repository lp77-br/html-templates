# HTML Templates & Kits

Beautiful, dependency-free HTML templates and multi-page kits. Copy, paste, ship.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

This repository contains a collection of handcrafted web interfaces. No build steps, no node_modules, no frameworks. Every file is pure HTML and CSS. Open it in a browser and it just works.

## 📂 Repository Structure

The project is divided into two main categories:

- **`templates/`** — Single-file components. Self-contained HTML files with inline CSS. Perfect for quick copy-pasting.
- **`kits/`** — Multi-page design systems. Cohesive sets of pages that share a common CSS file (`assets/styles.css`).

---

## 🧩 Templates (Single-file)

Standalone HTML files. Just open and edit.

| Template | Style | Description |
|----------|-------|-------------|
| [Landing SaaS (Purple Aurora)](templates/landing/landing-saas-purple-aurora.html) | Dark / Aurora | Hero section + Bento grid feature list. |
| [Pricing (Editorial Light)](templates/pricing/pricing-editorial-light.html) | Light / Minimal | Clean 3-tier pricing table with a featured card. |
| [404 (Space Float)](templates/404/404-space-float.html) | Dark / Playful | Floating gradient text with a CSS starfield. |

---

## 🎨 Kits (Multi-page)

Complete design systems with shared styles. Keep the folder structure intact to ensure relative links work.

### 1. Nexus SaaS (Purple Aurora)
A dark, modern SaaS starter kit with an animated aurora background and Inter typography.

**Pages:** Landing, Pricing, Auth, 404.
👉 **[View Kit](./kits/nexus-saas-purple/)**

### 2. Orbital Space (Dark Sci-Fi)
A sci-fi mission control theme featuring Space Grotesk typography, neon cyan accents, and a CSS starfield.

**Pages:** Landing, Dashboard, Pricing, Auth, 404.
👉 **[View Kit](./kits/orbital-space-dark/)**

---

## 🚀 How to use

**Option 1: The Templates**
1. Navigate to the `templates/` folder.
2. Click on any `.html` file.
3. Copy the code or download the file. Everything is in a single file.

**Option 2: The Kits**
1. Clone the repository:
   ```bash
   git clone https://github.com/lp77-br/html-templates.git
   ```
2. Navigate to the `kits/` folder.
3. Open any `index.html` to preview.
4. To use a kit, copy the entire folder (e.g., `nexus-saas-purple/`) to your project to keep the `assets/` links working.

## 📄 License

MIT — you can use these templates for personal or commercial projects.
Attribution is appreciated but not required. See [LICENSE](LICENSE) for details.

---
*Crafted by [lp77-br](https://github.com/lp77-br)*
