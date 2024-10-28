# EcoSim - Ecosystem Simulation Web Application

EcoSim is a web-based ecosystem simulation where various organisms (such as rabbits, foxes, and plants) interact in a digital environment. Users can observe how natural factors like predation, reproduction, and environmental limits shape population dynamics within this ecosystem. Built with JavaScript, HTML, and CSS, EcoSim provides an engaging interface for exploring ecological principles.

## Features

- **Organism Interactions**: Allows organisms like predators and prey to interact within the ecosystem, affecting population balance.
- **Population Dynamics**: Tracks the birth, death, and survival rates of organisms based on hunting success, food availability, and land capacity.
- **Visual Interface**: Displays real-time statistics for each organism in a user-friendly HTML interface.
- **Environmental Constraints**: Incorporates land capacity limits, hunting attempts, and reproduction probabilities.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Functions Overview](#functions-overview)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AadityaKGupta/Ecosystem-Simulation.git
   ```
3. Open `index.html` in a web browser to start the simulation.

## Usage

1. Open the application in a web browser.
2. Select organisms to observe within the simulation.
3. Adjust parameters as needed and monitor the population changes.
4. Use the UI to see population data, hunting success, and other organism statistics.

## File Structure

- **index.html**: The main HTML file for the simulation interface.
- **css/**: Contains CSS styles for the application layout and design.
- **js/app.js**: The primary JavaScript file containing core simulation logic for organism interactions, hunting, reproduction, and tracking.

## Functions Overview

### Organism Class
The `Organism` class defines behaviors for different organisms in the ecosystem:
- **hunt()**: Simulates hunting behavior for carnivorous organisms.
- **reproduce()**: Calculates reproduction rates based on available resources and organism type.

### generateOrganismHTML
The `generateOrganismHTML` function dynamically creates HTML elements to display the organism's name, population count, and other properties.

### Constants
- **MAX_LAND_CAPACITY**: The maximum land capacity, restricting the number of organisms that can exist in the ecosystem.

## Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests to improve EcoSim.

## License

This project is licensed under the MIT License.
