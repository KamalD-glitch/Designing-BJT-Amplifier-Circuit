# Designing BJT Amplifier Circuit

## Overview
This project demonstrates the design, simulation, and analysis of a multi-stage Bipolar Junction Transistor (BJT) amplifier circuit. The circuit was created to meet specific design objectives related to gain, input resistance, and output voltage swing, adhering to strict constraints on power supply and component usage.

The design and simulation were conducted using **Multisim**, providing accurate waveform analysis and performance validation.

---

## Course Information
- **Course Title**: Electronic Circuits 1  
- **Course Number**: ELE404  
- **Instructor**: Dr. Fei Yuan  
- **Semester/Year**: Winter 2024  
- **Assignment Title**: Design Project  
- **Submission Date**: April 7, 2024  

---

## Objectives
The design objectives included the following specifications:

1. **Power Supply**: +10V relative to ground.
2. **Quiescent Current**: No larger than 10mA.
3. **No-Load Voltage Gain** (at 1kHz): IAvol = 50 (±10%).
4. **Maximum No-Load Output Voltage Swing** (at 1kHz): No smaller than 8V peak-to-peak.
5. **Loaded Voltage Gain** (at 1kHz and with RL = 1kΩ): No smaller than 90% of the no-load voltage gain.
6. **Maximum Loaded Output Voltage Swing** (at 1kHz and RL = 1kΩ): No smaller than 4V peak-to-peak.
7. **Input Resistance** (at 1kHz): No smaller than 20kΩ.
8. **Amplifier Type**: Inverting or non-inverting.
9. **Transistor Type**: BJT.
10. **Number of Transistors (Stages)**: No more than 3.
11. **Resistances Permitted**: Values smaller than 220kΩ from the E24 series.
12. **Capacitors Permitted**: 0.1μF, 1μF, 2.2μF, 4.7μF, 10μF, 47μF, 100μF, 220μF.
13. **Other Components**: Only components from the ELE404 lab kit.
14. **Source Resistance**: 600Ω for all tests.

---

## Circuit Design

### Configuration:
The amplifier circuit consists of three stages:

- **Stage 1: Common Collector (CC) Amplifier**  
- **Stage 2: Common Emitter (CE) Amplifier**  
- **Stage 3: Common Emitter (CE) Amplifier**  

#### Stage 1: CC Amplifier
The CC amplifier was chosen to meet the required input resistance of greater than 20kΩ. This stage has a high input resistance and a low output resistance, making it ideal for the first stage of amplification.

#### Stages 2 and 3: CE Amplifiers
The CE amplifiers were used in the second and third stages to achieve the required voltage gain. The second stage provides a gain of approximately 5, and the third stage amplifies the signal by a factor of about 10, resulting in a total voltage gain of around 50.

<!---(PASTE THE MULTISIM CIRCUIT SCHEMATIC HERE) -->
---

## Experimental Results

### Stage 1: CC Amplifier
- **Input Voltage (VI)**: 77.79 mV  
- **Output Voltage (VO1)**: 378.39 mV  
- **Experimental Gain**: 4.864 (close to the manual calculation of 5.73)

### Stage 2: CE Amplifier
- **Input Voltage (VI)**: 77.79 mV  
- **Output Voltage (VO1)**: 378.39 mV  
- **Experimental Gain**: 4.864 (roughly consistent with manual gain of 5.73)

### Stage 3: CE Amplifier
- **Input Voltage (VI)**: 378.39 mV  
- **Output Voltage (VO2)**: 4.01V  
- **Experimental Gain**: 10.60 (consistent with manual gain of 12.69)

---

## Conclusion

The experimental results show that the designed BJT amplifier circuit meets the required specifications, with minor discrepancies in the gain values due to distortions observed in the output waveforms. These distortions could be mitigated by adjusting resistance values. Overall, the design is effective in achieving the necessary voltage gain, input resistance, and output swing characteristics.

---
<!---(ADD THE FILES INCLUDED HERE AND CREATE HYPERLINKS TO EACH FILE) -->
