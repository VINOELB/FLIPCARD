# AI Concept Flip Cards

An interactive web component featuring flip cards that showcase AI concepts. This component is designed to be used either as a standalone web element or embedded within Articulate Storyline as a web object.

## Table of Contents
- [Features](#features)
- [File Structure](#file-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Storyline Integration](#storyline-integration)
- [Browser Compatibility](#browser-compatibility)
- [Troubleshooting](#troubleshooting)

## Features
- Interactive flip cards with smooth animations
- Responsive design that works across different screen sizes
- Clean, modern UI with gradient backgrounds
- Click/tap interaction for card flipping
- Hover effects for enhanced user experience

## File Structure
```
ai-flip-cards/
├── index.html      # Main HTML file
├── styles.css      # CSS styling
├── script.js       # JavaScript interactions
└── README.md       # Documentation
```

## Installation
1. Download all project files
2. Keep all files in the same directory
3. Maintain the original file names or update the references in `index.html` if you change them

## Usage
### Local Testing
1. Download all files to a local directory
2. Open `index.html` in a modern web browser
3. Click/tap on cards to see them flip

### Web Hosting
1. Upload all files to your web server
2. Maintain the file structure
3. Access via the main HTML file URL

## Customization

### Adding New Cards
Add new cards by copying and pasting this HTML structure inside the container div:
```html
<div class="flip-card">
    <div class="flip-card-inner">
        <div class="flip-card-front">
            <div>Your Question</div>
        </div>
        <div class="flip-card-back">
            <div>Your Answer</div>
        </div>
    </div>
</div>
```

### Modifying Styles
Common customization points in `styles.css`:
- Card dimensions: Modify `width` and `height` in `.flip-card`
- Colors: Update `background` in `.flip-card-front` and `.flip-card-back`
- Animation speed: Adjust `transition` timing in `.flip-card-inner`
- Font styles: Change `font-family`, `font-size`, and `line-height`

## Storyline Integration
1. Host the files on a web server
2. In Storyline:
   - Insert > Web Object
   - Enter the URL of your hosted index.html
   - Enable "Load automatically"
   - Set "Scale with slide" as needed
   - Recommended size: 1000x300 pixels

## Browser Compatibility
Tested and working in:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Modern mobile browsers

## Troubleshooting

### Common Issues
1. Cards not flipping:
   - Check if JavaScript is enabled
   - Verify script.js is properly linked

2. Styling not appearing:
   - Ensure styles.css is in the same directory as index.html
   - Check file paths in HTML

3. Layout issues:
   - Verify viewport meta tag is present in HTML
   - Check container width and responsive settings

### Support
For additional support or customization:
1. Check HTML console for errors
2. Verify all files are properly linked
3. Ensure server permissions are set correctly

## Notes
- Minimum recommended display width: 320px
- Optimal viewing width: 768px or larger
- Content is editable in the HTML file
- Animations use CSS transforms for better performance
