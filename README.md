# ReflexLab — Match Hole

A small, touch-first orbit timing game inspired by the simple moving-dot / hole mechanic.

## How to play
- Start the game.
- Watch the white dot travel around the circular track.
- Tap the game area when the dot reaches the glowing gap.
- A successful match increases your score and reverses the dot's direction.
- A mistimed tap costs one life. You have three lives.
- Your best score is saved on the device.

## Project
- Single-page HTML, CSS and JavaScript.
- Canvas rendering with pointer/touch input.
- No external libraries, accounts, or network services required for gameplay.
- Offline support through the service worker.

## Web
Enable GitHub Pages in **Settings → Pages → Build and deployment → GitHub Actions**. The Pages workflow deploys on pushes to `main`.

## Android
The Android Actions workflow builds a debug APK. Open the latest successful Android build and download its artifact.
