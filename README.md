# 🎆 Diwali Phatka - Virtual Firecrackers Simulator

[![Deploy to GitHub Pages](https://github.com/ritikthakur22/diwali-phatka/actions/workflows/pages.yml/badge.svg)](https://github.com/ritikthakur22/diwali-phatka/actions/workflows/pages.yml)
[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2ea44f?style=flat&logo=github)](https://ritikthakur22.github.io/diwali-phatka/)
[![Original Reference](https://img.shields.io/badge/Original_Reference-pattasu--diwali.vercel.app-blue)](https://pattasu-diwali.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An interactive, browser-based **Augmented Reality (AR) & 3D Diwali Firecrackers Simulator**. Experience bursting crackers right in your room through your live camera, or enjoy the virtual celebration on an atmospheric Indian rooftop terrace under a starry night sky.

- 🌐 **Live Demo:** [https://ritikthakur22.github.io/diwali-phatka/](https://ritikthakur22.github.io/diwali-phatka/)
- 🔗 **Original Project Reference:** [https://pattasu-diwali.vercel.app](https://pattasu-diwali.vercel.app)

---

## ✨ Features

- 📸 **Live Camera AR Mode**: Burst fireworks directly over your surroundings using your phone or webcam! Realistic explosion illumination and flashes dynamically reflect onto your live camera video stream.
- 🪔 **Automatic 3D Terrace Fallback**: If camera access is denied, blocked, or unavailable, the app automatically falls back to a 3D Indian rooftop terrace with stone pavement, glowing city skyline, and 1,500 twinkling stars.
- 🔊 **100% Procedural Web Audio Engine**: Zero external audio downloads. All sound effects (whistling rocket motors, heavy explosion bodies, crackles, burning fuses, and distant street echoes) are synthesized in real-time with realistic physics delays (speed of sound: 340 m/s) and stereo panning.
- 🎇 **11 Authentic Firecracker Types**:
  - **Sky Fireworks**: Rockets, Sky shot (peony & chrysanthemum), 12-shot, Golden rain, Crackling, and Grand Finale.
  - **Ground Bombs**: Atom bomb, Sutli bomb, Lakshmi vedi, 100 wala garland, and 1000 wala garland (with rapid sequential pops and flying red paper shreds).
- 🎮 **Seamless Controls**:
  - Top mode tabs: **`[ 🎆 Sky Fireworks ]`** and **`[ 💥 Ground Bombs ]`**.
  - Tap / Click anywhere to launch or place crackers.
  - Hold down to fire continuous bursts in sky mode.
  - Drag to smoothly look around in 360°.
  - Camera toggle button (📷) to switch between Live AR and 3D Terrace anytime.
  - Sound mute/unmute button (🔊) and Hide UI button (👁️) for recording clean social media videos.

---

## 🎮 How to Play

1. Open [https://ritikthakur22.github.io/diwali-phatka/](https://ritikthakur22.github.io/diwali-phatka/).
2. Click **"Celebrate Diwali 🎆"**.
3. Allow camera access for the Live AR experience, or block/decline to enjoy the default 3D terrace scene.
4. Select your firecracker from the bottom tray:
   - Tap the sky to shoot rockets and aerial shells.
   - Switch to ground mode to place and light bombs and walas on the pavement.

---

## 🛠️ Tech Stack

- **Three.js** (`three@0.160.0` via ES Module Import Map)
- **WebGL & Custom GLSL Shaders** (Dynamic lighting, particle physics, reflections)
- **Web Audio API** (Procedural audio synthesis, biquad filters, convolution reverb)
- **HTML5 & CSS3** (Mobile-first, responsive, zero external build tools required)

---

## 🚀 Local Development

To run locally without build tools:

```bash
# Clone the repository
git clone https://github.com/ritikthakur22/diwali-phatka.git
cd diwali-phatka

# Start a local HTTP server
python3 -m http.server 8080
# or: npx serve .
```

Open `http://localhost:8080` in your browser.

> [!NOTE]  
> Browsers require HTTPS to access camera streams (`navigator.mediaDevices.getUserMedia`). For mobile camera testing, use tools like `cloudflared`, `ngrok`, or GitHub Pages.

---

## 📜 License & Credits

- Created and maintained by [**ritikthakur22**](https://github.com/ritikthakur22).
- **Original Project Reference & Concept**: [Pattasu](https://pattasu-diwali.vercel.app) by [Kevin Adams (@ikevinadams)](https://twitter.com/ikevinadams).
- Released under the [MIT License](LICENSE).
