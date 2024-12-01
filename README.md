#Solar System Simulation
This project is a simple animated simulation of the Solar System using HTML, CSS, and JavaScript. It displays the Sun at the center and planets revolving around it in their respective orbits. The animation also includes Earth's moon orbiting around Earth.

Features
Realistic depiction of the Solar System with the Sun and planets.
Animation of planets revolving around the Sun.
Earth's Moon orbiting around Earth as a satellite.
Scalable and responsive for various screen sizes.
Preview

Planets Included
Mercury
Venus
Earth (with Moon as a satellite)
Mars
Jupiter
Saturn
Uranus
Neptune
How to Use
Clone or download the repository.
Open the index.html file in any modern web browser.
Watch the animated solar system in action.
File Structure
bash
Copy code
Solar System Simulation/
├── index.html         # Main HTML file
├── README.md          # Readme file (this file)
└── assets/            # Folder for screenshots or related files (optional)
Technologies Used
HTML5: Structure of the project.
CSS3: Styling the Sun, planets, orbits, and moon.
JavaScript: Animation logic for the planets' and moon's revolutions.
How It Works
Each planet is assigned:
A unique color.
A size proportional to its scale in the Solar System.
A distance from the Sun (approximated for visual effect).
An orbital period, representing how fast it orbits the Sun.
JavaScript uses requestAnimationFrame for smooth animations.
Circular orbits are simulated using trigonometric functions (cos and sin).
