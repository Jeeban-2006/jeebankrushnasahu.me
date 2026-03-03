# 🎨 jeebankrushnasahu.me

[![Live Site](https://img.shields.io/badge/Live-jeebankrushnasahu.me-orange?style=for-the-badge)](https://jeebankrushnasahu.me)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](LICENSE)
[![Made with](https://img.shields.io/badge/Made_with-Vanilla_JS-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A bold, modern **neo-brutalist personal portfolio** built from scratch with pure HTML, CSS, and JavaScript. No frameworks, no build tools — just raw, creative code that makes a statement.

<div align="center">

**[🌐 Live Site](https://jeebankrushnasahu.me)** • **[💻 Terminal Mode](https://jeebankrushnasahu.me/terminal.html)** • **[📁 All Projects](https://jeebankrushnasahu.me/projects.html)**

</div>

---

## 👨‍💻 About

This is the personal portfolio of **Jeeban Krushna Sahu** — a B.Tech Computer Science student at ITER, SOA University, Bhubaneswar (CGPA: 8.86/10.0). Passionate about AI/ML engineering, full-stack development, and building impactful open-source tools.

> 💡 **Design Philosophy:** This portfolio rejects cookie-cutter templates in favor of bold creativity. It's a playground for animations, interactions, and experimental web design — code that tells a story.

---

## 🎨 What is Neo-Brutalism?

Neo-brutalism is a design movement that rejects the polished, rounded uniformity of modern web design:

- **🔲 Thick Black Borders** — Hard, visible edges on every element
- **📦 Flat Offset Shadows** — `box-shadow: 8px 8px 0 #000` for depth
- **🌈 High-Contrast Palettes** — Bright yellows, pinks, cyans, and greens
- **🏗️ Visible Structure** — The layout's bones are intentionally exposed
- **✨ Playful Imperfection** — Torn paper edges, tape stickers, hand-drawn vibes

This portfolio embraces all of these principles to create a unique, memorable experience.

---

## ✨ Key Features

### 🎯 Main Portfolio (index.html)

| Feature | Description |
|---------|-------------|
| **📄 Paper Tear Effect** | SVG torn paper edges between sections with scroll animations |
| **📖 Book-Flip Timeline** | Interactive journey timeline that opens like a treasure map |
| **🖍️ Scroll Highlights** | Text highlights animate like a real highlighter pen |
| **🗺️ Interactive Map** | Leaflet.js map — click timeline entries to fly to locations |
| **⌨️ Matrix Typing** | Hero greeting scrambles through random characters before resolving |
| **🎯 Falling Icons** | SVG tech icons drop with physics-based gravity on scroll |
| **📱 Fully Responsive** | Perfect on mobile, tablet, and desktop |
| **⚡ Performance Optimized** | Lazy loading, preconnect, and minimal dependencies |

### 💻 Terminal Mode (terminal.html)

An interactive terminal-style resume with 15+ commands:

**Main Commands:**
- `about` — Professional summary
- `skills` — Technical expertise
- `experience` — Work history
- `education` — Academic background
- `contact` — Get in touch
- `projects` — Project showcase

**Utility Commands:**
- `skills-visual` — Interactive skills visualization
- `game` — Play Snake game (p5.js)
- `matrix` — Matrix digital rain effect
- `weather <city>` — Check weather
- `calc <expression>` — Calculator
- `pdf` — Download resume
- `linkedin-cover` — Generate LinkedIn cover image

**Features:**
- 🎨 Multiple themes (Default, Dracula, Solarized, Nord)
- 📝 Command history (↑/↓ arrows)
- ⌨️ Tab completion
- 🔀 Split terminal views (Ctrl+Shift+H/V)
- 🎮 Interactive mini-games

---

## 📁 Project Structure

```
jeebankrushnasahu.me/
│
├── 🌐 HTML Files
│   ├── index.html          # Main neo-brutalist portfolio
│   ├── projects.html       # All projects showcase
│   └── terminal.html       # Interactive terminal resume
│
├── 🎨 Stylesheets
│   ├── neo-styles.css      # Styles for main portfolio
│   └── styles.css          # Styles for terminal mode
│
├── ⚙️ Scripts
│   └── script.js           # Terminal logic, commands & interactions
│
├── 🎯 Assets
│   ├── image/              # Photos, icons, social covers
│   ├── favicon.svg         # Site favicon (JKS logo)
│   └── resume.pdf          # Downloadable resume
│
├── 🔧 Configuration
│   ├── CNAME               # Custom domain configuration
│   ├── robots.txt          # Search engine directives
│   ├── sitemap.xml         # SEO sitemap
│   └── .nojekyll           # Bypass Jekyll on GitHub Pages
│
└── 📄 Documentation
    ├── README.md           # This file
    └── LICENSE             # License information
```

---

## 🛠️ Tech Stack

### Core Technologies
- **HTML5** — Semantic markup with SEO optimization
- **CSS3** — Modern layouts (Grid, Flexbox), animations, and custom properties
- **Vanilla JavaScript (ES6+)** — No frameworks, pure DOM manipulation

### Libraries & Tools
- **[Leaflet.js](https://leafletjs.com/)** — Interactive journey map
- **[p5.js](https://p5js.org/)** — Snake game canvas rendering
- **[Font Awesome 6](https://fontawesome.com/)** — Icon library
- **[Google Fonts](https://fonts.google.com/)** — Space Grotesk, Space Mono, Caveat, Fira Code

### SEO & Performance
- Structured Data (JSON-LD)
- Open Graph & Twitter Cards
- Sitemap & Robots.txt
- Lazy loading & resource preloading
- Optimized images & fonts

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional but recommended)

### Installation & Running

1. **Clone the repository**
   ```bash
   git clone https://github.com/Jeeban-2006/jeebankrushnasahu.me.git
   cd jeebankrushnasahu.me
   ```

2. **Start a local server**

   **Option 1: Using Node.js**
   ```bash
   npx serve .
   # Opens at http://localhost:3000
   ```

   **Option 2: Using Python**
   ```bash
   python -m http.server 8000
   # Opens at http://localhost:8000
   ```

   **Option 3: Using PHP**
   ```bash
   php -S localhost:8000
   ```

   **Option 4: Using VS Code**
   - Install "Live Server" extension
   - Right-click `index.html` → "Open with Live Server"

3. **Open in browser**
   - Navigate to the local server URL
   - Start exploring!

> ⚠️ **Note:** Opening `index.html` directly in a browser may cause CORS issues with some features. Always use a local server for development.

---

## 📊 SEO & Performance

✅ **SEO Optimized:**
- Semantic HTML5 structure
- Proper meta tags (Open Graph, Twitter Cards)
- JSON-LD structured data
- Sitemap.xml for search engines
- Robots.txt configuration
- Canonical URLs

✅ **Performance:**
- Minimal dependencies
- Lazy loading for images & fonts
- Preconnect to external domains
- Efficient CSS with custom properties
- No build process = instant updates

✅ **Accessibility:**
- High contrast ratios (WCAG AA compliant)
- Keyboard navigation support
- Alt text for all images
- Semantic HTML for screen readers

---

## 🌐 Deployment

This site is deployed on **GitHub Pages** with a custom domain.

### Deploy to GitHub Pages

1. Push to GitHub:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```

2. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Set source to `main` branch
   - Add custom domain in CNAME file

3. Configure DNS (for custom domain):
   - Add A records pointing to GitHub Pages IPs
   - Add CNAME record: `www` → `<username>.github.io`

---

## 🤝 Contributing

This is a personal portfolio project, but feedback and suggestions are welcome!

- 🐛 **Found a bug?** [Open an issue](https://github.com/Jeeban-2006/jeebankrushnasahu.me/issues)
- 💡 **Have an idea?** Feel free to suggest improvements
- ⭐ **Like the project?** Give it a star!

---

## 📝 License

This project is **proprietary** and all rights are reserved.

- ✅ You may view the source code for **inspiration and learning**
- ❌ You may **NOT** copy, modify, or redistribute this code without explicit written permission
- ❌ You may **NOT** use this design or code for your own portfolio without permission

For licensing inquiries, contact: [jeebankrushnasahu1@gmail.com](mailto:jeebankrushnasahu1@gmail.com)

See [LICENSE](LICENSE) for full details.

---

## 📬 Contact

**Jeeban Krushna Sahu**

- 🌐 Website: [jeebankrushnasahu.me](https://jeebankrushnasahu.me)
- 💼 LinkedIn: [linkedin.com/in/jeeban-krushna-sahu-004228301](https://linkedin.com/in/jeeban-krushna-sahu-004228301)
- 🐙 GitHub: [github.com/Jeeban-2006](https://github.com/Jeeban-2006)
- 📧 Email: [jeebankrushnasahu1@gmail.com](mailto:jeebankrushnasahu1@gmail.com)
- 📸 Instagram: [@jenext.exe](https://instagram.com/jenext.exe)

---

## 🙏 Acknowledgments

- **Original Design & Codebase:** [Marjo Ballabani](https://github.com/marjoballabani) - This portfolio is built upon Marjo's excellent neo-brutalist template and has been extensively customized and personalized with my own content, projects, and features.
- **Design Inspiration:** Neo-brutalism movement, Gumroad, Linear
- **Libraries:** Leaflet.js contributors, p5.js community
- **Fonts:** Google Fonts, Font Awesome team
- **Hosting:** GitHub Pages

---

<div align="center">

**Made with ❤️ and lots of ☕ by Jeeban Krushna Sahu**

⭐ Star this repo if you found it interesting!

</div>
