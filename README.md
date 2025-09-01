# 🪐 N-Body Simulation (3-Body Problem) with GUI & ML Optimizer

This project is a **Python-based N-Body simulator** (starting with 3 bodies), built with **Tkinter** for GUI visualization.  
It simulates gravitational interactions between bodies and provides options to tune masses, initial velocities, and simulation speed.  

Additionally, a simple **ML/DL optimizer** is included to search for **stable configurations**, where bodies orbit each other for long durations without collapsing or flying away.

---

## 🚀 Features
- Interactive **Tkinter GUI** with clean controls.  
- Real-time simulation of **gravitational interactions**.  
- Adjustable parameters:
  - Mass of each body  
  - Initial positions & velocities  
  - Simulation speed  
- Trails showing orbital paths.  
- Option to enforce **solid borders** (bodies bounce inside the window).  
- Built-in **ML optimizer** with two modes:
  - **Longevity mode**: maximize how long the system runs without collision/escape.  
  - **Stability mode**: maximize orbital stability (bodies orbit in repeating patterns).  
- Checkpoint saving → optimizer resumes training across runs.  

---

## 🛠️ Installation
Clone or download the project:
```bash
git clone https://github.com/your-username/nbody-simulation.git
cd nbody-simulation
