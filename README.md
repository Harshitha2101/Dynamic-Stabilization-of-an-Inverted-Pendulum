# Dynamic-Stabilization-of-an-Inverted-Pendulum
Demonstrating the balancing of an **inverted pendulum on a moving cart** using MATLAB Simulink, Simscape, and Control System Toolbox.


## Objective

To model, simulate, and stabilize an inverted pendulum using a **PID feedback controller** that regulates the cart’s motion and maintains the pendulum in the upright position.

---

## Method

* **Simscape Multibody** — Models the cart–pendulum dynamics
* **Simulink** — Implements closed-loop PID control
* **Control System Toolbox** — Tunes controller parameters
* Tested under **impulse** and **random disturbances**

---

## 🧮 Results

* **Without Control:** Pendulum falls due to instability
* **With PID Control:** System achieves stable upright balance and resists disturbances

---

## 🧰 Tools Used

* MATLAB R2023b
* Simulink
* Simscape Multibody
* Control System Toolbox

---

## 👩‍🔬 Contributors

**Lab Group E (Wednesday)**

* Darius Johanan
* Dharmansh Vyas
* Dhruv Agarwal
* **Gandhe Harshitha**

## 🏁 Run Instructions

1. Clone the repository
2. Open MATLAB and navigate to the project folder
3. Run `inverted_pendulum.slx`
4. Observe system behavior with and without PID control

---

