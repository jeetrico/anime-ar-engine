# 🌀 JEETRICO: Anime AR Engine ⚡
### Real-Time Chakra Effects in Your Browser

![License](https://img.shields.io/badge/License-MIT-blueviolet)
![Platform](https://img.shields.io/badge/Platform-Web_AR-orange)
![Engine](https://img.shields.io/badge/Engine-MediaPipe_Hands-blue)
![Status](https://img.shields.io/badge/Status-Experimental-green)

> **"A shinobi’s life is not measured by how they lived, but rather what they managed to accomplish."**

JEETRICO Anime AR Engine is a **browser-based Augmented Reality system** that allows you to summon iconic anime chakra techniques using **real-time hand tracking and computer vision**.

No apps.  
No installation.  
Just open the page and **activate your chakra.**

---
## 📺 Live Jutsu Demo
**[👉 CLICK HERE TO ACTIVATE YOUR CHAKRA](https://jeetrico.github.io/anime-ar-engine/)**

⚠️ Camera permission required.

Works best on:

• iPhone  
• Android flagship devices  
• Chrome / Safari browsers  

---

# ✋ How It Works

The engine uses **MediaPipe Hands** to track **21 hand landmarks** in real time.

Pipeline:

1️⃣ Camera captures the video feed  
2️⃣ MediaPipe detects hand landmarks  
3️⃣ Engine checks if palm is open  
4️⃣ Jutsu VFX attaches to palm anchor  
5️⃣ Chakra effect grows dynamically  

---

# 🔥 Jutsu System

## 🌪️ Rasen Shuriken (Right Hand)

When your **right palm opens**, the engine generates a rotating chakra sphere.

Features:

• Starts with swirling chakra core  
• Mid-animation loop for smooth aura  
• Dynamic chakra expansion  
• Anchored slightly above the palm  

Energy growth logic:

```javascript
if(handOpen){
   rasenganSize += chakraPower
}
```

The longer you hold the palm open, the **larger the Rasengan grows**.

---

## ⚡ Chidori / Raikiri (Left Hand)

Opening your **left palm** activates high-voltage lightning chakra.

Features:

• Instant activation  
• Continuous lightning animation  
• Infinite looping effect  
• Perfect palm-center alignment  

Inspired by the legendary **Raikiri technique**.

---

## ⚔️ Jutsu Clash Detection

When **both hands activate simultaneously**, the engine detects a chakra clash.

HUD Warning:

```
⚠️ JUTSU CLASH DETECTED ⚠️
```

Future versions will trigger:

💥 Chakra explosion  
⚡ Lightning discharge  
🌪️ Energy shockwave  

---

# 🧠 Engine Architecture

The system prevents animation glitches using **state-tracking logic**.

Example:

```javascript
if (!wasOpen[idx]) {
    vidRasengan.currentTime = 0;
    vidRasengan.play();
}
```

Key components:

| Component | Role |
|----------|------|
MediaPipe Hands | Hand landmark detection |
Gesture Logic | Detect open / closed palm |
Video VFX | Chakra animations |
Canvas Renderer | Skeleton tracking overlay |

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
HTML5 | UI structure |
CSS3 | Chakra glow effects |
JavaScript | Engine logic |
MediaPipe Hands | Real-time hand tracking |
Canvas API | Skeleton rendering |
MP4 overlays | Anime chakra VFX |

---

# 📂 Repository Structure

```
anime-ar-engine
│
├── index.html
│   └── Core AR engine
│
├── assets
│   ├── jeet_left_aura.mp4
│   └── jeet_right_aura.mp4
│
├── LICENSE
└── README.md
```

---

# 🚀 Running the Project Locally

Clone the repository:

```
git clone https://github.com/jeetrico/anime-ar-engine.git
```

Open the project folder:

```
cd anime-ar-engine
```

Run a local server:

```
python -m http.server
```

Open browser:

```
http://localhost:8000
```

---

# 📱 Performance Notes

For best tracking accuracy:

✔ good lighting  
✔ clear background  
✔ hand fully visible  

Mobile cameras usually provide **better tracking performance**.

---

# 🔮 Future Upgrades

Planned features:

• 💥 Chakra explosion system  
• ⚡ Lightning particle engine  
• 🎮 Gesture-based jutsu selection  
• 🎥 AR recording feature  
• 🧠 AI gesture recognition  
• 🌀 Multiple anime abilities  

---

# 👨‍💻 Author

**Jeet Banerjee**

GitHub  
https://github.com/jeetrico

---

# 📜 License

MIT License

You are free to:

✔ use  
✔ modify  
✔ distribute  

---

# ⭐ Support the Project

If this project awakened your chakra:

⭐ Star the repository  
🍴 Fork the project  
🚀 Build your own anime AR powers
