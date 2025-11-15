# Topology-optimization-of-an-electric-vehicle-hub-carrier

# Topology Optimization of an Ultra-efficient Vehicle Hub Carrier

This project, conducted as part of the Topology Optimization course at Politecnico di Milano, focused on the hub carrier of "Asteria," an ultra-efficient battery electric vehicle developed for the Shell Eco-marathon. The primary objective was to minimize the component's mass and maximize its structural stiffness.

---

## Optimization Problem and Analysis

The hub carrier's optimization was crucial, as mass was identified as the most influential parameter on the vehicle's energy consumption.

* **Objective:** Minimize the weighted compliance of the structure across all loading cases.
* **Constraints:** The optimization was subject to critical constraints on mass fraction (ranging between 0.2 and 0.4), toe stiffness (84,000 Nm/rad), camber stiffness (160,000 Nm/rad), and a forging constraint along the Y-direction to ensure manufacturability.
* **Material and Loads:** The component was analyzed using **Aluminium 6061 T6**. Six realistic loading conditions were considered, including pure rolling, braking, cornering (internal/external turn), and obstacle impacts.
* **FEA Validation:** Finite Element Analysis (FEA) confirmed that the maximum Von Mises stresses were well below the material's proof strength ($270~MPa$) in all simulated scenarios, ensuring the structural integrity of the optimized design.

---

## Final Results

Two design scenarios were studied: Case 1 (0.4 mass fraction) and Case 2 (0.2 mass fraction).

The final design choice was **Case 2 (0.2 mass fraction)**, which was the lighter option and still respected all stiffness and stress requirements.

* **Mass Reduction:** Achieved a **70% mass reduction** from the original design ($2.089~kg$ down to $0.589~kg$).
* **Stability:** The design maintained excellent structural stability, proving that significant weight reduction is possible through targeted structural optimization.

---

## Tools Employed

* **Altair Hyperworks:** Used for pre-processing, defining the design domain and boundary conditions, performing the core topology optimization, and conducting the Finite Element Analyses (FEAs).
* **Altair Inspire:** Employed during post-processing for refining the optimized geometry through surface wrapping and smoothing, resulting in the final, manufacturable design.

---

## Intended Audience

This repository is a practical resource for **Mechanical and Automotive Engineers**, **Topology Optimization Practitioners**, and **Students** interested in:

* Applying structural optimization principles to real-world automotive components.
* Using specialized commercial software (Altair Hyperworks) for lightweight design.
* Understanding the practical implications of design constraints (e.g., forging) in FEA.
