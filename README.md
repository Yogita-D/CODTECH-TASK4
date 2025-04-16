# CODTECH-TASK4
Name - Yogita Shrikant Dhonge
Company - CODETECH IT SOLUTIONS
ID - CT04WM47
Domain -VLSI
Duration -March 18th,2025 to April 18th,2025
Mentor - Vaishali

Project Overview: FIR Filter Design and Simulation

Objective:

Design, simulate, and analyze a Finite Impulse Response (FIR) Digital Filter using Verilog or MATLAB.


---

What is an FIR Filter?

A Finite Impulse Response (FIR) filter is a type of digital filter whose output is a weighted sum of a finite number of past input samples. It's widely used for signal processing because of its linear phase and stability.

General FIR filter equation: 

y[n]: output

x[n]: input

h[k]: filter coefficients

N: number of taps (filter order)



---

Deliverables:

1. Verilog Code or MATLAB Code implementing the FIR filter.


2. Simulation Results (waveforms, input/output plots).


3. Performance Analysis (filter order, delay, frequency response, etc.).




---

Implementation Steps:

Option 1: Verilog

1. Define coefficients (static or using a coefficient file).


2. Implement FIR structure (e.g., Direct Form I).


3. Testbench to simulate input signals.


4. Simulate using tools like ModelSim or Vivado.


5. Verify output using waveform analysis.



Option 2: MATLAB

1. Design filter using fir1, firpm, or designfilt.


2. Analyze response (magnitude, phase, impulse).


3. Simulate input signal and pass through filter.


4. Plot input vs output to verify performance.




---

Performance Analysis Points:

Filter order (number of taps)

Frequency response (low-pass, high-pass, etc.)

Passband/stopband behavior

Linear phase verification

Processing delay



---

Bonus: Tools You Can Use

MATLAB: fvtool, filter, freqz, fir1

Verilog Simulation: ModelSim, Vivado, Icarus Verilog
