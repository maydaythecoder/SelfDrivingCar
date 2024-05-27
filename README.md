# SelfDrivingCar


A brief description of what your project does and who it's for.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Files](#files)
- [License](#license)
- [Contributing](#contributing)

## Overview

This project is a simulation of autonomous vehicles using neural networks. The simulation includes multiple cars navigating a road, with one car acting as the "best" car based on its ability to stay on the road and avoid obstacles. The neural network is visualized, allowing users to see how the network processes information to make driving decisions.

## Setup

To set up the project, follow these steps:

1. Clone the repository to your local machine.
2. Open `Index.html` in your preferred web browser.

```bash
git clone https://github.com/maydaythecoder/SelfDrivingCar
cd selfdrivingcar
open Index.html
```

## Usage

The simulation can be interacted with through the browser. Here are the key functionalities:

- **Start/Stop Simulation**: The simulation runs automatically when the `Index.html` file is opened.
- **Save/Discard Best Car**: You can save the best-performing car's neural network to local storage and discard it if needed.
- **Adjust Number of Cars**: Modify the number of cars in the simulation by changing the value of `N` in `App.js`.

## Files

### Index.html

The main HTML file that sets up the canvas elements for 
the car and neural network visualizations.

### App.js

Handles the initialization of the road, cars, 
and neural network visualization. 
Manages the animation loop and updates the state of the simulation.

### visualizer.js

Contains the `Visualizer` class, which is responsible for drawing
the neural network on the canvas.

### car.js

Defines the `Car` class, which includes properties for position,
speed, and neural network. Handles car movement, 
collision detection, and drawing the car on the canvas.

### road.js

Defines the `Road` class, which sets up the lanes and 
road borders for the simulation.

### sensor.js

Defines the `Sensor` class, which equips the cars with sensors
to detect the environment around them.

### controls.js

Defines the `Controls` class, which manages user inputs and
AI control for the cars.

### utils.js

Contains utility functions used throughout the project,
such as linear interpolation (`lerp`).

### network.js

Defines the neural network structure and the mutation function
for evolving the neural networks.

## Contributing

Contributions are welcome!

---

This README provides an overview and essential details to 
get started with the autonomous vehicle simulation project.
For any additional questions or issues,
feel free to open an issue in the repository.