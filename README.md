# Hand-Tracked-3D-Particle-Morph

"A real-time 3D particle system morphing between shapes using Google MediaPipe for AI hand-tracking and Three.js for GPU-accelerated rendering."

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![ThreeJS](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0473EA?style=for-the-badge&logo=google&logoColor=white)

## ✨ Features
- **Real-time Hand Tracking:** Uses Computer Vision to map your hand coordinates to 3D space.
- **Gesture Interaction:** - **Pinch (Thumb + Index):** Creates a high-gravity "Black Hole" effect, attracting particles and changing their color to "heat" (Red/Orange).
  - **Open Hand:** Gentle attraction with fluid-like turbulence.
- **Dynamic Morphing:** Smoothly transitions between 5 mathematical shapes: Sphere, Heart, Saturn, Flower, and Cube.
- **GPU Accelerated:** Optimized with Three.js BufferGeometry to handle 12,000+ particles at 60 FPS.

## 🎮 How to Use
1. Allow webcam access when prompted.
2. **Move Hand:** Particles will follow your palm.
3. **Pinch:** Bring your thumb and index finger together to condense the energy.
4. **Change Shape:** Move your hand to the far **right edge** of the screen to cycle through shapes.

## 🛠️ Built With
- **Three.js** - 3D Engine and WebGL rendering.
- **MediaPipe Hands** - ML solution for high-fidelity hand and finger tracking.
- **HTML5/CSS3** - For UI overlays and structure.

## 🚀 Deployment
This project is ready to be hosted on **GitHub Pages**.
1. Push your code to a repository.
2. Go to **Settings > Pages**.
3. Select the `main` branch and click **Save**.

---
*Created as an exploration of Human-Computer Interaction (HCI) and Generative Art.*
