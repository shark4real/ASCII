# ASCII Art Generator

A retro-styled web application that converts webcam feeds or images into real-time ASCII art. Features a cyberpunk terminal interface with multiple rendering modes and customization options.

## Features

### Input Sources
- **Live Webcam**: Real-time ASCII rendering from your camera
- **Image Upload**: Convert static images to ASCII art

### Rendering Options
- **Character Sets**: Complex, Simple, Binary, Blocks, Braille, Waves, or Custom
- **Font Size**: Adjustable from 4px to 20px
- **Image Adjustments**: Contrast, Brightness, and Saturation controls
- **Color Modes**: Matrix (green), White, Amber, Cyan, Full Color, or Inverted

### Export Capabilities
- Download as PNG image
- Copy ASCII text to clipboard
- Copy as formatted HTML

### User Interface
- Desktop sidebar controls
- Mobile-friendly bottom sheet interface
- Responsive design (mobile, tablet, desktop)
- Real-time FPS counter
- Live grid dimensions display
- Keyboard shortcuts support

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `W` | Toggle webcam |
| `S` | Save as PNG |
| `C` | Copy ASCII text |
| `+` | Increase font size |
| `-` | Decrease font size |

## Color Schemes

- **Matrix**: Classic green-on-black terminal aesthetic
- **Amber**: Vintage CRT monitor look
- **Cyan**: Cool neon effect
- **Color**: Full RGB color mapping from source
- **White**: Clean monochrome
- **Invert**: Black on white

## Character Sets

- **Complex**: Rich detail with 68 characters
- **Simple**: Basic ASCII with 11 characters
- **Binary**: Just `0` and `1`
- **Blocks**: Unicode block characters
- **Braille**: Braille Unicode patterns
- **Waves**: Wave and tilde characters
- **Custom**: Enter your own character set

## Technical Details

- Single HTML file (no build required)
- Pure JavaScript (no dependencies)
- Real-time rendering using Canvas API
- Optimized luminance-to-character mapping
- Mobile-responsive CSS Grid layout
- Scanline CRT effect overlay

## Browser Requirements

- Modern browser with:
  - HTML5 Canvas
  - getUserMedia API (for webcam)
  - CSS Grid
  - ES6 JavaScript support

## Performance

- Real-time FPS display
- Automatic grid calculation based on viewport and font size
- Efficient pixel sampling and character mapping
- Optimized for 30 FPS webcam feeds

## Controls Panel Sections

1. **Input Source**: Webcam and image upload buttons
2. **Render Settings**: Font size, contrast, brightness, saturation sliders
3. **Character Set**: Preset options and custom character input
4. **Color Mode**: 6 color scheme buttons
5. **Export**: PNG download, text copy, and HTML copy buttons

## Getting Started

1. Open `index.html` in a modern web browser
2. Click "▶ Webcam" to start live streaming or "⬆ Upload Image" to load an image
3. Adjust rendering settings using the sidebar controls
4. Export your ASCII art using one of the export options

## Responsive Breakpoints

- **Mobile** (< 600px): Bottom sheet control panel
- **Tablet** (900px): Reduced sidebar width
- **Desktop** (> 1400px): Expanded panel padding
- **Small Phones** (< 380px): Hidden secondary buttons

## Tips

- Use higher contrast values for images with low contrast
- Braille character set provides the most detail in small font sizes
- Decrease font size for more detail, increase for abstract effect
- Custom character sets work best with 5-20 characters
- Webcam performance depends on browser and hardware capabilities

## License

Open source - feel free to modify and share
