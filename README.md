# Weldon Tan — AI Specialist & Data Scientist Portfolio

This repository hosts the personal portfolio for Weldon Tan. The site showcases core AI capabilities, highlighted projects, and a direct contact form in a sleek, futuristic interface optimised for showcasing AI-focused expertise.

## ✨ Features

- **Immersive hero experience** with animated gradients, floating badges, and metric cards that highlight delivery impact.
- **Glassmorphism-inspired content sections** that retain the original structure while adding depth, glow effects, and high-contrast readability.
- **Responsive technology showcase** presented as neon-tagged categories for quick scanning across device sizes.
- **Animated intersection reveals** so that each section fades up as the visitor scrolls, reinforcing the modern aesthetic.
- **Contact form wired for Google Apps Script** and wrapped in a glowing panel with success/error feedback states.

## 🛠️ Local Development

The site is a static HTML page, so you can use any static file server. For example, with Python installed:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser to view the site.

## 📁 Project Structure

```
├── favicon.png
├── index.html    # Main portfolio page
└── README.md     # Repository documentation (this file)
```

## 🚀 Deployment

Because the project is static, it can be deployed with GitHub Pages or any static hosting service. Push the repository to a GitHub Pages-enabled branch (such as `main` on a `username.github.io` repo) and Pages will serve `index.html` automatically.

## 📬 Contact

Use the form on the site to reach out. To connect the form to your Google Apps Script endpoint, replace the `SCRIPT_URL` constant in `index.html` with your deployed Apps Script web app URL.
