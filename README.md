# threejsfindinsideoutside

Interactive visualization of the point-in-polygon test using the winding-number algorithm, built with Three.js.

## Problem It Solves

Determining whether a point lies inside or outside an arbitrary (possibly concave) polygon is a classic computational geometry problem. This demo uses the **winding-number** approach—summing signed angles—to robustly classify points in real time.

## Features

- **Concave Polygon Support**  
  Handles any simple closed polyline, including concave shapes.  
- **Winding-Number Algorithm**  
  Computes sum of signed angles between the test point and each polygon edge to decide inclusion.  
- **Interactive Testing**  
  Click on the canvas to place test points; green = inside, red = outside.  
- **Orthographic View**  
  Preserves true 2D geometry without perspective distortion.  
- **Live Statistics**  
  Overlay shows total clicks, inside count, and outside count.  
- **Pure Client-Side**  
  No build tools or server required—just a modern browser and Three.js.

## Demo

https://jsfiddle.net/mbtLscdf/

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/z1000biker/threejsfindinsideoutside.git
   cd threejsfindinsideoutside
