# Three-Stage BJT Amplifier Design and Simulation Using Multisim 

## Project Overview

This project presents the design, simulation, and analysis of a high-gain multistage BJT amplifier using NI Multisim.

The amplifier consists of:

1. Differential Amplifier Input Stage
2. Common Emitter Gain Stage
3. Common Emitter Driver Stage
4. Class-AB Push-Pull Output Stage

The objective was to achieve an overall voltage gain close to 100 dB while maintaining low distortion and good signal fidelity.

---

## Project Objectives

- Design a multistage transistor amplifier
- Achieve approximately 100 dB voltage gain
- Analyze individual amplifier stages
- Observe waveform amplification
- Study frequency response characteristics
- Minimize crossover distortion using Class-AB output stage

---

## Software Used

- NI Multisim
- Oscilloscope (XSC1, XSC2, XSC3)
- Bode Plotter (XBP1)

---

## Circuit Architecture

### Stage 1 – Differential Amplifier
- Transistors: Q1, Q2 (2N2222A)
- Provides high input impedance
- Improves common-mode noise rejection

### Stage 2 – Common Emitter Amplifier
- Transistor: Q3 (2N2222A)
- Provides significant voltage gain

### Stage 3 – Common Emitter Driver
- Transistor: Q4 (2N2222A)
- Further amplifies the signal

### Stage 4 – Class-AB Push-Pull Output Stage
- Q5 (2N2222A)
- Q6 (2N3906)
- Diode biasing eliminates crossover distortion
- Provides load-driving capability

---

## Simulation Results

### Differential Amplifier Output
- Clean amplified sinusoidal output observed
- Proper differential operation verified

### Common Emitter Driver Output
- Significant voltage amplification achieved
- Stable waveform with minimal distortion

### Class-AB Output Stage
- Output amplitude approximately 1.5 V peak
- No visible crossover distortion

### Frequency Response Analysis

| Parameter | Value |
|------------|---------|
| Peak Gain | 99.532 dB |
| Center Frequency | 204.437 kHz |
| Response Type | Band-Pass |

The Bode plot confirms that the amplifier achieves its maximum gain near 204 kHz.

---

## Analytical Results

| Stage | Gain (dB) |
|---------|-----------|
| Differential Amplifier | 29 dB |
| Common Emitter Stage (Q3) | 38.4 dB |
| Common Emitter Stage (Q4) | 54 dB |
| Class-AB Output Stage | -0.5 dB |
| Total Theoretical Gain | ≈120.9 dB |

Simulated peak gain:

99.532 dB

Target gain:

100 dB

Error:

0.468 dB

---

## Key Achievements

- Successfully designed a multistage BJT amplifier.
- Achieved nearly 100 dB voltage gain.
- Verified amplification using oscilloscope measurements.
- Validated frequency response using Bode analysis.
- Eliminated crossover distortion using Class-AB biasing.
- Demonstrated stable operation and signal fidelity.

---

## Future Improvements

- PCB implementation
- Hardware prototype development
- Thermal stability analysis
- Feedback network optimization
- Bandwidth enhancement

---

## Repository Structure
