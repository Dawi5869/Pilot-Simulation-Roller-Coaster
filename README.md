# 🎢 Pilot Simulation Roller Coaster – G-Force Modeling & Simulation

## ✨ Overview
This project was completed for our ASEN 2803 Dynamics & Controls course. Our goal was to model a **pilot training simulator** based on a roller coaster that reproduces realistic G-forces. The track includes four major components: a **loop**, **banked turn**, **zero-G parabola**, and **braking section**, all designed to simulate the types of forces experienced during flight maneuvers.

The coaster begins at an elevation of 125 meters and uses only gravitational potential energy—no motors or propulsion systems—making it a safe and cost-effective alternative for training. We simulated rider G-forces in all directions and verified that most sections stayed within realistic thresholds for pilot safety and effectiveness.

---

## 👨‍💻 Personal Contributions

- **📐 Loop Modeling**
  - Developed the code and derivations for the loop portion of the coaster using polar coordinate dynamics.
  - Derived and implemented formulas for **forward/backward** and **vertical G-forces**:
    - \( G_y = \frac{v^2}{gR(\theta)} + \cos(\theta) \)
    - \( G_x = \sin(\theta) \)
  - Accounted for centripetal and tangential components in the acceleration profile of the loop.
  - Visualized loop forces using MATLAB and confirmed that the vertical and lateral G-loads stayed within pilot tolerances.

- **🧠 Final Integration & Conclusions**
  - Wrote the **conclusion** section of the final report.
  - Evaluated the effectiveness of each track section and discussed the physical feasibility of using this simulator for training.
  - Interpreted G-force plots and identified limitations due to constraints on total track length (~1250 m).

---

## 🛠 Tools & Technologies

- **MATLAB** – Used to derive, implement, and simulate G-force profiles across all coaster sections.
- **3D Modeling** – Visualized velocity, curvature, and spatial layout of the full coaster using MATLAB 3D plots.
- **Analytical Dynamics** – Applied Newton’s laws and coordinate transformations for force derivation in each coaster component.

---

## 📊 Simulation Results

- **Loop**:
  - Maximum Gs experienced at the bottom of the loop due to increased normal force.
  - Riders experienced slight negative Gs at the top, simulating inverted flight.
- **Banked Turn**:
  - Gs remained constant and within tolerance, dependent solely on the banking angle (not speed or radius).
- **Zero-G Parabola**:
  - Riders experienced near-zero Gs between 550–750 meters of track.
- **Braking Section**:
  - Horizontal G-forces remained constant, with vertical/lateral Gs ≈ 0.

⚠️ Some sections marginally exceeded target Gs due to constraints on total track length.

---

## 🧩 Track Breakdown
| Segment         | Approx. Distance (m) | Notable Forces         |
|----------------|----------------------|-------------------------|
| Banked Turn     | 0–53                 | Lateral: 1.41 Gs        |
| Zero-G Parabola | 550–750              | All Gs ≈ 0              |
| Loop            | ~810+                | Up to ±3 Gs vertically  |
| Braking Section | Final segment        | Constant deceleration   |

---

## 📬 Contact
Reach out at dawi5869@colorado.edu
