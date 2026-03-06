# 🛰️ KNIGHTOS: EVENT HORIZON | SYSTEM SPECIFICATIONS

## 🌌 ARCHITECTURE OVERVIEW
KnightOS is a high-performance, browser-based environment utilizing a centralized 
event-delegation engine. This architecture ensures minimal latency while managing 
a complex multi-window "Glassmorphism" interface.

---

## 🖥️ THE SINGULARITY (DESKTOP)
The primary workspace uses a "Global App Launcher" logic to manage interactions.
* **Selection:** Single-clicking an icon triggers the "Active" state, applying 
  royal-gold borders and a diffused glow backdrop.
* **Canvas Interaction:** Clicking the starry background invokes a system-wide 
  `querySelectorAll` to clear active states and focus the desktop.
* **Z-Index Management:** The OS uses a dynamic `highestZ` variable. Every window 
  click increments this value, ensuring the current task always overlays background processes.

---

## 🎨 VISUAL ENGINE: OBSIDIAN SQUIRCLES
The icon system (as seen in the desktop and terminal tray) follows a strict 
"Obsidian Squircle" design language:
* **Geometry:** A continuous-curve square container with semi-transparent glass backing.
* **Active Feedback:** CSS `:after` pseudo-elements create a gold underline on labels.
* **Atmospherics:** Pulse waves provide 2000ms of visual feedback upon app initialization.

---

## 📂 INTEGRATED APPLICATIONS
* **THE FORGE (TERMINAL):** A command-line shell for low-level system interaction.
* **THE EASEL (PAINT):** A canvas-driven creative suite for digital rendering.
* **THE ABACUS (CALC):** A precision mathematical engine for real-time computation.
* **GRAPHING:** A specialized module for visualizing complex functional data.
* **HORIZON BROWSER:** A sandboxed portal for external web navigation.

---

## 🛠️ SYSTEM COMMANDS & SHORTCUTS
* **Double-Click:** Direct execution of the `data-opens` attribute linked to window IDs.
* **Theme Toggle:** Instantly swaps root CSS variables between Indigo (Dark) and 
  Frosted (Light) modes.
* **Taskbar (The Horizon):** Centralized hub for application switching and system 
  status monitoring (Volume/Brightness).

---

## 📡 TECHNICAL STACK
* **Core:** Vanilla JavaScript (ES6+), HTML5, CSS3.
* **Rendering:** CSS Grid/Flexbox for the Horizon, Canvas API for the Singularity.
* **Performance:** Event delegation on the `document` object to prevent memory leaks.
