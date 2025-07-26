# AuraFX

**AuraFX** is an advanced visual particle effect editor designed specifically for [MythicMobs](https://www.spigotmc.org/resources/mythicmobs.5702/), the leading Minecraft plugin for custom mob skills and behaviors. AuraFX offers a high-fidelity, browser-based editing experience that allows creators to design 2D and 3D particle effects visually, without writing YAML manually.

> 💡 No coding. Just creativity.

---

## 🌍 Live Version  
**→ https://www.aurafx.online**  
AuraFX is fully browser-based. No downloads, no setup, no account required.

---

## 🧩 Key Features

### 🎨 Visual Canvas

- **2D Drawing Layer**  
  Draw freely using lines, points, circles, and pre-defined shapes.

- **3D Effect Space**  
  Fully rotatable 3D workspace for previewing layered effects in real time.

- **Multi-layer System**  
  Organize effects using a powerful layer-based system (rings, orbits, spirals, random scatter, custom paths).

- **Pixel-to-Particle Converter**  
  Import PNG images and convert visible pixels into particle positions — perfect for logos or signatures.

- **OBJ Import Support**  
  Transform vertices of any `.obj` 3D model into animated particle paths (experimental feature).

---

### ⚙️ MythicMobs YAML Generator

- Export effects directly into **MythicMobs-compatible YAML format**.
- Live YAML preview panel (auto-updated as you design).
- Clean, production-ready structure optimized for integration.

---

### 🔁 Dynamic Animations & Modifiers

- Add dynamic behaviors like:
  - Rotation
  - Orbiting
  - Rainbow color cycling
  - Speed ramping
  - Mirror / Flip
  - Pulse or burst patterns
- Tweak frequency, lifetime, and repeat delays

---

### 📁 Save & Share

- Save your projects as `.fxp` (AuraFX Project File)
- Load them anytime to continue editing
- Share FXP files with other creators or your team

---

### 💻 Performance Optimization

- Toggle between **Editor Mode** and **Performance Mode**
- Effect throttling and runtime particle count management
- GPU-accelerated rendering with efficient Three.js pipelines

---

## 🔧 Technical Overview

| Component        | Stack                        |
|------------------|------------------------------|
| Frontend         | [Next.js 14](https://nextjs.org/) + TypeScript |
| 3D Engine        | [Three.js](https://threejs.org/)              |
| Deployment       | [Vercel](https://vercel.com/) (Global CDN)   |
| Data Handling    | LocalStorage (no server-side DB)             |
| Hosting Location | United States (Vercel region auto-routing)  |

---

## 📜 Licensing & Source Code

AuraFX is currently **closed-source** and proprietary.  
All rights to the visual editor and generator system are reserved to the author.  
However, all YAML output generated using the platform is **free to use in your own MythicMobs scripts**, including for commercial Minecraft servers.

> ❗ Source code is not publicly available.  
> ❗ Reverse engineering or redistribution is not permitted.

---

## 👤 Author

Developed & maintained by **sleepsweetly**

- SpigotMC: [sleepsweetly](https://www.spigotmc.org/resources/authors/sleepsweetly.1865523/)
- Discord: `yaslicadi`
- Community Discord: [discord.gg/PheCGb6j](https://discord.gg/PheCGb6j)

---

## 💬 Support & Feedback

- Found a bug? Have a feature request?
- Reach out via the Discord community.
- Feedback is actively used to improve new versions.

---

## 📈 Planned Features (Roadmap)

- 🔄 GitHub integration for code sync (view only)
- 🧠 AI-assisted effect suggestions
- 🧰 Built-in effect templates (starter packs)
- 🔧 MythicMobs skill editor integration (via YAML bridging)
- 💾 Cloud save / share (optional, anonymous)

---

## 📌 Disclaimer

AuraFX is not affiliated with MythicMobs or its creators.  
This tool is designed independently to support the open scripting format used by MythicMobs.

---

