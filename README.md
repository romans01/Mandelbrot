# Mandelbrot Set Visualization

This project visualizes the Mandelbrot set using WebGL. The application allows users to interact with the Mandelbrot set by panning, zooming, and changing color schemes.

## Features

- **Panning**: Click and drag to move around the Mandelbrot set.
- **Zooming**: Use the mouse wheel to zoom in and out.
- **Color Schemes**: Select different color schemes from a dropdown menu.

## Getting Started

### Prerequisites

- A modern web browser with WebGL support.

### Running the Application

1. Open the `m1.html` file in your web browser.
2. Interact with the Mandelbrot set using the mouse and the color scheme dropdown.

### Controls

- **Pan**: Click and drag the mouse to move around.
- **Zoom**: Use the mouse wheel to zoom in and out.
- **Change Color Scheme**: Select a different color scheme from the dropdown menu.

## Code Overview

### Shaders

- **Vertex Shader**: Defines the position of vertices.
- **Fragment Shader**: Calculates the color of each pixel.

### JavaScript Functions

- **createShader**: Compiles a shader.
- **drawMandelbrot**: Renders the Mandelbrot set.
- **handleMouseDown**: Starts the panning action.
- **handleMouseMove**: Updates the position while panning.
- **handleMouseUp**: Ends the panning action.
- **handleWheel**: Handles zooming.
- **handleColorSchemeChange**: Changes the color scheme.

### Event Listeners

- **resize**: Redraws the Mandelbrot set when the window is resized.
- **mousedown**: Initiates panning.
- **mousemove**: Updates the view during panning.
- **mouseup**: Ends panning.
- **wheel**: Handles zooming.
- **change**: Changes the color scheme.

## License

This project is licensed under the MIT License.