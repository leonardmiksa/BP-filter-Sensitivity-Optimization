# Sensitivity Optimization of a 4th-Order Chebyshev Bandpass Filter in CBQ Structure

This project focuses on analyzing and minimizing the sensitivity of a fourth-order Chebyshev bandpass filter implemented in a *Cascade of Biquadratic (CBQ)* structure.  
This work is also my Master's thesis.

The goal is to reduce the impact of real-world component tolerances (resistor and capacitor variations) on the filter's key performance metrics, such as center frequency, quality factor (Q), and gain.

Key features:
- Analog filter design for a central frequency of 4 kHz
- Analytical derivation of sensitivity functions with respect to passive components
- MATLAB simulations of:
  - Frequency response
  - Sensitivity analysis
  - Sensitivity optimization
- Modified filter design using optimized values for resistors and capacitors
- Comparison of sensitivity between optimized and non-optimized CBQ implementations (cascade structure, CBQ structure, and optimized CBQ structure)
- Validation of all filter designs in LT Spice, including Monte Carlo analysis
- Testing the final filtar design frequency response on a laboratory breadboard (although sensitivity couldn't be measured in lab)

Tools used:
- MATLAB (symbolic math toolbox and standard simulation)
- LT Spice
- Electronic components and breadboard
- Oscilloscope

> 📎 Full project report (in Croatian) is available in the provided PDF file.


Author:
Leonard Mikša
MSc Electrical Engineering student  
📧 [leonardmiksa@gmail.com](mailto:leonardmiksa@gmail.com)

> *This repository is currently under active development as part of my Master's thesis project.*
