<div align="center">

# ✨ Interactive 3D Physics Portfolio
### *Immersive WebGL Personal Portfolio featuring Custom Shaders, Skeletal Rigs & Scroll Kinetics*

[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Three.js](https://img.shields.io/badge/Three.js-WebGL-black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![GSAP](https://img.shields.io/badge/GSAP-ScrollTrigger-88CE02?style=for-the-badge&logo=greensock&logoColor=white)](https://greensock.com/gsap/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<br />

<img src="https://raw.githubusercontent.com/Zishan3909/-3d-portfolio/main/public/banner.gif" alt="3D Portfolio Banner" width="100%" onerror="this.src='https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=1200&q=80'" />

<p align="center">
  <b>A showcase of advanced front-end engineering, merging real-time 3D graphics, procedural character animation, and high-performance WebGL rendering.</b>
</p>

[🌐 Explore the Live Experience](https://flourishing-kitsune-e3810c.netlify.app/)

</div>

---

## 📌 Executive Summary

Traditional static portfolios fail to showcase the depth of modern graphics rendering. This project is a production-grade 3D web experience built to push browser boundaries while maintaining accessibility. 

Anchored by an interactive GLTF character model with procedural bone tracking and lighting shaders, the application choreographs narrative storytelling through **GSAP ScrollTrigger pipelines** while sustaining a locked 60 FPS across both desktop and constrained mobile viewports.

---

## ✨ Features

- 🕺 **Procedural 3D Character Rigging:** Custom Three.js integration featuring GLTF skeletal manipulation, procedural mouse-tracking, and dynamic idle/react animations.
- 📜 **Kinematic Scroll Choreography:** Seamless GSAP ScrollTrigger pipelines tying WebGL camera translation, rotation matrices, and DOM transitions to scroll depth.
- ⚡ **Adaptive 60 FPS Performance Engine:** Automated Device Pixel Ratio (DPR) clamping, dynamic draw-call batching, and geometry disposal to prevent mobile memory leaks.
- 💎 **Glassmorphic Spatial UI:** Modern responsive design system built on custom Tailwind CSS layouts, glassmorphic filters, and fluid CSS grids.
- 🎨 **Custom Lighting Shaders:** Real-time environment reflections, directional spotlights, and HDR lighting maps built directly in WebGL.

---

## 🛠️ Tech Stack

- **Core Framework:** React 18 & Vite
- **3D Graphics & Shaders:** Three.js, WebGL, DRACO 3D Compression
- **Animation Pipelines:** GSAP (GreenSock), ScrollTrigger
- **Type Safety & Architecture:** TypeScript, ES Modules
- **Design System:** Tailwind CSS, PostCSS Flexbox/Grid

---

## 🚀 Quick Start / Installation

### Prerequisites
- Node.js (v18.0.0 or higher)
- npm, pnpm, or yarn

### Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/Zishan3909/-3d-portfolio.git
cd -3d-portfolio

# 2. Install project dependencies
npm install

# 3. Launch local Vite development server
npm run dev
