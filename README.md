# Interactive 3D Neural Network Visualization

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A visually stunning, interactive 3D neural network visualization built with `three.js`. Explore multiple procedurally generated network formations, customize visual themes, and trigger vibrant energy pulses that propagate through the connections in real-time.

---

### [✨ View Live Demo ✨](https://your-username.github.io/your-repo-name/)

https://codepen.io/lost-spirit-the-animator/pen/zxrYLay

## 🚀 Key Features

* **Real-time 3D Rendering:** Built with `three.js` for high-performance WebGL rendering.
* **Procedural Formations:** Switch between four unique, algorithmically generated network structures:
    * **Quantum Cortex:** A structured, layered sphere with primary axes.
    * **Hyperdimensional Mesh:** A complex structure representing intersecting dimensions.
    * **Neural Vortex:** A swirling, dual-helix formation.
    * **Synaptic Cloud:** A clustered, organic-looking network of nodes.
* **Advanced Pulse Controls:** Trigger energy pulses in three different modes:
    * **Click:** Pulses originate from your cursor's position.
    * **Center:** Pulses originate from the central root node.
    * **Random:** Pulses start from a randomly selected node.
* **Thematic Palettes:** Choose from four distinct blue-centric color palettes to customize the visual mood.
* **Dynamic Density:** Adjust the network's density in real-time with a slider to see more or fewer nodes and connections.
* **Post-Processing Effects:** Includes bloom and film grain effects for a polished, cinematic look.
* **Fully Responsive UI:** The control panels are designed to work smoothly on both desktop and mobile devices.

## 🛠️ Tech Stack

* **Core Library:** [three.js](https://threejs.org/)
* **Languages:** HTML5, CSS3, JavaScript (ES Modules)
* **Fonts:** [Google Fonts](https://fonts.google.com/) (Inter)
* **Styling:** Modern CSS with variables for easy theming.

## ⚙️ Getting Started

Because this project uses JavaScript Modules (`import`), it must be run from a local web server to work correctly due to browser security policies (CORS). Opening the `index.html` file directly will not work.

The easiest way to run this locally is with the **Live Server** extension in VS Code.

### Prerequisites

* A modern web browser (Chrome, Firefox, Edge).
* [Visual Studio Code](https://code.visualstudio.com/) (or any code editor with a local server solution).

### Installation & Running

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/my-username/my-repo-name.git](https://github.com/my-username/my-repo-name.git)
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd my-repo-name
    ```

3.  **Run with Live Server in VS Code:**
    * Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension from the VS Code Marketplace.
    * Right-click the `index.html` file in the VS Code Explorer.
    * Select **"Open with Live Server"**.

Your browser will automatically open with the visualization running.

## 🎮 How to Use

* **Rotate View:** Click and drag with your mouse.
* **Zoom:** Use the scroll wheel on your mouse.
* **Trigger Pulse:** Click anywhere on the canvas (if in "Click" mode).
* **Change Formation:** Click the `Formation` button.
* **Change Pulse Mode:** Click the `Mode` button to cycle through Click, Center, and Random.
* **Pause/Play:** Toggle the animation and auto-rotation.
* **Reset Camera:** Return the camera to its default position.
* **Adjust Visuals:** Use the theme buttons and density slider in the top-right panel.

## 🎨 Customization

It's easy to customize the look and feel:

* **Colors:** The UI colors can be changed by editing the CSS variables at the top of the `<style>` tag in `index.html`.
* **Themes:** The four theme palettes are defined in the `colorPalettes` array in the JavaScript section. You can change these `THREE.Color` values to create your own themes.

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more information.
