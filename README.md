# Hand-Guided-Particles-3D
An interactive 3D particle system controlled in real-time via hand gestures using MediaPipe and Three.js. This project translates physical hand movements into digital forces like attraction, repulsion, and rotation.
# 🌌 Neural Flux: Hand Gesture Particle System

A high-performance, browser-based particle simulation that reacts to human hand movements. Using **MediaPipe Hands** for computer vision and **Three.js** for WebGL rendering, this project creates a bridge between physical motion and digital art.

## ✨ Features
* **Real-time Tracking:** Low-latency hand landmark detection via webcam.
* **Gesture-Based Physics:**
    * ✋ **Open Palm:** Repels particles away from your hand.
    * ✊ **Fist:** Attracts particles toward your palm (Gravity Well).
    * 🤏 **Pinch:** Dynamically cycles particle colors.
* **Dual Hand Support:** Includes a specialized module for two-handed interaction and energy field manipulation.
* **3D Rotation:** Full 360° hand orientation mapping for particle cloud rotation.

## 🛠️ Tech Stack
- **Three.js** (3D Rendering Engine)
- **MediaPipe** (Hand Landmark Detection)
- **JavaScript (ES6+)**
- **HTML5/CSS3**

## 🚀 Quick Start
1. Clone the repository.
2. Open `dual_hand_gesture.html` or `partical_gesture1.html` in any modern web browser (Chrome recommended).
3. Click **Start Camera** and allow webcam access.
4. Experiment with different hand shapes to interact with the particles.

## 📂 File Structure
- `dual_hand_gesture.html`: Advanced version supporting two hands and complex rotation.
- `partical_gesture1.html`: High-density single-hand version (70k+ particles) with color-change triggers.
