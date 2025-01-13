# Modeling-Tumor-Angiogenesis-with-Neural-Networks-and-Differential-Equations

Objective:  To model angiogenesis—a key process in tumor growth—using nonlinear systems of ordinary differential equations (ODEs). The project explored traditional numerical methods and Physics-Informed Neural Networks (PINNs) to compare their efficiency and accuracy in simulating this critical biological phenomenon.

## Key Achievements:
	•	Numerical Methods: Implemented Euler and Runge-Kutta 4 (RK4) in Python, ensuring precise numerical stability for tumor and vascular growth simulation.
	•	PINNs: Developed and trained a Physics-Informed Neural Network, integrating the biological ODE system into the loss function to predict dynamics realistically.
	•	Comparison of Approaches:
	•	RK4 & Euler: High stability but less capacity for capturing complex biological nuances.
	•	PINNs: More realistic biological behavior, including saturation dynamics, but with lower numerical stability.
	•	Metrics Analyzed: Growth rates, inflection points, and stability parameters to evaluate method performance.
 
Impact: This work highlights the promise of PINNs in biomedical applications, offering insights into the trade-offs between numerical stability and biological realism. These findings contribute to advancements in computational oncology, potentially aiding in the optimization of cancer treatments.
