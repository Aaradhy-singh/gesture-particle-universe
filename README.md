# Gesture Particle Universe

Real-time 3D particle system controlled by hand gestures.
Built with Three.js + MediaPipe Hands.

## Live Demo
[Open in browser](https://aaradhy-singh.github.io/gesture-particle-universe/)

## Gestures
| Gesture | Action |
|---|---|
| ✊ Fist | Compress particles |
| 🖐 Open palm | Expand particles |
| 🤌 Pinch | Next shape |
| ✌️ Peace | Next color |

## Tech
- Three.js r128 — custom GLSL shader, additive blending
- MediaPipe Hands — palm-center distance gesture detection
- Pure HTML/CSS/JS — no build step, open directly in browser
