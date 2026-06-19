# 🦆 QUACK.DRAW

**Draw in the air. Let the AI guess.**

QUACK.DRAW is a finger-tracking drawing game inspired by Google's Quick Draw — except there's no mouse, no keyboard, just your hand in front of a webcam. Point, draw, and watch an AI try to figure out what you sketched, all in real time.

🔗 **Live:** [quack-draw.vercel.app](https://quack-draw.vercel.app/)

---

## How It Works

1. **Show your hand** — point your index finger at the camera to begin drawing
2. **Draw in the air** — move your finger to draw directly on the live video feed
3. **AI guesses** — the model recognizes your doodle in real time, before the 20-second timer runs out

## Features

- ✋ Real-time finger tracking via **MediaPipe**
- 🧠 Live sketch recognition powered by **ml5.js**, trained on the **Quick Draw dataset**
- ⏱️ 20-second round timer for that quick-draw pressure
- ☁️ Zero installation — runs entirely in the browser
- 🦆 Pixel-art duck companion for that extra bit of charm

## Tech Stack

- **JavaScript** — core game logic
- **MediaPipe** — hand and finger landmark detection from the webcam feed
- **ml5.js** — in-browser ML inference for doodle recognition
- **Canvas API** — real-time drawing surface mapped to finger movement
- **Vercel** — static deployment

## Why I Built This

Wanted to explore computer-vision-driven interaction without relying on a mouse or keyboard — using just hand tracking as the entire input method, then pairing it with a lightweight ML model for real-time classification. It's a fun intersection of CV, on-device ML, and playful UI/UX.

## Credits

Inspired by Google's [Quick Draw](https://quickdraw.withgoogle.com/) experiment. Dataset used under Creative Commons license, with acknowledgement.

---

© 2026 QUACK.DRAW 🦆
