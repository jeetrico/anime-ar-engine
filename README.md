🌀 JEETRICO: Anime AR Engine ⚡
Real-Time Chakra Effects in Your Browser








“A shinobi’s life is not measured by how they lived, but rather what they managed to accomplish.”

JEETRICO Anime AR Engine is a browser-based augmented reality system that lets you summon iconic anime chakra techniques using only your camera and hand gestures.

No apps.
No downloads.
Just open the page and activate your chakra.

🎥 Live Demo

👉 Activate the engine

https://jeetrico.github.io/anime-ar-engine/

⚠️ Camera access required

Best experience on:

• iPhone
• Android flagship devices
• Chrome / Safari

✋ How It Works

The engine uses MediaPipe Hands to track 21 hand landmarks in real time.

Pipeline:

1️⃣ Camera captures the video feed
2️⃣ MediaPipe detects hand landmarks
3️⃣ Engine checks gesture state
4️⃣ VFX video attaches to palm anchor
5️⃣ Chakra effect grows dynamically

🔥 Jutsu System
🌪️ Rasen Shuriken (Right Hand)

When your right palm opens, the engine generates a rotating chakra sphere.

Features:

• Starts with swirling chakra core
• Mid-animation loop for smooth aura
• Dynamic chakra expansion
• Anchored above the palm

Energy growth logic:

Open hand longer → Chakra size increases
⚡ Chidori / Raikiri (Left Hand)

Opening your left palm activates lightning chakra.

Features:

• Instant activation
• High-frequency lightning effect
• Infinite loop animation
• Palm-center anchor for thrust poses

Inspired by the legendary Raikiri technique.

⚔️ Jutsu Clash Detection

When both hands activate simultaneously, the engine detects a clash.

HUD warning appears:

⚠️ JUTSU CLASH DETECTED ⚠️

Future versions will trigger:

💥 Chakra explosion
⚡ Lightning discharge
🌪️ Energy shockwave

🧠 Engine Architecture

The system prevents animation glitches using state tracking logic.

Example:

if (!wasOpen[idx]) {
    vidRasengan.currentTime = 0;
    vidRasengan.play();
}

Key components:

Component	Role
MediaPipe Hands	Hand landmark detection
Gesture Logic	Detect open/closed palm
Video VFX	Chakra animations
Canvas Renderer	Skeleton tracking overlay
🛠️ Technology Stack
Technology	Purpose
HTML5	UI structure
CSS3	Chakra glow effects
JavaScript	Engine logic
MediaPipe Hands	Real-time hand tracking
Canvas API	Skeleton rendering
MP4 VFX overlays	Anime chakra visuals
📂 Project Structure
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
🚀 Running the Project Locally

Clone the repository:

git clone https://github.com/jeetrico/anime-ar-engine.git

Navigate into the folder:

cd anime-ar-engine

Run a local server:

python -m http.server

Open browser:

http://localhost:8000
📱 Performance Notes

For best tracking accuracy:

✔ good lighting
✔ plain background
✔ hand visible in frame

Mobile devices provide smoother tracking than most webcams.

🔮 Future Upgrades

Planned improvements:

• 💥 Chakra explosion system
• ⚡ Lightning particle engine
• 🎮 Gesture-based jutsu selection
• 🎥 AR recording feature
• 🧠 AI gesture recognition
• 🌀 Multiple anime abilities

👨‍💻 Author

Jeet Banerjee

GitHub
https://github.com/jeetrico

📜 License

MIT License

You are free to:

✔ use
✔ modify
✔ distribute

⭐ Support the Project

If you like the project:

⭐ Star the repository
🍴 Fork the project
🚀 Build your own anime AR powers

✨ Activate your chakra. Summon your jutsu.
