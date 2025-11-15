# 💡 Realistic Bulb for Three.js & WebXR

Ultra-realistic 3D light bulb component with custom GLSL shader.  
**WebXR ready** - Optimized for Meta Quest 2/3.

---

## 🎬 Demos

| Demo | Description | Link |
|------|-------------|------|
| **Interactive Simulator** | Full-featured lighting simulator | [Try it](https://wory-bonbon.github.io/threejs-realistic-bulb/) |
| **WebXR Version** | Quest/PC compatible standalone | [Try it](https://wory-bonbon.github.io/threejs-realistic-bulb/webxr-bulb.html) |
| **Minimal Example** | Shader-only, clean code | [Try it](https://wory-bonbon.github.io/threejs-realistic-bulb/shader-bulb.html) |

---

## 🎯 For Metaverse & Web3D Developers

- **Copy & paste ready** - Single function, no dependencies
- **VR optimized** - Auto quality switching for Quest
- **Customizable** - Color, intensity, multiple bulbs support
- **MIT License** - Use anywhere, even commercial projects

---

## 🚀 Quick Start

### Basic Usage
```javascript
// 1. Copy createHighQualityBulb() function from shader-bulb.html
// 2. Add to your scene
const bulb = createHighQualityBulb(0, 3, 0);
scene.add(bulb.group);
bulb.pointLight.intensity = 22;
bulb.pointLight.color.setHex(0xffaa33);
```

### WebXR Usage
See `webxr-bulb.html` for Meta Quest optimization

---

## ✨ Technical Features

### Custom GLSL Shader
- Fresnel effect (edge glow)
- Distance-based light falloff
- Height gradient illumination
- Realistic glass refraction (IOR 1.52)
- Flickering animation

### Geometry
- 220-point Bézier curve bulb shape
- 240-segment LatheGeometry
- Spiral tungsten filament (TubeGeometry)
- Accurate E26 socket model

### Performance
- **High Quality Mode**: Full shader effects (~60fps on desktop)
- **Low Quality Mode**: Quest-optimized (~72fps on Quest 2)
- Auto device detection

---

## 🛠️ Use Cases

- Metaverse lighting fixtures
- VR interior design apps
- Architectural visualization
- Web3D showcases
- Three.js learning projects

---

## 📦 What's Included
```
threejs-realistic-bulb/
├── index.html              # Interactive simulator (try all features)
├── webxr-bulb.html         # WebXR standalone (Quest ready)
├── shader-bulb.html        # Minimal example (copy from here)
├── README.md
└── LICENSE (MIT)
```

---

## 📄 License

MIT License - Use freely in personal/commercial projects

---

**⭐ Star this repo if you use it in your metaverse project!**