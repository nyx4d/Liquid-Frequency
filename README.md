Liquid-Frequency

This project is a real-time audio visualizer built with Three.js. It utilizes Web Audio API to analyze audio frequencies and update the motion of particles, inspired by fluid dynamics. The particles' velocities are influenced by the music, creating dynamic and visually appealing interactions based on the sound.
Features

    Audio Visualizer: Particles move and react to the audio frequency data in real time.
    Fluid Dynamics Simulation: Particle velocities are influenced by both audio frequency and fluid-like motion, with drag applied for smooth, realistic movement.
    Interactive 3D Environment: Users can interact with the 3D scene using mouse controls to orbit around the particles.
    Audio Integration: Supports audio file input via an <audio> element with controls.
    Responsive Design: The scene automatically adjusts to the browser window size.

Demo

YouTube - https://youtu.be/PH0qV2yLlW0

Insert a link to your demo here if you're hosting one (e.g., GitHub Pages).
Getting Started
Prerequisites

    A modern browser with WebGL support.
    A basic understanding of HTML, JavaScript, and Three.js.
    You can replace the provided audio file (audio/loFi.mp3) with any .mp3 file by changing the src attribute in the <audio> tag in the HTML file.

Installation

    Clone the repository:

    bash

git clone https://github.com/nyx4d/Liquid-Frequency.git

Navigate to the project directory:

bash

    cd Liquid-Frequency

    Open the index.html file in your browser to run the visualizer locally.

Customizing

    Changing the Audio File:
    Replace the src of the <audio> element in the HTML file with your desired .mp3 file:

    html

<source src="audio/loFi.mp3" type="audio/mpeg">

Modifying Particle Count:
You can modify the number of particles by changing the particleCount variable in the JavaScript:

javascript

    let particleCount = 15000;  // Adjust as needed

License

This project is licensed under the MIT License. See the LICENSE file for details.
Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the issues page if you want to contribute. Email - nyx4d@proton.me
