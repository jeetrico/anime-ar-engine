# 🌀 JEETRICO: Anime AR Engine v2.0 ⚡

![GitHub license](https://img.shields.io/badge/License-MIT-blueviolet.svg)
![Platform](https://img.shields.io/badge/Platform-Web_AR-orange.svg)
![Tech](https://img.shields.io/badge/Engine-MediaPipe_Hands-blue.svg)

> **"A shinobi's life is not measured by how they lived, but rather what they managed to accomplish before their death."** > This engine brings the power of the Hidden Leaf directly to your browser using advanced Computer Vision.

---

## 📺 Live Jutsu Demo
**[👉 CLICK HERE TO ACTIVATE YOUR CHAKRA](https://jeetrico.github.io/anime-ar-engine/)** *(Requires Camera Access. Works best on mobile devices like iPhone 17/Android High-End)*

---

## 🔥 Jutsu Manifestation
This isn't just a video overlay. It’s a **Real-Time Physics-Based Engine** that tracks 21 individual points on your hand to anchor the chakra perfectly to your palm.

### 🌪️ Rasen Shuriken (Right Hand)
* **Formation:** Starts from a swirling core at `0.0s`.
* **Stability:** Once formed, the engine loops from `3.4s` to maintain a high-velocity aura.
* **Chakra Growth:** The longer you hold your hand open, the larger the Rasengan grows, simulating a massive chakra build-up.

### ⚡ Chidori / Raikiri (Left Hand)
* **Static Discharge:** Instant activation with high-frequency purple lightning.
* **Infinite Loop:** Seamlessly loops from `0.0s` to maintain the "1000 Birds" chirping effect.
* **Palm Anchor:** Specifically coded to sit flat against the palm for realistic "thrusting" poses.

---

## 🛠️ Secret Scrolls (Technical Specs)
* **Logic Gatekeeper:** Uses `wasOpen` state tracking to prevent video "stutter" during hand movements.
* **TimeUpdate Sync:** Unlike standard `ended` events, this uses a `0.1s` buffer check for zero-frame-drop looping.
* **Raw Quality Path:** 1:1 Camera passthrough. No filters, no dullness—just pure iPhone sensor quality.



## 📂 Repository Structure
```text
├── index.html          # The Core Jutsu Logic
├── assets/             # VFX Scrolls (MP4 Files)
│   ├── jeet_left_aura.mp4
│   └── jeet_right_aura.mp4
├── LICENSE             # MIT Protection
└── README.md           # This scroll
