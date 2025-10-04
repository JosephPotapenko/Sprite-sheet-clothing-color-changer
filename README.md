# Sprite Sheet Clothing Color Changer

A powerful web-based tool for manipulating colors in sprite sheets and pixel art. Perfect for game developers, pixel artists, and anyone needing to change clothing colors, equipment variations, or create color palettes for sprites.

*Created with the assistance of AI technology.*

## Features

### 🎨 **Intelligent Color Extraction**
- Automatically extracts diverse color palettes from uploaded images
- Uses K-means clustering algorithm to find the most representative colors
- Handles transparency and filters out near-transparent pixels
- Optimized for sprite sheets and pixel art

### 🖼️ **Advanced Image Viewing**
- **Zoom & Pan**: Mouse wheel to zoom, drag to pan around large sprites
- **Pixel-perfect rendering**: Maintains crisp pixel art appearance at all zoom levels
- **Double-click to reset**: Instantly center and reset zoom
- **Ctrl/Cmd + wheel**: Alternative zoom control

### 🎭 **Sophisticated Color Manipulation**
- **Individual color selection**: Click any palette color to highlight it in the image
- **Group selection**: Ctrl/Cmd + click to select multiple colors for batch editing
- **Hue shifting**: Change the hue of selected colors while preserving saturation
- **Lightness adjustment**: Make colors lighter or darker
- **Visual feedback**: Selected colors glow with blue outline

### 🔧 **Professional Tools**
- **Color merging**: Automatically combine similar colors with adjustable threshold
- **Undo/Redo system**: Full history tracking with up to 60 steps
- **Real-time preview**: See changes instantly on your sprite
- **High-quality export**: Download processed images at original resolution

### 🎯 **Precision Controls**
- **Slider controls**: Fine-tune hue (0-360°) and lightness (0-100%)
- **Arrow buttons**: Make precise single-degree/percent adjustments
- **Smart averaging**: When multiple colors are selected, sliders show their average values
- **Absolute positioning**: Set exact hue and lightness values

## How to Use

### Getting Started
1. **Load an Image**: Click "Choose File" and select your sprite sheet or pixel art
2. **Wait for Processing**: The tool automatically extracts the color palette
3. **Start Editing**: Select colors and adjust them using the tools

### Basic Workflow
1. **Select Colors**: 
   - Click a palette swatch to highlight that color in the image
   - Ctrl/Cmd + click multiple swatches to group them together
   - Selected colors will have a blue glow effect

2. **Adjust Colors**:
   - Use the **Hue slider** to shift colors around the color wheel
   - Use the **Lightness slider** to make colors darker or lighter
   - Use **arrow buttons** for precise single-unit adjustments
   - Click **"Apply to Selected"** to confirm changes

3. **Advanced Operations**:
   - **Merge Similar Colors**: Adjust threshold slider and click "Merge" to combine similar shades
   - **Undo/Redo**: Use history buttons to step back/forward through changes
   - **Reset**: Return to original image and palette

4. **Export**: Click **"Download PNG"** to save your modified sprite at full resolution

### Color Selection Techniques
- **Single color**: Click once to select and highlight
- **Multiple colors**: Hold Ctrl/Cmd and click to build a selection group
- **Clear selection**: Click "Clear Selection" or press Esc
- **Visual feedback**: Selected colors have blue glowing borders

### Pro Tips
- **Clothing recoloring**: Select all parts of an outfit (shadows, highlights, base color) then adjust hue together
- **Batch processing**: Group similar colors and adjust them simultaneously for consistent results
- **Color merging**: Use 5-15% threshold to combine very similar shades and reduce palette complexity
- **Precision work**: Use arrow buttons for fine adjustments instead of dragging sliders

## Technical Features

- **K-means color clustering** for intelligent palette extraction
- **HSL color space manipulation** for natural-looking color shifts  
- **Canvas-based rendering** with zoom/pan support
- **History system** with branching support
- **Pixel-perfect scaling** maintains crisp sprite appearance
- **Full-resolution processing** - display scaling doesn't affect output quality

## Browser Compatibility

Works in all modern browsers that support:
- HTML5 Canvas
- ES6+ JavaScript
- CSS Grid and Flexbox
- File API for image loading

Tested on Chrome, Firefox, Safari, and Edge.

## Use Cases

### Game Development
- Create color variations for character clothing/armor
- Generate team uniforms or faction colors  
- Produce different material types (metal, wood, fabric)
- Make seasonal or regional variants

### Pixel Art
- Experiment with different color schemes
- Create color-coordinated sprite families
- Generate palette variations for mood/lighting
- Clean up and optimize color palettes

### Digital Art
- Recolor existing artwork
- Create themed variations
- Standardize color palettes across multiple sprites
- Generate complementary color schemes

## File Structure

```
├── index.html          # Main application file with embedded CSS/JS
├── style.css           # Additional styling (referenced from HTML)  
├── script.js           # Minimal JavaScript connection test
├── README.md           # This documentation
└── favicons/           # App icons and manifest files
    ├── favicon.ico
    ├── favicon.svg
    └── ... (various icon sizes)
```

## Local Development

1. Clone or download this repository
2. Open `index.html` in a web browser
3. No build process or dependencies required - runs completely in the browser

For local development server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP  
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## Contributing

This project was created with AI assistance and is open for improvements. Potential enhancements:
- Support for additional image formats
- Batch processing multiple files
- Custom palette import/export
- Advanced color harmony tools
- Animation frame support

## License

Open source - feel free to use, modify, and distribute.

---

*This tool demonstrates the power of combining traditional computer graphics algorithms with modern web technologies to create intuitive creative software.*