# SolarSystemThreejs
# Orrery Web App - NASA SpaceApps Challenge 2024

![Project Preview](link-to-screenshot)  
*(Add a screenshot of your project here)*

## Project Overview

This Orrery Web App is an interactive 3D visualization tool designed to simulate the solar system, along with Near-Earth Objects (NEOs), such as asteroids, comets, and Potentially Hazardous Asteroids (PHAs). Built using Three.js and NASA’s Small Body Database, this project aims to create an immersive and educational experience for astronomy enthusiasts, students, and professionals to explore celestial objects and their orbits in real time.

### Features

- **3D Solar System Visualization**: Interactive orbits and rotations of planets, NEOs, and the Sun.
- **Near-Earth Object (NEO) Tracking**: Fetches and visualizes real-time NEO data from NASA’s API.
- **Planetary Details**: Toggleable labels and trajectory views for celestial bodies.
- **Interactive Controls**: Zoom, rotate, and navigate the solar system with intuitive controls.
- **Realistic Lighting Effects**: Simulated lighting based on the position of the Sun.
- **Customizable Speed**: Adjust the speed of planetary rotations and orbits.
- **Skybox Background**: Realistic space environment background using Three.js skybox.
- **Follow Planet Feature**: Ability to click and track planets during their revolution and rotation.
- **Asteroid Destroy Game**: A fun, integrated mini-game where users can attempt to destroy asteroids that pose a potential threat to Earth. Players can shoot asteroids as they approach, adding an engaging interactive layer to the app.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Three.js
- **NASA API**: Small Body Database, Keplerian parameters
- **3D Models**: GLTF/GLB models of planets and the Sun
- **Asteroid Destroy Game**: JavaScript, Three.js
- **Version Control**: Git, GitHub Pages for deployment

## How It Works

1. **Planetary Rendering**: The solar system is rendered in a 3D space where each planet orbits the Sun while rotating on its axis. Users can explore different perspectives using mouse controls.
   
2. **Near-Earth Object Visualization**: The NASA API fetches real-time data about NEOs (like asteroids and comets), displaying their current positions and orbits.

3. **Interactive Controls**: The app allows users to zoom in/out and rotate the solar system, as well as focus on individual planets with a click.

4. **Asteroid Destroy Game**: In the asteroid destroy mini-game, players can protect Earth by shooting down incoming asteroids. Players aim and fire using simple keyboard/mouse controls, adding an interactive layer to the app.

5. **Real-Time Data**: NEO positions are updated dynamically, allowing users to track them in near real-time as they orbit the Sun.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/samaddarsoham/NASA_3D_SolarSystem_Three.js.git
