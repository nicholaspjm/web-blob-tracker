# blob tracker

High-performance blob tracking that runs entirely in your browser. Built with vanilla JavaScript and optimized for real-time performance.

**[Try it live](https://nicholaspjm.github.io/web-blob-tracker/)**



## Features

TBD

## Usage

### Online

Just visit the [live demo](https://nicholaspjm.github.io/web-blob-tracker/) and click "toggle camera"

### Local

1. Download `index.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Click "toggle camera" and allow camera access
4. Adjust settings in the sidebar

## Controls

### Detection
- **Threshold** - Brightness cutoff for blob detection (0-255)
- **Min/Max Area** - Size range for detected blobs
- **Max Blobs** - Maximum number of objects to track

### Performance
- **Resolution** - Detection quality (lower = faster)
- **Frame Skip** - Process every Nth frame for speed boost

### Style
- **Outline/Trail Color** - Customize tracking colors
- **Thickness** - Line weight for brackets and connections
- **Brackets** - Toggle corner brackets vs full boxes
- **Dotted** - Enable dashed line style

### Features
- **Trails** - Show smooth curved paths through blob centers
- **Connections** - Draw lines between nearby blobs
- **IDs** - Show blob identification numbers
- **Metrics** - Display tracking data overlay
- **Grid** - Technical grid overlay

### Smoothing
- **Motion** - Interpolation smoothness (0.0-1.0)
- **Line Smoothness** - Trail curve resolution (2-16)

## Technical Details

### Algorithm
- Connected component labeling via flood fill
- Catmull-Rom spline interpolation for smooth trails
- Exponential smoothing for stable motion tracking
- Frame skipping with cubic easing interpolation

### Performance
- **High quality**: 1.0 resolution, frame skip off = ~60 FPS
- **Balanced**: 0.75 resolution, frame skip 2 = ~90 FPS
- **Maximum speed**: 0.5 resolution, frame skip 3 = ~120 FPS

### Browser Support
- Chrome/Edge (recommended)
- Firefox
- Safari
- Any browser with WebRTC support

## Development

Built with:
- Vanilla JavaScript (no frameworks)
- HTML5 Canvas API
- WebRTC getUserMedia API
- Space Mono font

The entire application is contained in a single HTML file for maximum portability.

## Use Cases

- Visual performance tracking
- Interactive art installations
- Motion capture prototyping
- Computer vision education
- Creative coding experiments
- Real-time video effects

## Privacy

This application:
- ✅ Runs 100% locally in your browser
- ✅ Never sends video data to any server
- ✅ Processes everything on your device
- ✅ Works completely offline after loading
- ✅ No cookies, no tracking, no analytics

## License

N/A

## Credits


## Contributing

Issues and pull requests welcome! Ideas for improvements:
- GPU acceleration
- Recording/export functionality
- Custom color schemes
- Additional tracking algorithms
- Mobile optimization


