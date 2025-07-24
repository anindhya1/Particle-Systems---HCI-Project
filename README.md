# Particle Systems — HCI Project

## Overview  
This project explores interactive particle systems as part of a Human–Computer Interaction (HCI) study. It demonstrates how users can engage with and manipulate simulated particle swarms in real-time, evaluating usability, responsiveness, and visual feedback dynamics.

## Features  
- **Real-Time Particle Simulation**: Simulates large swarms of particles governed by customizable rules.  
- **Interactive Controls**: Users can adjust parameters (e.g., force strength, particle count, attraction/repulsion) via an intuitive UI.  
- **Visual Feedback**: Smooth, responsive graphics that illustrate emergent behaviors in particle movements.  
- **Adaptable Systems**: Supports multiple behaviors—aligned motion, separation, cohesion, and field influence.

## Technology Stack  
- **Frontend / Simulation**:  
  - Implemented with **p5.js** or **Processing**, enabling high-performance, browser-based visualization.  
- **Controls & UI**:  
  - HTML/CSS/JavaScript interface for real-time parameter tweaking and mode selection.  
- **Architecture**:  
  - Modular design for behavior engines, rendering loop, and parameter input handling.

## Installation

### Prerequisites  
- Modern web browser (Chrome, Firefox, Safari)  
- Optional local web server (e.g., `http-server`, `Live Server` extension)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/anindhya1/Particle-Systems---HCI-Project.git
    cd Particle-Systems---HCI-Project
    ```

2. Launch a local server (optional but recommended for full functionality):
    ```bash
    http-server .  # or use Live Server in VSCode
    ```

3. Open `index.html` in your browser:
    - If using a server, visit `http://localhost:8080`
    - Otherwise, open the file directly

## Usage  
1. Use the panel or on-screen sliders to adjust parameters like particle count, force ranges, and mode selection.  
2. Observe how changes influence particle behavior and system responsiveness.  
3. Explore different modes (e.g., flocking, repulsion wave, field manipulation) to visualize emergent effects.

## File Structure  
```
.
├── index.html # Main viewer with simulation canvas and UI
├── sketch.js # Core particle system logic and update loop
├── styles.css # UI styling
├── data/ # Optional datasets or logs from interaction sessions
└── README.md # Project documentation
```


## Development & Research  
- **Extend Rules**: Add new forces such as noise, gravity wells, or obstacle avoidance.  
- **Data Logging**: Record participant interactions to evaluate usability and discoverability.  
- **User Testing**: Integrate forms to collect qualitative feedback for HCI studies.  
- **Performance Optimization**: Explore WebGL/WebGPU-based rendering for smoother handling of large swarms.

## Contributing  
Contributions are welcome! To participate:

1. Fork the repository  
2. Create a feature branch:
    ```bash
    git checkout -b feature-name
    ```

3. Commit improvements:
    ```bash
    git commit -m "Add feature description"
    ```

4. Push your branch:
    ```bash
    git push origin feature-name
    ```

5. Submit a Pull Request

## License  
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author  
[Anindhya Kushagra](https://github.com/anindhya1)

---

Built as part of a Human–Computer Interaction project evaluating interactive visual systems.

