# Palmtone

Play music with your hand. A webcam + [MediaPipe Hand Landmarker](https://developers.google.com/mediapipe) track your hand in the browser; [Tone.js](https://tonejs.github.io/) turns its position and shape into sound.

## Controls
- **Point** one finger — hold a note, slide up/down to bend pitch
- **Open & spread** your hand — swell a chord
- **Fist** — go quiet
- Left/right hand position shapes filter brightness and stereo pan
- Switch **instrument** (theremin / bass / marimba / bell) and **scale** (pentatonic / major / minor / blues) from the top-right menus

Everything runs client-side — no build step, no server, no data leaves the browser except the model files loaded from CDN.

## Run locally
Just open `index.html` in a browser (Chrome/Edge recommended) and allow camera access.

## Deploy
Static site, zero config — works as-is on Vercel, Netlify, GitHub Pages, or any static host.
