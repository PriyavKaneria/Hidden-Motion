# Hidden Motion Detection

A real-time web application that reveals invisible motion using frame difference analysis. Built with vanilla JavaScript and HTML5 Canvas, this tool makes subtle movements visible to the human eye.

![Hidden Motion Demo](https://img.shields.io/badge/Status-Live-brightgreen) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow) ![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)

## 🚀 Live Demo

[**Try Hidden Motion Detection**](https://hiddenmotion.priyavkaneria.com)

## 🔬 Real-World Applications

Frame difference analysis is a powerful technique used across multiple industries:

### 🏭 **Industrial & Manufacturing**
- **Gas Leak Detection** - Invisible gas escapes become visible through air density changes
- **Heat Loss Identification** - Thermal inefficiencies in buildings and equipment
- **Vibration Analysis** - Detecting mechanical wear in rotating machinery
- **Quality Control** - Spotting defects in manufacturing processes

### 🔬 **Scientific Research**
- **Fluid Dynamics** - Visualizing air currents and turbulence patterns
- **Structural Engineering** - Monitoring building sway and bridge oscillations
- **Medical Imaging** - Detecting subtle tissue movements and blood flow
- **Seismic Analysis** - Early detection of ground movement

### 🏠 **Security & Monitoring**
- **Perimeter Security** - Detecting intrusions in low-light conditions
- **Wildlife Monitoring** - Tracking animal movement without disturbance
- **Traffic Analysis** - Understanding pedestrian and vehicle flow patterns
- **Home Automation** - Motion-triggered systems with high sensitivity

### 🎯 **Environmental Monitoring**
- **Air Quality Assessment** - Visualizing pollution and particulate movement
- **Water Flow Analysis** - Detecting leaks in pipes and water systems
- **Weather Pattern Studies** - Analyzing micro-climates and wind patterns

## 📚 Educational Resources

Learn more about motion detection and computer vision:

- [**The Power of Frame Differencing**](https://www.youtube.com/watch?v=zFiubdrJqqI) - Comprehensive overview of frame difference techniques
- [**Advanced Motion Detection Methods**](https://www.youtube.com/watch?v=rEoc0YoALt0) - Professional applications and algorithms

## 🌟 Features

- **Real-time Motion Detection** - Processes camera feed at maximum frame rate
- **Customizable Frame Difference** - Choose between 2-frame or 3-frame difference analysis
- **Smooth Motion Trails** - Beautiful sea-green curved paths showing object movement history
- **Velocity Indicators** - Real-time speed and direction vectors with position display
- **Rainbow Mode** - Cycling HSV colors for enhanced motion visualization
- **Space Background** - Animated starfield with rotating nebula effects
- **Fullscreen Support** - Immersive detection experience
- **Responsive Controls** - Collapsible settings panel with real-time adjustments

## 🛠️ How It Works

The application uses **temporal differencing** to detect motion:

1. **Frame Capture** - Continuously captures video frames from your camera
2. **Grayscale Conversion** - Converts color frames to grayscale for processing efficiency
3. **Frame Comparison** - Compares current frame with previous frame(s) pixel by pixel
4. **Threshold Application** - Filters out noise using configurable sensitivity thresholds
5. **Region Detection** - Groups adjacent motion pixels into coherent objects
6. **Velocity Calculation** - Tracks object centers to compute speed and direction
7. **Trail Generation** - Creates smooth curved paths showing movement history

## 🔧 Technical Details

- **Language**: Vanilla JavaScript (ES6+)
- **Rendering**: HTML5 Canvas API
- **Video**: WebRTC getUserMedia API
- **Graphics**: SVG for smooth trail rendering
- **Performance**: Optimized flood-fill algorithm for region detection
- **Browser Support**: Modern browsers with camera access

## 🎨 Customization

The application supports extensive customization:

- **Sensitivity Thresholds** - Adjust motion detection sensitivity
- **Color Schemes** - Custom colors for motion and static areas
- **Trail Behavior** - Modify trail length and fade patterns
- **Velocity Smoothing** - Configure motion smoothing algorithms

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs and issues
- 💡 Suggest new features
- 🔧 Submit pull requests
- 📚 Improve documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Created By

**Priyav Kaneria** ([@_diginova](https://x.com/_diginova))

One of [many experiments](https://projects.priyavkaneria.com) • Made with ❤️

---

*Hidden Motion Detection - Making the invisible visible through the power of computer vision*
