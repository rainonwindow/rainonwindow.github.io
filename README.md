# Rain on Window 🌧️

A relaxing, interactive rain-on-glass simulator with realistic raindrops sliding down your window and ambient rain sounds. Perfect for relaxation, meditation, focus, or sleep.

🌐 **Live Demo:** [rainonwindow.github.io](http://rainonwindow.github.io)

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

- 🌧️ **Realistic Raindrops** — physics-based droplets with mass, gravity, trails, and random sticking behavior
- 🎵 **Dynamic Ambient Sound** — procedurally generated rain audio that adapts to intensity
- 🌐 **Multilingual Support** — Ukrainian (default) and English
- 💾 **Persistent State** — all your settings are saved in local storage
- 🖥️ **Fullscreen Mode** — immersive distraction-free experience
- 📱 **Responsive Design** — works on any screen, supports both portrait and landscape orientations
- ⌨️ **Keyboard Shortcuts** — quick access to controls
- 🎨 **Beautiful Visuals** — moody city lights and atmospheric fog effects

## 🎮 Controls

### Settings Panel
- **Intensity** — adjust the amount of rain (also affects sound)
- **Drop Size** — control the size of raindrops
- **Speed** — change how fast drops slide down
- **Sound** — toggle ambient rain audio on/off
- **Volume** — set audio level
- **Language** — switch between UA / EN

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `S` | Toggle settings panel |
| `F` | Toggle fullscreen |
| `Esc` | Hide settings panel |

## 🔊 Sound System

The audio is fully procedural — no external sound files needed. The rain sound dynamically responds to the intensity slider:

- **Low intensity** — soft, muffled drizzle with occasional drops
- **Medium intensity** — steady rainfall with regular droplet impacts
- **High intensity** — heavy downpour with bright, full sound and rapid drops

Audio is generated using the Web Audio API with brown noise, dynamic filters, and procedurally synthesized droplet impacts.

## 🚀 Getting Started

Simply open `index.html` in your browser. No build process, no dependencies, no installation required.

## 💡 Tips

- Click anywhere on the page first to enable audio (browser autoplay policy)
- Press `F` for the most immersive fullscreen experience
- Use it as a focus tool while working or studying
- Great background ambience for sleep or meditation

## 🛠️ Technical Details

Built with vanilla HTML, CSS, and JavaScript. Uses:

- **Canvas 2D API** for raindrop rendering
- **Web Audio API** for procedural sound generation
- **LocalStorage** for state persistence
- **Fullscreen API** for immersive mode

Single-file application — everything (HTML, CSS, JS, favicon) is contained in one file.

## 📄 License

MIT
