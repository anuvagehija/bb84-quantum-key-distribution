# BB84 Quantum Key Distribution Analysis

Implementation and analysis of the BB84 Quantum Key Distribution (QKD) protocol using Python.

This project investigates how the BB84 protocol behaves under different eavesdropping conditions by analysing Quantum Bit Error Rate (QBER), secure key generation, error correction, and privacy amplification.

## Overview

BB84 is a quantum cryptography protocol used for secure communication through Quantum Key Distribution (QKD). The protocol enables two parties to establish a shared secret key while detecting the presence of an eavesdropper through disturbances introduced during quantum measurement.

This project analyses three communication scenarios:

1. No eavesdropping
2. Full intercept-resend attack
3. Partial interception attack

The analysis evaluates:

* Quantum Bit Error Rate (QBER)
* Secure key generation
* Error correction using Hamming codes
* Privacy amplification

## Features

* BB84 protocol analysis and simulation
* QBER calculation and analysis
* Full intercept-resend attack simulation
* Partial eavesdropping attack simulation
* Privacy amplification implementation
* Error correction concepts using Hamming codes
* Data visualisation using Matplotlib

## Technologies Used

* Python
* NumPy
* Matplotlib
* Jupyter Notebook

## Results

### Privacy Amplification and Secure Key Rate

The figure below shows the relationship between QBER and secure key generation after privacy amplification. The experimentally measured QBER remains below the BB84 security threshold, allowing secure key extraction.

<img width="690" height="390" alt="image" src="https://github.com/user-attachments/assets/743609b0-b3f2-4779-aa86-ebcc33b33cd6" />


### Lab 1 — Without Interference

The measured QBER was approximately 4%, indicating secure communication with minimal disturbance.

### Lab 2 — Full Intercept Attack

A full intercept-resend attack increased the QBER to approximately 25%, demonstrating how eavesdropping introduces detectable disturbances into the quantum channel.

### Lab 3 — Partial Attack

Partial interception introduced moderate disturbances while attempting to reduce detectability.

## Error Correction

The project demonstrates basic error correction concepts using Hamming codes to identify and correct transmission errors before privacy amplification.



## Repository Contents

* `BB84_Analysis.ipynb` — Complete analysis and visualisation notebook
* `BB84_Report.pdf` — Full technical report
* `README.md` — Project documentation




