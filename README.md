# 3D-Finite-Element-Analysis-Model
# 📐 3D Educational FEA Simulator

An interactive **3D Finite Element Analysis (FEA) visualization tool** built with JavaScript and WebGL.
This educational simulator demonstrates how **material properties affect deformation** in a simple 3D structure.

The project allows users to modify **Young’s Modulus** and **Poisson’s Ratio** and observe how a 3D cube deforms under a simulated load.

This tool is designed for **students, educators, and engineering enthusiasts** learning the basics of **solid mechanics and finite element concepts**.

---

# 🌐 Live Demo

You can run the simulator in your browser:

**Live Website:**
https://3d-finite-element-analysis-model-michael-nsengiyumva.org/

---

# 🎯 Features

* Interactive **3D visualization**
* Adjustable **material properties**
* Simulated **elastic deformation**
* Real-time geometry updates
* Smooth **WebGL rendering**
* Lightweight **single-file implementation**

---

# ⚙️ How It Works

The simulator creates a **3D mesh cube** using a geometry grid.
When the user clicks **Run Simulation**, the program:

1. Reads the material properties:

   * **Young's Modulus (E)**
   * **Poisson Ratio (ν)**

2. Calculates a simple deformation model:

   * Higher **Young's Modulus → less deformation**
   * Lower **Young's Modulus → more deformation**

3. Applies displacement to the cube's vertices.

4. Updates the geometry and recomputes vertex normals for rendering.

This is a **simplified conceptual demonstration** of how Finite Element methods deform meshes under material constraints.

---

# 🧰 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Three.js (WebGL 3D library)**

Library used:

* https://threejs.org/

---

# 📂 Project Structure

```
project-folder
│
├── index.html      # Main simulator
└── README.md       # Project documentation
```

This project intentionally uses a **single-file architecture** for simplicity and educational clarity.

---

# 📚 Educational Purpose

This project demonstrates several concepts:

* Basic **Finite Element deformation principles**
* **3D mesh manipulation**
* **Vertex displacement**
* Real-time **WebGL rendering**

While simplified, the simulator illustrates how **material stiffness influences structural deformation**.

# 👨‍💻 Author

**Michael Nsengiyumva**
**mng2650**

© 2026 Michael Nsengiyumva
All Rights Reserved
