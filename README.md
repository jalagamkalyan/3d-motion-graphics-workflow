# ⚡ $0 3D Motion Graphics Workflow (Claude + Three.js)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Three.js](https://img.shields.io/badge/Three.js-r128-black?logo=three.js)](https://threejs.org/)
[![YouTube](https://img.shields.io/badge/YouTube-Kalyan's%20Lab-red?logo=youtube)](https://youtube.com/@TheKalyanChakri)
[![Cost](https://img.shields.io/badge/Cost-%240-success)](https://github.com/jalagamkalyan/3d-motion-graphics-workflow)

Stop paying **$35/month for After Effects** or struggling for hours in Blender. 

This repository contains the exact **prompt, workflow, and Three.js source code** used by **[Kalyan's Lab](https://youtube.com/@TheKalyanChakri)** to create custom, 60 FPS 3D motion graphics for **$0** that run entirely inside Google Chrome.

---

## 🎯 The YouTube Studio Experiment

> *"My channel was stuck at 22 views because generic stock clips looked boring and lazy. When I replaced stock b-roll with custom interactive Three.js 3D visuals, audience retention shot from 20% to 84%, and views exploded to **1,203 views in 24 hours**. Audiences don't care about your subscriber count—they care about visual effort."*

---

## 🚀 Quick Start (In 30 Seconds)

1. Clone or download this repository:
   ```bash
   git clone https://github.com/jalagamkalyan/3d-motion-graphics-workflow.git
   ```
2. Double-click **`index.html`** to open it in **Google Chrome** (or any browser).
3. **Move your mouse or touch the screen** to see the 3D card tilt and interact with real-time WebGL light caustics and particle physics!
4. Zero installs, zero node_modules, zero dependencies.

---

## 📋 The Master AI Prompt (Claude / ChatGPT)

Want to generate your own custom 3D visuals? Copy and paste the prompt from [`CLAUDE_MASTER_PROMPT.txt`](./CLAUDE_MASTER_PROMPT.txt) directly into **Claude.ai** or **ChatGPT**:

```text
You are an expert creative technologist and Three.js developer. 
Create a complete, single-file, production-ready HTML5/Three.js 3D animation suitable for a high-end faceless YouTube video or tech landing page.

SPECIFICATIONS:
1. Architecture: A single self-contained index.html file with Three.js (r128) imported from CDN (https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js). Zero node modules, zero npm installs.
2. Canvas & Visuals:
   - Deep obsidian background (#0A0D14) with subtle glowing atmospheric vignette.
   - A floating, rounded glass card (MeshPhysicalMaterial with high transmission: 0.92, low roughness: 0.08, index of refraction: 1.52, and subtle cyan/purple rim caustics).
   - Dynamic 3D lighting: PointLight with Electric Cyan (#00F5D4) on one edge, soft Apple Crimson (#FF3B30) ambient fill, and a directional rim light.
   - Ambient particle dust (500 small glowing stars/dust particles floating gently in 3D depth).
3. Typography / Details on Card:
   - Embossed or canvas-rendered high-contrast typography on the card face:
     - Header: "KALYAN'S LAB" (SF Pro / Inter aesthetic, uppercase, tracked)
     - Tag: "THREE.JS · 60 FPS WEBGL"
     - Metric badge: "+1,203 VIEWS" in Electric Cyan.
4. Movement & Animation:
   - Smooth continuous 3D idle floating and tilting along the X and Y axes (using Math.sin/cos time oscillation).
   - Mouse / Touch Parallax: The card tilts smoothly toward the cursor on desktop or touch move on mobile with easing.
5. Code Quality:
   - Clean, well-commented, responsive (handles window resize smoothly), high performance (60 FPS on integrated GPUs).
   - Output ONLY the raw HTML code enclosed in ```html ``` with no conversational filler.
```

---

## 🎬 How to Use in Your YouTube Videos / Shorts

1. Open `index.html` in Chrome and press `F11` (full screen).
2. Record 5–10 seconds of screen video using **OBS Studio** or **Windows Game Bar** (`Win + G`).
3. Drop the smooth 60 FPS clip directly into **CapCut**, **Premiere Pro**, or **DaVinci Resolve**.

---

## ⚡ Next Template Dropping Friday

Every Friday, we open-source a new motion graphics template and AI coding workflow.

👉 **[Subscribe to Kalyan's Lab on YouTube](https://youtube.com/@TheKalyanChakri)** to follow the live channel experiment and get the next 3D component!

---

## 📄 License
This project is open-source under the [MIT License](./LICENSE). Feel free to use it in your personal and commercial videos/websites!
