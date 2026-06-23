# Gesture Control | Precision Gesture Control Engine

A high-performance, web-based gesture control interface powered by MediaPipe. Interact with particles, draw in 3D space, and unleash superpowers using only your hands.

## Live
Experience it live here: [https://gesture-control-website.netlify.app](https://gesture-control-website.netlify.app)

---

## Features
- **Gesture-Based Navigation:** Switch between interaction modes using the "Rock On" (🤟) lock-gesture and a horizontal swipe.
- **Live Image Puzzle:** Take a snapshot of your webcam feed and solve a 3x3 sliding puzzle using intuitive pinch-and-drag hand controls.
- **Particle Interaction:** Engage with real-time particle systems.
- **Dual-Wield Sketching:** Sketch in 3D space using both hands simultaneously with customizable colors.
- **Superpowers:** - **Plasma Sphere:** Charge energy by bringing palms together and launch it with a rapid pull.
    - **Fireball Blaster:** Use the "Finger Gun" pose (Thumb up to cock, thumb down to fire) to shoot fireballs with sound effects.
- **Precision Tracking:** Built-in adaptive smoothing and 3D depth-aware math for jitter-free performance.
- **Responsive Design:** Fully optimized for mobile and desktop browsers.

---

## How to Use

### Global Controls
* **Change Mode:** Raise Index & Pinky (🤟). While holding this pose, swipe your hand left or right.

### Mode Instructions

| Mode | Gesture | Action |
| :--- | :--- | :--- |
| **Particle** | Pinch Index & Thumb | Trigger energy pulse. |
| **Particle** | Both hands on screen | Energy Bridge (connects fingertips). |
| **Particle** | Finger Gun Pose | Thumb up to cock, Thumb down to shoot fireball. |
| **Particle** | Both palms close | Charge Plasma Sphere. |
| **Geometry** | Both palms together | Align index fingers up to lock geometry. |
| **Sketch** | Thumb & Middle Pinch | Sketch on the canvas. |
| **Sketch** | Open Hand (5 fingers) | Change pen color. |
| **Puzzle** | Click Start/Restart | Take a camera snapshot and shuffle the grid. |
| **Puzzle** | Pinch (Index+Thumb) & Drag | Slide a neighboring puzzle piece into the empty slot. |

---

## Tech Stack
* **MediaPipe Hands:** For real-time 3D hand landmark tracking.
* **Web Audio API:** For real-time synthesized sound effects (Pews, Explosions).
* **Canvas API:** For high-performance particle and drawing rendering.
* **Vanilla JavaScript:** For a lightweight, dependency-free engine.

---

## How to Run Locally
1. Clone this repository.
2. Open `index.html` in a modern web browser (Works best on Google Chrome).
3. Allow camera access when prompted and enjoy.

---

## Made by
- **Vaibhav Agarwal** 
- [LinkedIn Profile](https://www.linkedin.com/in/vaibhavagarwal46)
