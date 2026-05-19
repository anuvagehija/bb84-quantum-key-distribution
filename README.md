# bb84-quantum-key-distribution
Implementation and analysis of the BB84 Quantum Key Distribution (QKD) protocol using Python.

This project investigates how the BB84 protocol behaves under different eavesdropping conditions by analyzing Quantum Bit Error Rate (QBER), secure key generation, error correction, and privacy amplification.


## Overview

BB84 is a quantum cryptography protocol used for secure communication through quantum key distribution. The protocol allows two parties to generate a shared secret key while detecting the presence of an eavesdropper using principles of quantum mechanics.

This project simulates three communication scenarios:

1. No eavesdropping
2. Full intercept-resend attack
3. Partial interception attack

The simulation evaluates:
- Quantum Bit Error Rate (QBER)
- Secure key generation
- Error correction using Hamming codes
- Privacy amplification


## Features

- BB84 protocol simulation
- QBER calculation and analysis
- Full intercept-resend attack simulation
- Partial eavesdropping attack simulation
- Privacy amplification implementation
- Error correction concepts
- Data visualization using Matplotlib

---

## Technologies Used

- Python
- NumPy
- Matplotlib


## Results

### Lab 1 — Without Interference

The simulation produced a QBER of approximately 4%, indicating secure communication with minimal disturbance.

### Lab 2 — Full Intercept Attack

A full intercept-resend attack increased the QBER to approximately 25%, demonstrating how eavesdropping introduces detectable disturbances into the communication channel.

### Lab 3 — Partial Attack

Partial interception introduced moderate disturbances while attempting to reduce suspicion from communicating parties.

### Privacy Amplification

Privacy amplification reduced information leakage and improved the security of the final generated key.

## Error Correction

The project also demonstrates basic error correction concepts using Hamming codes to identify and correct transmission errors.


## Report

The complete report includes:
- BB84 protocol theory
- QBER analysis
- Attack simulations
- Error correction
- Privacy amplification
- Experimental discussion and conclusions


## Author

Anuva Gehija  
UNSW Quantum Engineering
