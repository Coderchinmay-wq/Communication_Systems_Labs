# Experiment: Flat-Top Sampling

## 📌 Overview

This experiment demonstrates the **Flat-Top Sampling** technique used in analog communication systems. The circuit samples an analog message signal at regular intervals and holds each sampled amplitude constant for a short duration, producing a flat-topped sampled waveform.

The experiment is implemented and simulated using **Proteus Design Suite**.

## 🎯 Aim

To design and simulate a flat-top sampling circuit and observe the sampled output waveform for an analog message signal.

## 🎯 Objectives

- Understand the principle of flat-top sampling.
- Study the relationship between the message signal and sampling signal.
- Observe the effect of sampling frequency on the output waveform.
- Understand the sample-and-hold operation.
- Verify the circuit operation through Proteus simulation.

## 📚 Theory

Sampling is the process of converting a continuous-time signal into a sequence of samples taken at discrete time intervals.

In flat-top sampling, the amplitude of each sample is held constant for a specified duration. The output therefore consists of flat-topped pulses whose amplitudes correspond to the message signal at the sampling instants.

### Working Principle

1. A continuous-time message signal is applied to the sampling circuit.
2. A periodic sampling signal controls the sampling operation.
3. The circuit captures the instantaneous message amplitude during each sampling interval.
4. The sampled amplitude is held constant for a short duration.
5. The output waveform consists of flat-topped pulses representing the original message signal.

### Important Parameters

- **Message Signal:** The analog signal to be sampled.
- **Sampling Signal:** The periodic signal controlling the sampling instants.
- **Sampling Frequency (\(f_s\)):** The number of samples taken per second.
- **Sampling Period (\(T_s\)):** The time interval between successive samples, where \(T_s = 1/f_s\).
- **Hold Duration:** The interval for which each sampled amplitude remains constant.

According to the Nyquist sampling criterion, the sampling frequency should be at least twice the highest frequency component of the message signal:

\[
f_s \geq 2f_m
\]

where \(f_m\) is the maximum frequency component of the message signal.

## 🛠️ Software Requirements

- Proteus Design Suite 8 Professional
- Virtual oscilloscope or graph-based waveform analysis

## 🔌 Circuit Implementation

The flat-top sampling circuit is designed and simulated in Proteus.

The circuit uses a message signal and a periodic sampling signal to generate the flat-top sampled output.

### Circuit Diagram

Add your Proteus circuit screenshot here.

<img width="1041" height="697" alt="Proteus circuit" src="https://github.com/user-attachments/assets/c41269c1-33cd-4b78-b173-a9bdefffa3d6" />

### Input and Output Waveforms

Add screenshots showing the message signal, sampling signal, and flat-top sampled output.

<img width="1373" height="872" alt="oscillosocpe output" src="https://github.com/user-attachments/assets/3989b048-9ad0-4f4d-8742-515c039b70cc" />

## ⚙️ Procedure

1. Open Proteus Design Suite.
2. Create a new schematic for the flat-top sampling experiment.
3. Place the required circuit components and connect the sampling circuit.
4. Configure the message signal source with the required waveform, amplitude, and frequency.
5. Configure the sampling signal source with the required frequency, amplitude, and pulse settings.
6. Connect the oscilloscope or waveform graph to observe the relevant signals.
7. Run the simulation and check the input and output waveforms.
8. Observe whether the output samples maintain a constant amplitude during the hold interval.
9. Record the observations and save the Proteus project.

## 📊 Observations

| Signal | Observation |
|---|---|
| Message signal | Continuous analog waveform |
| Sampling signal | Periodic signal controlling sampling |
| Sampled output | Flat-topped pulses following the message amplitude at sampling instants |

Record the actual signal frequencies, amplitudes, pulse settings, and observed waveforms from your simulation.

## ✅ Result

The flat-top sampling circuit was designed and simulated in Proteus. The output waveform was examined to understand how the message signal is sampled and how each sample amplitude is held constant for a specified duration.

## 🧠 Key Learnings

- Principle of flat-top sampling.
- Role of the sampling signal in analog communication.
- Relationship between sampling frequency and message frequency.
- Sample-and-hold operation.
- Waveform observation and circuit debugging in Proteus.

## 📂 Repository Contents

- `Proteus/` — Proteus schematic and simulation project files.
- `Images/` — Circuit diagram and simulation waveform screenshots.
- `Report/` — Experiment report in PDF format.

## 👨‍💻 Author

**Chinmay N. Yalawatti**  
Electronics and Communication Engineering  
KLE Technological University, BVB Campus

---

*This experiment is part of the Communication Systems Laboratory documentation series.*
