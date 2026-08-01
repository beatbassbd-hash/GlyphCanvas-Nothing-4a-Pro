# GlyphCanvas-Nothing-4a-Pro

> An interactive creation studio and dynamic ambient companion for the Nothing Phone (4a) Pro Glyph Matrix.

`GlyphCanvas-Nothing-4a-Pro` turns the rear LED matrix of the Nothing Phone (4a) Pro into a live creative playground and ambient display. Draw pixel-by-pixel, stream dynamic photo dithering, scroll emoji-rich marquee text, and run low-power background clock and audio visualizers without interrupting core Nothing OS functions.

---

##  Key Features

### Interactive Studio Mode

* **Pixel-Perfect Canvas:** Direct 1:1 matrix editing with freehand draw, shape tools (lines, boxes, circles), eraser, and multi-step Undo/Redo.
* **Custom Image Import & Dithering:** Load photos from your gallery or camera with real-time 1-bit Floyd-Steinberg and Atkinson dithering optimized for monochrome LEDs.
* **Text & Emoji Engine:** Custom 5x7 bitmap renderer supporting marquee text scrolling with full emoji mapping for dot-matrix displays.
* **Animation Suite:** Build tiny frame-by-frame animations with onion-skinning controls, loop speeds, and procedural effect presets (Pulse, Wave, Glitch, Shimmer).

### Native Integration & Interoperability

* **Signature Nothing Aesthetic:** Built strictly adhering to Nothing's design guidelines with Ndot typography, pure monochrome theme, retro-futuristic audio feedback, and micro-haptic controls.
* **Zero System Interference:** Seamlessly hands over Matrix control to Nothing OS for incoming ringtones, system alarms, timers, and Essential Notifications.

---

## Tech Stack & Requirements

### System Requirements

* **Language:** Kotlin
* **Target Operating System:** Android 13+ / Nothing OS
* **Core Dependency:** Nothing GlyphMatrix Developer Kit

### Required Device Permissions

* **Glyph Matrix Access:** Required to control the hardware LED grid on the rear panel.
* **Audio Sampling:** Required to sample output frequency bands for the dynamic music visualizer.
* **Background Service Registration:** Required to keep the ambient clock and battery meters running when the app is minimized.

---

## Getting Started

### Prerequisites

1. Nothing Phone (4a) Pro with Developer Options enabled.
2. Android Studio (Ladybug release or newer) installed with Java Development Kit 17 or higher.

### Installation Process

-Download the GlyphCanvas.apk file on your Nothing 4a pro and run the file

---
Made by Nothing Community
This project is open-source
