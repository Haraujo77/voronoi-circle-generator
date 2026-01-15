# Voronoi Circle Generator

An interactive web application for generating beautiful Voronoi diagrams within a circular boundary. Features rounded corners, customizable colors, and SVG export.

## Features

- **Interactive Voronoi Generation**: Create Voronoi diagrams with customizable cell count
- **Rounded Corners**: Adjustable corner radius for smooth, organic shapes
- **Circular Boundary**: Voronoi cells form a perfect circle with curved edges
- **Color Customization**: Control line and fill colors
- **Two Control Modes**:
  - Direct mode: Set the number of cells directly
  - Area-based mode: Control cell size via area percentage
- **SVG Export**: Download your designs as vector graphics
- **Real-time Preview**: See changes instantly as you adjust parameters

## Usage

Simply open `voronoi.html` in a web browser. No build process or dependencies required - everything runs client-side.

## Controls

- **Number of Cells**: Adjust the complexity of the Voronoi diagram
- **Circle Diameter Ratio**: Control the size of the circle
- **Line Thickness**: Adjust stroke weight for Voronoi cells and circle
- **Corner Radius**: Round the corners of Voronoi cells (0 = sharp, higher = more rounded)
- **Corner Style**: Choose between MITER (sharp) or ROUND stroke joins
- **Colors**: Customize stroke and fill colors
- **Download SVG**: Export your design as a vector file

## Technologies

- p5.js for rendering
- d3-delaunay for Voronoi diagram generation
- Pure HTML/CSS/JavaScript - no build tools needed

## License

Free to use and modify.

