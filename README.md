# 🚀 Cosmic Hand-Tracking Particle System

An interactive, real-time 3D particle simulation built using web technologies. By combining advanced spatial math with computer vision, users can manipulate a cosmic dust storm using their hands, compressing the particles into a solid planet with a Saturn-like rotating ring system.

## ✨ Features

* **Vibrant 3D Graphics:** Powered by **Three.js** with high-density glowing particle shaders.
* **AI Hand Tracking:** Uses **Google MediaPipe Hands** to analyze real-time video frames from your webcam.
* **Gestural Morphing States:** * *Fingers Open:* Particles scatter into a chaotic, drifting cosmic nebula (Deep Space Blue).
    * *Fingers Folded/Pinched:* Gravitational pull draws particles into a dense planetary core (Fiery Orange) surrounded by an orbital disk (Neon Cyan).
* **Interactive HUD:** A layered 2D tracking canvas overlays digital tracking nodes on top of your hand joints seamlessly.
* **Zero-UI Background Capture:** The webcam is actively processed in the background but hidden visually from the browser viewpoint.

## 🛠️ Tech Stack

* **HTML5** & **CSS3** (Custom UI Layering & Typography)
* **JavaScript (ES6+)**
* **Three.js** (WebGL 3D Engine)
* **MediaPipe Hands** (Machine Learning Framework)

## 🚀 Quick Start

1. **Clone or Download** this project folder to your local machine.
2. Open the directory inside **VS Code**.
3. Install the **Live Server** extension in VS Code if you haven't already.
4. Right-click on `index.html` and select **Open with Live Server**.
5. Give the browser permission to access your webcam when prompted.
6. Hold your hand up, pinch your fingers together, and watch the planet form!

## 📂 Project Structure

```text
├── index.html        # Main template, Three.js engine & MediaPipe logic
├── style.css         # UI layering, text glow effects & hidden camera canvas
└── README.md         # Project documentation
