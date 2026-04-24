🔥 ThermoMaster: Interactive Thermodynamics & CPU Cooling Guide

ThermoMaster is an interactive, single-page educational web application designed to help users understand the fundamental Laws of Thermodynamics. It bridges the gap between theoretical physics and real-world application by featuring a live, interactive CPU thermal cooling simulation.

✨ Features

The 4 Laws of Thermodynamics: Clear, concise explanations of the Zeroth, First, Second, and Third laws.

Custom SVG Visualizations: Intuitive, built-in vector graphics to help visualize abstract concepts like thermal equilibrium and entropy.

Real-world Case Study: A practical guide on how thermodynamics applies to computer hardware, specifically CPU cooling and the role of thermal paste.

Interactive Thermal Simulation: A live JavaScript-powered simulation where users can:

Toggle CPU power and watch heat generation in real-time.

Apply or remove thermal paste to see the dramatic effects on heat dissipation.

Observe thermal throttling when heat is trapped by air gaps (isolators).

Responsive Design: Fully responsive layout built with Tailwind CSS, ensuring a great learning experience on desktops, tablets, and mobile devices.

🛠️ Tech Stack

This project is built using purely client-side technologies, making it incredibly lightweight and easy to deploy.

HTML5: Semantic structure and custom inline SVG graphics.

Tailwind CSS: (via CDN) For rapid, modern, and responsive UI styling.

Vanilla JavaScript: Powers the interactive thermal simulation, DOM manipulation, and smooth scrolling.

Lucide Icons: (via unpkg CDN) For crisp, scalable iconography.

🚀 Getting Started

Since this is a static single-page application, no build tools or server setups are required.

Prerequisites

A modern web browser (Chrome, Firefox, Safari, Edge, etc.)

Installation & Execution

Clone this repository:

git clone [https://github.com/yourusername/thermomaster.git](https://github.com/yourusername/thermomaster.git)


Navigate to the project directory:

cd thermomaster


Simply double-click the thermodynamics_guide.html file to open it in your default web browser, or serve it using a simple local server if you prefer:

# If you have Python installed:
python -m http.server 8000


🎮 How to Use the Simulation

Scroll down to the "Interactive Thermal Simulation" section.

Click "Turn ON CPU" to start generating heat. Watch the temperature rise.

Notice how quickly the CPU overheats (reaches > 90°C) without thermal paste, triggering a thermal throttling warning.

Click "Apply Thermal Paste" to bridge the air gap. Observe how the heat is now efficiently transferred to the heatsink, bringing the CPU temperature down to a stable level.

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

Fork the project.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📝 License

This project is open-source and available under the MIT License.

Created with ❤️ for physics and hardware enthusiasts.
