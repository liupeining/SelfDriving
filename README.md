# SelfDriving Simulation
Welcome to the SelfDriving simulation project! This repository contains a JavaScript-based simulation for self-driving car behavior. Dive into the world of autonomous vehicles and neural networks as you explore the code that drives these cars on a virtual road.
<p align="center">
  <img src="https://github.com/liupeining/SelfDriving/assets/56020224/a74c173e-16fc-415d-b0b5-02709ab22ad2" alt="SelfDriving Simulation Image">
</p>

## Project Structure

The project consists of several key components that work together to simulate a self-driving car environment:

- `car.js`: Defines the `Car` class, which includes properties such as speed, acceleration, and controls, as well as methods for updating the car's state and drawing it on the canvas.
- `controls.js`: Implements the `Controls` class to manage the car's movements based on user input or AI decisions.
- `main.js`: The entry point of the simulation, setting up the canvas, creating cars, and starting the animation loop.
- `network.js`: Contains the `NeuralNetwork` and `Level` classes, which are used to create and manage the AI brain of the cars.
- `road.js`: Describes the `Road` class, representing the road on which the cars drive, including its lanes and borders.
- `sensor.js`: Defines the `Sensor` class, which is responsible for detecting the surroundings of the car and providing input to the neural network.
- `utils.js`: A utility script that provides essential mathematical functions for the simulation, such as `lerp` for linear interpolation, `getIntersection` for detecting line intersections, `polysIntersect` for checking polygon intersections, and color utility functions like `getRGBA` and `getRandomColor` for visual feedback.
- `visualizer.js`: Contains the `Visualizer` class responsible for rendering the neural network's architecture and activity. It visualizes the network layers, neurons, connections, and activation levels, providing insight into the decision-making process of the AI.

Each car in the simulation is equipped with sensors that feed data into a neural network, which then decides the car's movements. The cars can be controlled either by the AI or by the user's keyboard inputs.

<p align="center">
  <img src="https://github.com/liupeining/SelfDriving/assets/56020224/c7ff3dc6-ac8d-4511-8eae-97e5913449db" alt="SelfDriving Simulation Image">
</p>




## Features

- Simulation of autonomous car behavior using a simple neural network.
- Interactive controls allowing users to take over the car's driving.
- Visualization of the neural network's decision-making process.

## Getting Started

To get started with the SelfDriving simulation:

1. Clone the repository to your local machine.
2. Open `index.html` in your web browser to run the simulation.
3. Observe the AI-driven cars or use the arrow keys to control a car manually.

## Acknowledgments

Special thanks to [FreeCodeCamp.org](https://www.freecodecamp.org/) for providing the educational content that greatly assisted in the development of this project. Their comprehensive teaching materials are an invaluable resource for learning and understanding the principles behind self-driving car simulations.
