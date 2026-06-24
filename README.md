# ASCII-Avatar 🖥️

[![Deployment Status](https://img.shields.io/github/deployments/itishacodes/ASCII-Avatar/github-pages?label=Live%20Demo&color=2ea44f)](https://itishacodes.github.io/ASCII-Avatar/)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

An ultra-minimalist, retro textmode avatar generator deeply inspired by 1980s terminal installations, BIOS setup screens, and net-art constraints. 

Built with absolute computational minimalism, the entire application lives inside a single, lightweight file utilizing vanilla web technologies - no frameworks, no bundlers, and zero external packages.

---

## 🌐 Live Application

The application is deployed live and running directly via GitHub Pages: **[itishacodes.github.io/ASCII-Avatar](https://itishacodes.github.io/ASCII-Avatar/)** 🚀

---

## Core Pillars

### 🎨 State-Driven Color Matrix
The engine tracks state changes seamlessly. Every input command, feature adjustment, or menu navigation triggers a recalculation of the terminal's color palette—cycling through dark/light contrast pairs dynamically to keep each session uniquely creative.

### 🧱 Monospaced Layering Engine
Unlike modern canvas grids that manipulate individual pixels, ASCII-Avatar compiles multi-line text strings over structured data matrices, preserving column/row layout rules inside native `<pre>` elements.

### 🕹️ Authentic Terminal Navigation
True to classic mainframe computers, users interact natively using their keyboards. Typing option numbers directly inputs data into a live-updating blinking cursor pipeline, though it features responsive pointer fallbacks for seamless navigation.

---

## ⚙️ Technical Blueprint

| Layer | Architecture | Mechanics |
| :--- | :--- | :--- |
| **Frontend** | Vanilla HTML5 | Structural `<pre>` blocks |
| **Styling** | Native CSS3 | Monospaced alignment, keyframe blink animations |
| **Logic** | Vanilla JS (ES6) | Stateful option mappings, dynamic array injection |
| **Dependencies** | None | Pure, lightweight client-side execution |

---
*Created in 2026. Designed for open experimentation. Free to fork and modify.*
