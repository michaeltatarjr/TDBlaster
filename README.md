# Tone Lab/Tatabugs Deuterium Blaster

A progressive web app tone generator with overtone series control.

## How to Use

### Quick Start (Local)

Serve the files with any local HTTP server. For example:

```bash
# Python
python -m http.server 8000

# Node.js (npx, no install needed)
npx serve .

# PHP
php -S localhost:8000
```

Then open `http://localhost:8000` on your phone (both devices must be on the same network, use your computer's local IP like `http://192.168.x.x:8000`).

### Install on Phone

1. Open the URL in Chrome (Android) or Safari (iOS)
2. Tap the browser menu
3. Select "Add to Home Screen" / "Install App"
4. The app will now launch fullscreen like a native app

### PWA Icons

Open `generate-icons.html` in a browser, right-click each canvas, and save as `icon-192.png` and `icon-512.png` in this folder. These are needed for the home screen icon.

## Features

- **Pitch Control**: Large touch area — slide your finger up/down to change frequency (55 Hz to 2 kHz, logarithmic scale)
- **Note Display**: Shows current frequency, nearest note name, and cents deviation
- **Overtone Series**: 8 harmonics with individual amplitude sliders
- **Presets**: Pure, Saw, Square, Bell, Organ, Hollow, Bright, Fifth
- **Waveform Display**: Real-time oscilloscope visualization
- **Volume Control**: Master volume slider
- **Offline**: Works without internet once loaded (service worker caching)

## No App Store Required

This is a PWA (Progressive Web App). It runs in your browser and can be installed to your home screen without any app store. Works on both iOS and Android.
