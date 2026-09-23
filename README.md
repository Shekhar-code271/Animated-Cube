# 🧊 Animated 3D Rubik's Cube Game

A fully interactive, beautifully polished 3D Rubik's Cube puzzle and solver built using **Three.js**, custom **JavaScript**, and modular **CSS3** animations. Test your puzzle-solving skills, customise cube dimensions, alter colour themes, and track your personal best solve times!

## ✨ Features

* **3D WebGL Rendering:** Powered by Three.js with smooth, physics-inspired layer rotations and easing animations.
* **Scalable Cube Sizes:** Configure your cube dimensions from \(2\times2\times2\) all the way up to \(5\times5\times5\).
* **Scrambling & Timers:** Automated smart-scrambler with built-in solve timers and a progress tracker.
* **Detailed Statistics Tracker:** Keep track of total solves, best times, worst times, and rolling averages (Ao5, Ao12, Ao25).
* **Custom Themes & Colour Editor:** Multiple built-in colour palettes (Cube, Erno, Dust, Camo, Rain) alongside a custom HSL theme picker[cite: 10, 11].
* **Confetti & Victory States:** Celebration confetti particle effects upon successfully solving the puzzle.
* **Local Storage Integration:** Automatically saves your ongoing game state and high scores locally.

## 📁 Project Structure

```text
├── index.html    # Main application structure, UI text nodes, range sliders, and layout
├── style.css     # Styling for menus, UI overlays, custom range inputs, and animations[cite: 12]
└── script.js     # Core Three.js setup, custom geometry (RoundedBox), controls, and game logic[cite: 11]
