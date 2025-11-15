# 💡 Realistic Bulb for Three.js & WebXR

Ultra-realistic 3D light bulb component with custom GLSL shader.  
**WebXR ready** - Optimized for Meta Quest 2/3.

![Demo](images/demo.gif)

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

## 🎮 Live Demos

| Demo | Description | Link |
|------|-------------|------|
| **Interactive Simulator** | Full-featured lighting simulator | [Try it](https://wory-bonbon.github.io/threejs-realistic-bulb/) |
| **WebXR Version** | Quest/PC compatible standalone | [Try it](https://wory-bonbon.github.io/threejs-realistic-bulb/webxr-bulb.html) |
| **Minimal Example** | Shader-only, clean code | [Try it](https://wory-bonbon.github.io/threejs-realistic-bulb/shader-bulb.html) |

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

## 🎓 For Beginners

**New to Three.js?** Start here:
1. Open `shader-bulb.html` in browser
2. View source code
3. Copy `createShaderBulb()` function
4. Paste into your project
5. Customize colors/position

**New to WebXR?** Check `webxr-bulb.html` for:
- Device detection
- Quality auto-switching
- VR controller integration

---

## 🤝 Contributing

This is a learning project by a metaverse beginner!  
Feedback, issues, and PRs welcome.

---

## 📄 License

MIT License - Use freely in personal/commercial projects

---

## 🙏 Acknowledgments

Built with:
- Three.js r128
- Inspired by real incandescent bulb physics
- Tested on Meta Quest 2

---

**⭐ Star this repo if you use it in your metaverse project!**
```

---

## GitHubトピック追加

リポジトリページ → About の歯車 → Topics:
```
threejs
webxr
metaverse
vr
3d-graphics
shader
glsl
meta-quest
virtual-reality
web3d