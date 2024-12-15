# SilkCursor 🖱️

## An Enchanting Interactive Cursor Experience


SilkCursor transforms your mouse cursor into a mesmerizing, fluid trail of motion. Using canvas animation and spring-physics simulation, it creates an elegant, responsive cursor effect that brings your web interface to life.

### ✨ Features

- **Fluid Motion**: Smooth, organic cursor trail
- **Responsive Design**: Works perfectly on all screen sizes
- **Cross-Device Support**: Compatible with mouse and touch devices
- **Pure JavaScript**: No external libraries required
- **Customizable**: Easy to tweak trail parameters

🚀 Quick Start

Installation

1. Clone the repository:
```bash
git clone https://github.com/[your-username]/SilkCursor.git
```

2. Open `index.html` directly in your browser

Integration into Your Project

```html
<!-- Add these to your HTML -->
<canvas></canvas>
<script src="script.js"></script>
```

🛠 Customization

Modify the `params` object in `script.js` to customize the trail:

```javascript
const params = {
    pointsNumber: 40,  // Number of points in the trail
    widthFactor: .3,   // Trail width variation
    spring: .4,        // Spring tension
    friction: .5       // Movement resistance
};
```

🤖 How It Works

The cursor trail is generated using canvas animation with a spring-physics approach:
- Each point in the trail follows the previous point
- Points have individual momentum and resistance
- Creates a natural, snake-like motion
- Adapts to mouse and touch interactions



🛡️ Browser Compatibility

- Chrome ✓
- Firefox ✓
- Safari ✓
- Edge ✓

🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

📋 Todo

- [ ] Add configuration options
- [ ] Create npm package
- [ ] Add color customization
- [ ] Improve touch device support

📄 License

Distributed under the MIT License. See `LICENSE` for more information.

🙌 Acknowledgements

- Inspired by creative web interaction designs
- Canvas animation techniques

📧 Contact

Your Name - Imran Mani

Project Link: [(https://github.com/Mani821/SilkCursor)](https://github.com/Mani821/SilkCusror)
