# ✈️ Paper Airfoil Aerodynamics & Flight Stability Workbench

An interactive Python/Flask workbench running in Google Colab to simulate and analyze paper airfoil aerodynamics, time-dependent pitch stability, and flight trajectories.

---

## 🚀 Features
* **MATLAB-Style Numerical Inputs:** Configure fan airflow speed, attack angle, paper mass, chord length, and simulation time with exact units.
* **Airfoil Database:** Select from 6 distinct aerodynamic profiles (NACA 2412, NACA 0012, Flat Paper Plate, Clark-Y 1922, Wright 1908, Gottingen 386).
* **Time-Dependent Flight Dynamics:** Visualizes pitch oscillation damping, wind settling behavior, and horizontal distance trajectories using Chart.js.
* **Comparative Summary Table:** Instantly compares lift force, air drag resistance, and stability deviations across selected airfoil designs.

---

## 🛠️ Technology Stack
* **Backend:** Python, Flask, NumPy
* **Frontend:** HTML5, CSS3 (Inter Font, Dark Theme), Chart.js
* **Environment:** Google Colab (Embedded Iframe Execution)

---

## 📊 How to Run in Google Colab
1. Open the project notebook in Google Colab.
2. Run the code cell containing the Flask server and physics engine.
3. The interactive web workbench will automatically launch directly inside your Colab output window via an iframe.
