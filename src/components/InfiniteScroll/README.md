# Infinite Scroll Component for Shopify

## Overview
This component provides an infinite horizontal scroll effect, which can be used in Shopify themes. The implementation is available in Liquid for Shopify and also as a Vanilla JavaScript version.

## Features
- Infinite horizontal scrolling of images
- Customizable autoplay speed (slow, medium, fast)
- Adjustable heading size and text
- Configurable padding
- Supports image inversion

## Files Structure
```
/project-root
│── vanilla/             # Vanilla JavaScript version
│   ├── index.html
│   ├── index.js
│   ├── index.css
│── index.liquid         # Shopify-compatible version
│── README.md
```

## Installation (Shopify Version)
1. Copy the contents of `index.liquid`.
2. Navigate to your Shopify theme editor.
3. Create a new section and paste the copied code.
4. Save and add the section to your theme.

## Installation (Vanilla JS Version)
1. Copy the `vanilla/` folder into your project.
2. Ensure `index.html` includes `index.js` and `index.css`.
3. Open `index.html` in a browser to see the effect.

## Customization
You can adjust the settings in the schema:
- **Color Scheme**: Change the section's color theme.
- **Heading**: Modify the text displayed at the top.
- **Heading Size**: Choose from different heading sizes.
- **Autoplay Speed**: Set the speed to slow (60s), medium (40s), or fast (20s).
- **Padding**: Adjust the top and bottom padding values.
- **Image Inversion**: Toggle inversion of images.

## Demo
Check out the working demo on CodePen:
[View on CodePen](https://codepen.io/xrwniksu-the-encoder/pen/NPWvgBy)

## License
This component is open-source and can be freely modified and used in projects.

