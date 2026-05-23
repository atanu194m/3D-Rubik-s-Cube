# Online 3D Rubik's Cube 🧩

A fully interactive, high-performance, and responsive **3D Rubik's Cube game** built for modern web browsers. It functions as a Progressive Web App (PWA) with complete touch/drag support, smooth physics animations, multiple cube configurations, dynamic color theme generation, and persistent statistics tracking.

---

## 🚀 Live Demo


---

## ✨ Features

### 🎮 Gameplay & Puzzles
* **Multiple Cube Sizes:** Choose from $2 \times 2 \times 2$, $3 \times 3 \times 3$, $4 \times 4 \times 4$, or $5 \times 5 \times 5$ interactive grids.
* **Intelligent Scrambler:** Generates randomized, standard-compliant shuffle sequences with variable difficulty lengths ($20$, $25$, or $30$ moves).
* **Solvability Validation:** Automatic background solver checking logic to instantly recognize when a face configuration matches a completed state.

### ⚙️ Customizable Controls & Preferences
* **Camera Modes:** Toggle easily between **Orthographic** and **Perspective** camera angles.
* **Tween Physics:** Configure turn types between *Swift*, *Smooth*, or *Bounce* settings depending on your favorite kinetic feedback profile.
* **Field of View (FOV):** Adjustable zooming dynamics to comfortably fit small mobile layouts or ultra-wide monitors.

### 🎨 Visuals & Aesthetics
* **Dynamic Color Schemes:** Pre-configured themes inspired by classic styles including *Cube*, *Erno*, *Dust*, *Camo*, and *Rain*.
* **Custom Theme HSL Editor:** Interactive slider menus to dynamically edit Hue, Saturation, and Lightness coordinates across target surfaces.
* **Celebration Effects:** Confetti particle system drops upon successfully completing a puzzle layer sequence.

### 📊 Performance Tracking & Storage
* **Session Counter:** LocalStorage persistent data pipeline tracking your Total Solves, Best Time, Worst Time, and competitive running averages (Average of 5, 12, and 25).
* **Game Session Recovery:** Built-in auto-save configuration state prevents loss of an ongoing scramble match if a webpage accidentally refreshes.

---

## 🛠️ Built With

* **HTML5 & CSS3** – Semantic structured canvas layout and modern fluid UI interface boundaries.
* **JavaScript (ES6+)** – Native asynchronous game engine loops, structural component controllers, and mathematical transformation calculations.
* **Three.js (r95)** – WebGL-based low-overhead rendering engine managing materials, lightning paths, and custom rounded geometric layouts.

---

## 📂 Repository Structure

```text
├── index.html   # Main workspace markup template containing PWA configurations
├── main.js      # Consolidated core application engine loop (Three.js & layout controllers)
├── style.css    # Layout aesthetics rules and fluid responsive grid specifications
└── cube.png     # Application shortcut viewport icon resource
