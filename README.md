# PB3D: Project Beyond 3-Dimensional 🌌

![PB3D Gif](https://github.com/SlizR/PB3D/blob/main/Assets/photo.gif)

---

  <p align="center">
  <img src="https://img.shields.io/badge/Created by-Sliz®-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Apache License 2.0-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Project%20Beyond%20-3 Dimensional-purple?style=for-the-badge" />
</p>
  
---

PB3D (Project B-Dimensional) is a minimalistic and interactive web project built using **Three.js** to demonstrate and explore 3D geometry and the 4D hypercube (Tesseract) in real time.

Users can switch between various standard 3D shapes (Cube, Sphere, Tetrahedron) and observe the Tesseract's 4D rotation via a 3D projection.

---

## ✨ Key Features

* **Multi-Dimensionality:** Easily switch between standard 3D primitives and an interactive 4D projection (Tesseract).
* **Interactive Controls:** Use **OrbitControls** to manually rotate and zoom the scene with your mouse.
* **Animation Control:** Toggle **Auto-Rotation** on/off using of dedicated slider.
* **Lightweight:** The project uses a minimal set of external libraries (only Three.js and its OrbitControls module).

---

## 🌌 Open Source Code

* The **open source code** is provided in a file [**here**](OSC.txt), and **you can copy** it **without the footer** and **author's badge**, **but with one author's comment**.

---

## 🛠️ Technology Stack

* **HTML5**
* **CSS3** (for basic styling and the interactive control menu)
* **JavaScript (ES6+)**
* **Three.js (r128)** — The core library for WebGL 3D graphics.
* **OrbitControls.js** — For camera interaction.

---

## 🚀 Setup and Launch

The PB3D project is simple to set up. Since it primarily uses local files (HTML, CSS, JS) and public CDN links for Three.js, you can run it directly in your browser.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SlizR/PB3D.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd PB3D
    ```
3.  **Open the file:** Simply open the `index.html` file in any modern web browser (e.g., Chrome, Firefox) **OR** Visit the **test** [**website**](https://slizr.github.io/PB3D/) to see the work

> **Note:** If you encounter issues (like cross-origin security errors on certain browsers), you may need to run a simple local web server (e.g., using VS Code Live Server or `python3 -m http.server`).

---

## 💡 How to Use

The main control panel is located in the bottom-left corner of the screen:

1.  **Select a Shape:** Use the buttons to switch the rendered object:
    * **◼︎ Cube** (4-point figure)
    * **⏺︎ Ball** (Sphere)
    * **▲ Triangle** (Tetrahedron)
    * **♾︎ Hypercube (4D)** (Tesseract)
    * **✹ Stress Test** (2 million objects)
2.  **Rotation Control:**
    * **Auto-Rotation:** Toggle switch to enable or disable automatic rotation around the X and Y axes.
    * **FPS display:** You can turn the FPS display on or off; it's off by default. When you enter a stress test, it automatically turns on, but when you exit, it returns the value before entering.
3.  **Camera Control (OrbitControls):**
    * **Rotate View:** Click and drag the left mouse button.
    * **Zoom/Pinch:** Use the mouse scroll wheel.
    * **Pan:** Click and drag the right mouse button.

---

## 📄 License

This project is licensed under the **Apache License 2.0**. See the [`LICENSE`](LICENSE) file for more details.
-
**All rights reserved** by the **registered** company **SLIZ®**. In case of violation of the license rights: [**Apache License 2.0**](LICENSE) You will be responsible for your own actions. If you copy and distribute without the original creator's mark: ```<meta name="author" content="Sliz®">``` And without the mark that you edited: ```// Edited by ...``` You will be responsible for your own actions. And before copying, please read the [`LICENSE`](LICENSE) completely. Thank you for reading the information! Copying index.html is strictly prohibited. There is an exact copy ([**Open Source Code.txt**](OSC.txt)), but without the footer, etc.

---

## 📧 Contact

**Creator:** Sliz®

* **Web-page:** [PB3D](https://slizr.github.io/PB3D/)
* **Sliz®:** [Github Page Sliz®](https://github.com/SlizR)
* **Open Source Code:** [OSC.txt](OSC.txt)
* **Email:** markd.voznyuk@gmail.com

*© 2025 Sliz®. All Rights Reserved. Version 25.0*
