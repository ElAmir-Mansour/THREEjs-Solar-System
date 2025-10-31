3D Solar System Simulation
This is a web-based 3D solar system simulation created with Three.js. It renders a simplified model of our solar system, complete with the sun, 8 planets, and their orbital paths. The simulation is interactive, allowing you to explore the scene with mouse controls.

Features
Sun & 8 Planets: Includes the Sun, Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, and Neptune.

Real Textures: Uses realistic 2K textures for all celestial bodies.

Elliptical Orbits: Planets travel on elliptical paths, not just perfect circles.

Planet & Sun Rotation: All planets and the sun rotate on their own axes.
<img width="1368" height="679" alt="Screenshot 2025-10-31 at 4 32 38 PM" src="https://github.com/user-attachments/assets/7a30df5a-ff54-413a-901b-1d9c9ef0e2b7" />

Bonus Features:

Earth's Moon: The Moon orbits the Earth as the Earth orbits the Sun.

Saturn's Ring: Saturn includes a textured ring system.

Starry Background: Uses a 2K Milky Way texture for a beautiful space background.

Interactive Controls: You can rotate, pan, and zoom the camera using OrbitControls.

🛠️ Technologies Used
Three.js: The core 3D graphics library for JavaScript.

HTML5 & CSS3: For the basic web page structure.

JavaScript (ES6+): For the simulation logic.

🚀 How to Run
This project is a static website and requires no server or installation.

Clone or download the repository.

Ensure all texture files are in their correct folders (/Earth, /Planets2k, /Sun-moon-stars).

Open the index.html file in any modern web browser (like Chrome, Firefox, or Edge).

Controls
Rotate: Left-click and drag.

Zoom: Scroll with the mouse wheel.

Pan: Right-click and drag.

📁 File Structure
Solar System Project/
│
├── index.html           # The main file to run the simulation
├── Readme.md            # This file
│
├── Earth/
│   ├── 2k_earth_daymap.jpg
│   ├── 2k_earth_nightmap.jpg
│   └── 2k_earth_clouds.jpg
│
├── Planets2k/
│   ├── 2k_mercury.jpg
│   ├── 2k_venus_surface.jpg
│   ├── 2k_mars.jpg
│   ├── 2k_jupiter.jpg
│   ├── 2k_saturn.jpg
│   ├── 2k_uranus.jpg
│   ├── 2k_neptune.jpg
│   └── 2k_saturn_ring_alpha.png
│
└── Sun-moon-stars/
    ├── 2k_sun.jpg
    ├── 2k_moon.jpg
    └── 2k_stars_milky_way.jpg
📜 Credits
All textures used in this project are from Solar System Scope.
