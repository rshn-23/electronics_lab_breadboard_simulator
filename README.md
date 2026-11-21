# Electronics Lab Breadboard Simulator

An interactive, browser-based solderless breadboard and benchtop electronics laboratory simulator built for undergraduate electronics practical preparation.

## Live Demo
Access the simulator directly in your browser via GitHub Pages:  
👉 **[Launch Electronics Lab Breadboard Simulator](https://rshn-23.github.io/electronics_lab_breadboard_simulator/)**

## Key Features
- **High-Precision Solderless Breadboard:** 30-column terminal strips (`A–E`, `F–J`) and continuous power rails (`+` / `−`) with real-time internal strip continuity highlighting on hover.
- **Interactive Component & Instrument Workbench:**
  - **Components:** 1N4001 P-N Junction Diode, 5.6V Zener Diode (`1Z5.6`), Carbon Film Resistors (560Ω, 1kΩ, 10kΩ, 100kΩ + custom values), BC107 BJT, BFW10 JFET, and Light Dependent Resistor (LDR) with movable lamp distance control (5–100 cm).
  - **Bench Equipment:** 0–100V Regulated Power Supply, Digital Voltmeters, Digital Ammeters, Decade Resistance Box, 1 kHz Function Generator, 6V-0-6V Center-Tapped Transformer, and Dual-Channel Cathode Ray Oscilloscope (CRO).
- **8 Guided Laboratory Experiments + Custom Sandbox:**
  1. V-I Characteristics of P-N Junction Diode (Forward & Reverse Bias)
  2. V-I Characteristics of Zener Diode
  3. Zener Diode as a Voltage Regulator (Line & Load Regulation)
  4. Half-Wave & Full-Wave Center-Tapped Rectifiers
  5. Positive & Negative Biased Diode Clippers
  6. Common Emitter BJT (`BC107`) Input & Output Characteristics
  7. JFET (`BFW10`) Drain & Transfer Characteristics
  8. LDR Resistance vs. Lamp Distance Characteristics
- **Topological Netlist Verifier & Physics Engine:** Union-Find electrical net analyzer that verifies student breadboard wiring regardless of column placement, paired with a Newton-Raphson Shockley diode solver, live V-I curve plotter, Auto-Sweep generator, and dual-channel CRO waveform renderer.

## Controls & Shortcuts
- **Click any hole / instrument terminal:** Connect Bezier jumper wires (choose wire color in the left drawer; right-click any wire to delete).
- **Drag component:** Move across breadboard holes; double-click or press **`R`** to rotate 90°.
- **`Delete` / `Backspace`:** Remove selected component, wire, or instrument.

## Tech Stack
- **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript (ES6+), SVG & HTML5 Canvas

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
