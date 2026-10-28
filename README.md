# Pro Dynamics Lab ⚙️

An interactive, browser-based 3D simulation and analytical solver for **Spring-Mass-Damper** systems. Designed for students, educators, and engineers studying *Dynamics of Machinery* and *Mechanical Vibrations*.

Developed by **Shekh Ayan R.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)

## ✨ Features

Pro Dynamics Lab is divided into two powerful modules:

### 1. Interactive 3D Simulator
* **Real-time 3D Rig:** A fully modeled test rig rendered with `Three.js`, featuring dynamic spring compression/extension and an oil dashpot.
* **Oscilloscope Graphing:** A live-plotting graph that tracks displacement over time ($x$ vs $t$), overlaying the theoretical decay envelope for underdamped systems.
* **Live Variable Control:** Instantly adjust Mass ($m$), Spring Stiffness ($k$), Damping Ratio ($\zeta$), and Initial Displacement ($x_0$) using intuitive sliders.
* **Automatic Regime Classification:** Instantly calculates and classifies the system as *Undamped, Underdamped, Critically Damped,* or *Overdamped*.
* **Deep-Dive Modals:** "Zoom" buttons allow you to expand the 3D rig or the mathematical graph into a full-screen view for detailed analysis.

### 2. Universal Solver (Analytical Tools)
* **Physical Properties Analysis (Forward):** Enter known $m$, $k$, and $c$ to calculate Natural Frequency ($\omega_n$), Critical Damping ($c_c$), Damping Ratio ($\zeta$), Damped Frequency ($\omega_d$), and Logarithmic Decrement ($\delta$).
* **Experimental Data Solver (Inverse):** Uses logarithmic decrement mathematics. Input the start/end peaks from a real-world test over $n$ cycles to reverse-engineer the system's hidden stiffness ($k$) and damping ($c$).
* **Design Targeting:** Input a target natural frequency ($f_n$) in Hz to calculate the exact required mass or spring stiffness needed to achieve it.

