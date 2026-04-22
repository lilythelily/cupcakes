# Cupcakes Motion Graphics Bundle (v1.0.0) Documentation

## Overview

A visual asset bundle featuring delightful cupcake artwork. This package includes vector illustrations meticulously created in Adobe Fresco and Adobe Illustrator, Pre-rendered MP4 Video, CSS @keyframes Animation code, and a sample section code.

## Code Base Structure

```
sweets-dev/
├── asset/              # Standalone vector source(backup)
├── css/                # Contains css animation logic 
├── index.html          # Container for the strawberry cupcake animation with Inline SVG code
├── lemon.html          # Container for the lemon cupcake animation with Inline SVG code
└── readMe.md           # Documentation

```

### index.html

Contains the animation container for the strawberry cupcake. The SVG code is embedded inline to allow for direct CSS manipulation of individual elements (e.g., strawberry).

### lemon.html

Contains the animation container for the lemon cupcake. The SVG code is embedded inline to allow for direct CSS manipulation of individual elements (e.g., lemon-2).

### strawberry.css

Contains layout styling and the @keyframes animation logic for the strawberry cupcake.

### lemon.css

Contains layout styling and the @keyframes animation logic for the lemon cupcake.


## How to Use

The vector illustrations are embedded in the "index.html" and "lemon.html" within <svg></svg> tags. 

To add an animation to your project:

1.  **Open 'index.html' or 'lemon.html' file** 
Copy the entire code block inside <body></body> tags.

2.  **Open 'strawberry.css' or 'lemon.css' file** 
Copy all the code into your css file.

## Customization

**Change background color** You can easily adjust the background color in the ":root" section of the CSS file. 

Example (from white background to black background):

Before🎨 --background-color: #ffffff;
After🎨 --background-color: #000000;

## License

This project is licensed for personal and commercial use. Redistribution or resale of the file itself is not permitted.
