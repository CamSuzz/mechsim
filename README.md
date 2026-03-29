# MechSim

A lightweight, browser-based kinematic mechanism simulator for planar linkages. Design, simulate, and analyze 2D mechanisms in real-time with an intuitive visual interface.

## Features

- **Interactive Design**: Drag-and-drop mechanism builder with revolute, rail, arc, and circle slider joints
- **Real-time Simulation**: Newton-Raphson constraint solver with Levenberg-Marquardt damping
- **Live Visualization**: Smooth animation and motion tracking
- **Data Export**: CSV recorder with configurable sample rate and finite-difference derivatives
- **Responsive UI**: Mobile-friendly dark-themed interface
- **No Dependencies**: Pure JavaScript—runs entirely in the browser

## Getting Started

Open `index.html` in any modern web browser. No installation required.

## How to Use

1. **Build**: Click and drag to place links, joints, and sliders
2. **Configure**: Set link lengths and joint constraints
3. **Simulate**: Press Play to run the mechanism
4. **Export**: Record motion data to CSV for analysis

## Technical Details

- **Solver**: Newton-Raphson with constraint-based kinematics
- **Performance**: Optimized for smooth 60fps simulation
- **Browser**: Works on desktop, tablet, and mobile

## License

[Your License Here — e.g., MIT, GPL, etc.]

## Contact

Questions? Email: contact@mechsim.app
