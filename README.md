# Prototypes

A collection of interactive prototypes and demos built with various web technologies.

## 🌐 Live Site

Visit [prototypes.blaze.design](https://prototypes.blaze.design) to see all demos in action.

## 🛠️ Built With

- **Jekyll** - Static site generator

## 🚀 Local Development

1. Clone the repository
2. Install dependencies: `bundle install`
3. Run locally: `bundle exec jekyll serve`
4. Open `http://localhost:4000`

## 📁 Project Structure

- `/` - Individual prototype HTML files
- `/_layouts/` - Jekyll layout templates
- `/_sass/` - Sass stylesheets
- `/_includes/` - Reusable components
- `/assets/` - Images and compiled CSS

## 🎨 Adding New Prototypes

Create a new HTML file in the root directory with this front matter:

```yaml
---
layout: default
title: your-prototype-name
description: brief description
prototype: true
---
```

Then add your HTML, CSS, and JavaScript below the front matter.

## 🤖 AI Assistant Guidelines

When creating new prototypes, follow these patterns:

- **Keep it simple**: Each prototype should demonstrate one focused concept
- **Self-contained**: All CSS and JavaScript should be inline within the HTML file
- **Use semantic file names**: `token-swap.html`, `image-spin.html`, `marble-maker.html`
- **Brief descriptions**: Keep the description short and technical (e.g., "css animation", "three.js 3d experiment")
- **Standard structure**: Front matter → `<style>` → HTML → optional `<script>`
- **Responsive design**: Consider mobile-friendly sizing and layouts
- **External assets**: Use CDN links for libraries like Three.js, or reference local assets in `/assets/`
- **Three.js template**: For Three.js prototypes, copy `test.html` and rename it for your new experiment. It includes basic Three.js setup with canvas element, OrbitControls for camera interaction, dat.GUI for parameter controls, and responsive styling for the canvas container.

The goal is rapid prototyping and experimentation, not production-ready code.

---

Made by [blaze](https://blaze.design) 