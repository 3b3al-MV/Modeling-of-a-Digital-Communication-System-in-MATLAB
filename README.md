# Modulation Techniques Simulation

This repository contains MATLAB code for simulating various digital modulation techniques, including Binary Phase Shift Keying (BPSK), Quadrature Phase Shift Keying (QPSK), 8-ary Phase Shift Keying (8PSK), and 16-ary Quadrature Amplitude Modulation (16-QAM).

## Overview

The MATLAB scripts provided in this repository simulate the performance of different modulation techniques in a noisy communication channel. The simulations calculate the Bit Error Rate (BER) for each modulation scheme under varying signal-to-noise ratios (Eb/No) and compare the results with theoretical predictions.

## Modulation Techniques

- **BPSK (Binary Phase Shift Keying):** A simple modulation scheme where the phase of the carrier signal is shifted to represent binary symbols.
  
- **QPSK (Quadrature Phase Shift Keying):** Modulates two independent carrier waves, each shifted in phase by 90 degrees, to transmit two bits per symbol.
  
- **8PSK (8-ary Phase Shift Keying):** Extends QPSK to eight different phase shifts, allowing three bits to be transmitted per symbol.
  
- **16-QAM (16-ary Quadrature Amplitude Modulation):** Combines amplitude and phase modulation to transmit four bits per symbol using a constellation of 16 points.

## Results

The simulation results are plotted to compare the simulated BER with theoretical BER curves for each modulation scheme. Separate plots are provided for each modulation technique, as well as a combined plot for comparison.

|         *1-BPSK Simulated vs Theoretical*         |         *2-QPSK Simulated vs Theoretical*         |       *3-8PSK Simulated vs Theoretical*           |
|--------------------------------------------------|--------------------------------------------------|--------------------------------------------------|
| ![](Screenshots/1-BPSK_%20Simulated%20vs%20Theoretical.png) | ![](Screenshots/2-QPSK_%20Simulated%20vs%20Theoretical.png) | ![](Screenshots/3-8PSK_%20Simulated%20vs%20Theoretical.png) |
 *1-BPSK Simulated vs Theoretical*         |         *2-QPSK Simulated vs Theoretical*         |       *3-8PSK Simulated vs Theoretical*           

