##  CS_PHY_Sem6 — Computational Physics Codes (BSMS Semester 6)

This repository contains a collection of **Python scripts** developed and used during my **6th semester at IISER Kolkata** for solving various **computational physics problems**. Each module demonstrates fundamental numerical techniques essential for modeling, simulation, and data analysis in physics.

---

### 1. Root Finding Algorithms
- **Bisection Method**
- **Newton-Raphson Method** (Tangent Method)
- **Secant Method**

---

### 2. Numerical Differentiation & Integration
- **Differentiation**:
  - Forward Difference
  - Backward Difference
  - Central Difference
  - Five-point Approximation  
- **Curve Fitting**:
  - Linear Least Squares Method
- **Integration**:
  - Trapezoidal Rule
  - Simpson’s 1/3 Rule
  - Simpson’s 3/8 Rule
  - Bode’s Rule

---

### 3. Solving Ordinary Differential Equations (ODEs)
Numerical solvers for initial value problems (IVPs):
- **Euler Method**
- **Midpoint Method**
- **Runge-Kutta 4th Order (RK4)**
- **Verlet Methods**:
  - Standard Verlet
  - Velocity Verlet
  - Leapfrog Integration

---

### 4. Boundary Value Problems (BVPs)
Techniques to solve second-order differential equations with boundary conditions:
- **Shooting Method** – implemented in `solution01`
- **Crank–Nicolson Method with Thomas Algorithm** – implemented in `solution02`

---

### 5. Time-Dependent Schrödinger Equation (TDSE)
Numerical approach for solving the 1D TDSE using:
- **Strang Splitting Approximation** + **Fast Fourier Transform (FFT) & Inverse FFT**

---

### 6. Random Number Simulations
Exploratory simulations using pseudo-randomness:
- **1D Random Walk**
- **Buffon’s Needle Problem**
- more...

---

### 7. Monte Carlo Techniques
Sampling-based numerical integration and probabilistic modeling:
- **Monte Carlo Integration**
- **Importance Sampling**
- **Metropolis Algorithm**

---

### Notes
- `adaptive_time_stepping` is **not yet implemented**, but the **problem and reference material** are included for future completion.
