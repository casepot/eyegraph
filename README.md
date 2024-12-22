# Eye-Tracking Knowledge Graph

An interactive knowledge graph visualization that reveals progressively deeper information based on gaze duration using WebGazer.js for eye tracking and D3.js for visualization.

## Features

- Eye tracking-based interaction using webcam
- Progressive content revelation:
  - Initial view shows basic labels
  - After 2 seconds reveals summary
  - After 5 seconds shows full detail
- Interactive graph visualization with D3.js
- Proper calibration system with 4-point calibration
- Mouse hover fallback for testing
- Smooth transitions and visual feedback
- Responsive text wrapping and formatting

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/eye-tracking-graph.git
cd eye-tracking-graph
```

2. Start a local server (e.g., using Python):
```bash
python3 -m http.server 8000
```

3. Open http://localhost:8000 in your browser

## Usage

1. Allow webcam access when prompted
2. Click the "Start Calibration" button in the top-left
3. Look at each red calibration dot and press spacebar (4 points total)
4. After calibration, look at nodes to reveal their content:
   - Initial look shows label
   - After 2 seconds shows summary
   - After 5 seconds shows full detail

A red dot shows your current gaze position. Mouse hover functionality is available as a fallback for testing.

## Dependencies

- [WebGazer.js](https://webgazer.cs.brown.edu/) - Eye tracking
- [D3.js](https://d3js.org/) - Graph visualization

## Browser Requirements

- Modern browser with webcam support
- Secure context (HTTPS or localhost)
- Good lighting conditions for optimal eye tracking

## License

MIT License
