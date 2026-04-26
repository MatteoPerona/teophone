# 🪨 teophone

A rhythm instrument for the browser. Drop balls into a box and let physics make the beat.

![teophone demo](demo.gif)

## 🎯 How it works

Press keys to spawn objects that bounce around the screen. Every collision produces a percussive sound. Rhythm emerges from the geometry of their paths.

## 🎮 Controls

### Spawn
- **A thru L** spawn a ball at your cursor. Each key = different size, pitch, tone
- **Shift + A thru L** spawn a square. Squares only move horizontally or vertically
- **Speed slider** (right edge) controls launch speed. Set to 0 to spawn frozen 🧊

### Interact
- **Click empty space** freeze all objects ✋
- **Click + drag empty space** (throw mode) set all objects to the same velocity and direction
- **Click a ball** (throw mode) freeze it, drag to aim, release to throw 🏏
- **Click a ball** (drag mode) reposition without changing its speed
- **Right-click a ball** remove it 💀
- **Cmd/Ctrl + Z** undo last spawn
- **Escape** clear everything

### Modes
- **Q** toggle between throw and drag mode
- **Space** pause / play ⏸️

### 🥁 Rhythm
- **BPM** (top left) sets the tempo. All collision sounds quantize to a grid
- **Pulses** (bottom left) subdivisions per measure. Try odd numbers like 5, 7, or 19 for weird polyrhythms

### 🔊 Sound
- Click the **key hint box** (bottom right) to open the sound menu
- Upload your own audio samples for any key 🎤

## 🚀 Run

Open `index.html` in a browser.
