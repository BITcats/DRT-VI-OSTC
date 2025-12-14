# DRT-VI-OSTC

# A Rotation-Translation Decoupled Solution for Visual-Inertial Initialization and Online Spatial-Temporal Calibration
<p align="center">
 <img width="45%" alt="image" src="https://github.com/user-attachments/assets/5fa71a41-6d54-4ec8-816f-49b0d765fdaf" />
</p>

This repository provides the official implementation of our **rotation–translation decoupled initialization and online spatial-temporal calibration method** for **Visual–Inertial Odometry (VIO)**.

Our method enables **robust and accurate VIO initialization**, even under **pure rotational motion**, while **simultaneously estimating gyroscope bias, extrinsic rotation, and camera–IMU time offset**.

---

## 📌 Overview

Visual–Inertial Odometry (VIO) systems critically rely on a reliable initialization stage.  
However, existing initialization methods often:

- Suffer from **limited accuracy or robustness**
- Fail under **small or zero translational motion**
- Ignore **simultaneous spatial–temporal calibration**, despite its practical importance

To address these challenges, we propose a **novel rotation–translation decoupled VIO initialization framework** with integrated **online spatial-temporal calibration**.

---

## ✨ Key Contributions

<p align="center">
 <img width="95%" alt="image" src="https://github.com/user-attachments/assets/dd6c361f-5b03-46d8-a081-9c3ce5a87514" />
</p>

- **Rotation–Translation Decoupled Initialization**
  - Decouples rotation and translation estimation to improve robustness and accuracy

- **Simultaneous Spatio-Temporal Calibration**
  - Jointly estimates:
    - Gyroscope bias
    - Camera–IMU extrinsic rotation
    - Camera–IMU time offset  
  - Works even under **pure rotational motion**

- **Observability Analysis**
  - First to analyze **rotational constraint observability** in decoupling-based methods
  - Identifies **unobservable state-space directions** under three degenerate motions

- **Practical Parameter Boundary Analysis**
  - Extensive experiments reveal **practical solvable regions**
  - Significantly improves real-world applicability

- **Efficient and Robust**
  - Maintains **low computational cost**
  - Improves **convergence behavior** of downstream VIO systems

---
## 🚀 Quick Start


## 🙏 Acknowledgements


## 📜 Citation

## 📄 License



