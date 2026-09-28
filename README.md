🌌 Planet Simulation using Python & Pygame

A simple 2D Solar System simulation built using Python and Pygame. This project demonstrates how planets move around the Sun using basic physics and Newton's Law of Universal Gravitation.

The simulation calculates the gravitational force between celestial bodies and updates their velocity and position over time to create an animated planetary orbit.

🚀 Features

- ☀️ Sun and four planets — Mercury, Venus, Earth, and Mars
- 🌍 Realistic planetary masses and distances
- 🪐 Gravitational attraction between planets
- 📐 Orbital motion based on velocity and acceleration
- 📏 Displays the distance of each planet from the Sun
- 🛤️ Shows the orbital path/trail of each planet
- ⚡ Real-time animation using Pygame

🛠️ Technologies Used

- Python
- Pygame
- Math module
- Basic concepts of Physics and Mathematics

📚 Physics Concepts Used

The simulation is based on Newton's Law of Universal Gravitation:

F = G × (m₁ × m₂) / r²

Where:

- "F" = Gravitational force
- "G" = Gravitational constant
- "m₁" = Mass of the first object
- "m₂" = Mass of the second object
- "r" = Distance between the two objects

The program then uses:

Acceleration:

"a = F / m"

Velocity:

"v = u + a × dt"

Position:

"s = s₀ + v × dt"

These calculations are repeated continuously to simulate planetary motion.

📂 Project Structure

Planet-Simulation/
│
├── planet_simulation.py
└── README.md

💻 Installation

1. Clone the repository

git clone https://github.com/akankhyasahoo/Planet-Simulation.git

2. Open the project folder

cd Planet-Simulation

3. Install Pygame

pip install pygame

4. Run the program

python planet_simulation.py

🎮 How It Works

1. The Sun and planets are created with their respective mass, position, radius, and color.
2. Each planet has an initial velocity.
3. The program calculates the gravitational force between every planet.
4. The force is converted into acceleration.
5. Velocity and position are updated for every frame.
6. The updated position is displayed on the screen.
7. The previous positions are stored to create orbital trails.

🌍 Planets Included

Planet| Approx. Distance from Sun| Initial Velocity
Mercury| 0.387 AU| 47.4 km/s
Venus| 0.723 AU| 35.02 km/s
Earth| 1 AU| 29.783 km/s
Mars| 1.524 AU| 24.077 km/s

🎯 Learning Objectives

This project was created to understand how programming, mathematics, and physics can be combined to create a simple scientific simulation.

It helped demonstrate concepts such as:

- Object-Oriented Programming in Python
- Classes and Objects
- Loops and Functions
- Real-time animation
- Newtonian gravity
- Velocity and acceleration
- Coordinate systems
- Basic numerical simulation

🔮 Future Improvements

Possible improvements include:

- Adding more planets and moons
- Adding zoom and camera controls
- Adding pause/resume functionality
- Adding planet information panels
- Improving orbital accuracy
- Adding adjustable simulation speed
- Adding a more realistic scale and visual effects

👩‍💻 Author

Akankhya Sahoo

GitHub: https://github.com/akankhyasahoo

⭐ Acknowledgement

This project is created for learning and demonstrating the application of Python programming with basic physics concepts.
